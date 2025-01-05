# 📽️ Action Detection Using ML

**Action Detection Using ML** is a real-time system designed to classify and detect human actions using advanced machine learning techniques. This project leverages the power of sequential modeling to understand and interpret human movements effectively.

---

## 🚀 Features

- **Real-Time Detection**: Capable of processing live video streams for immediate action recognition.
- **Scalable Model**: Expandable to support additional actions beyond the initial implementation.
- **ML-Powered**: Utilizes cutting-edge machine learning algorithms for accurate predictions.
- **Customizable Dataset**: Easily adaptable to new datasets for extended functionality.
- **Robust Feature Extraction**: Employs preprocessed keypoints for consistent and reliable detection.

---

## 📂 Dataset Structure

The dataset includes multiple actions stored as \`.npy\` files, with each file containing preprocessed keypoints:
```
dataset/
├── action_1/
│   ├── file1.npy
│   ├── file2.npy
│   └── ...
├── action_2/
│   ├── file1.npy
│   ├── file2.npy
│   └── ...
└── ...
```


Adding new actions is straightforward—simply extend this structure and update the configuration.

---

## ⚙️ Requirements

Make sure you have the following dependencies installed:

- Python 3.7+
- TensorFlow 2.0+
- NumPy
- Mediapipe
- Matplotlib
- OpenCV 

Install the dependencies with:
\`\`\`bash
pip install tensorflow numpy mediapipe matplotlib opencv-python
\`\`\`

---

## 🛠️ Setup and Usage

### 1️⃣ **Prepare the Dataset**
- Organize the dataset as per the structure above.
- Update the \`DATA_PATH\` variable in the code to point to your dataset's location.

### 2️⃣ **Train the Model**
- Train the ML model on the dataset by running the training script:
  \`\`\`bash
  python train_model.py
  \`\`\`

### 3️⃣ **Test the Model**
- Evaluate the model's accuracy and loss using the test sequences:
  \`\`\`bash
  python test_model.py
  \`\`\`

### 4️⃣ **Real-Time Detection**
- Start real-time action detection:
  \`\`\`bash
  python real_time_recognition.py
  \`\`\`

---

## 🧠 Model Architecture

The ML model is designed for sequential data processing and includes:

- **Input Layer**: Handles preprocessed keypoints.
- **Hidden Layers**: Consist of LSTM layers to capture temporal patterns.
- **Output Layer**: Provides probabilities for each action class.

---

## 📊 Results

- **Accuracy**: 96%
- **Loss**: 0.08
- **Actions Recognized**: 10

---

## 🌟 Future Enhancements

- **Expand Dataset**: Add more actions to increase versatility.
- **Optimize Performance**: Improve model architecture and fine-tune hyperparameters.
- **Mobile/Edge Deployment**: Adapt for low-latency environments.
- **Enhanced Input Handling**: Integrate OpenCV for robust video processing.

---

## 🤝 Contributing

We welcome contributions! To get started:

1. Fork the repository.
2. Create a new branch:
   \`\`\`bash
   git checkout -b feature/your-feature-name
   \`\`\`
3. Make your changes and commit them:
   \`\`\`bash
   git commit -m "Add your message here"
   \`\`\`
4. Push to your branch:
   \`\`\`bash
   git push origin feature/your-feature-name
   \`\`\`
5. Open a pull request.

---

## 📜 License

This project is licensed under the MIT License. See the \`LICENSE\` file for details.

---

## 👨‍💻 Authors

- **Anirudh Mishra**  
  [GitHub Profile](https://github.com/Anirudh112233)  
  [Email Address](mailto:anirudhmishra112233@gmail.com)

---

### 🌟 Star this repository if you find it helpful! 🌟
