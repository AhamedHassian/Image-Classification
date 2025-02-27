# 🖼️ CIFAR-10 Image Classification using CNN 🚀

This project implements a **Convolutional Neural Network (CNN)** to classify images from the **CIFAR-10 dataset** into 10 categories. The dataset contains images of **airplanes, automobiles, birds, cats, deer, dogs, frogs, horses, ships, and trucks**.

---

## 📂 Dataset
The CIFAR-10 dataset consists of:
- **50,000 training images**
- **10,000 testing images**
- **10 classes** (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck)

📌 The dataset is **automatically downloaded** when using `tensorflow.keras.datasets`.

---

## 🛠️ Installation & Requirements
Make sure you have the following installed before running the code:

```bash
pip install tensorflow matplotlib numpy
```

---

## 📜 Code Overview
### 📌 1. Load & Preprocess Data
- Download the **CIFAR-10 dataset**.
- Normalize pixel values between `0` and `1`.
- Visualize the first 25 images.

### 🏗️ 2. Build CNN Model
- **3 Convolutional Layers** (`Conv2D` + `MaxPooling2D`)
- **Flatten layer** to convert features into a vector
- **2 Dense layers** (Fully Connected) with ReLU & Softmax activation

### 🏋️‍♂️ 3. Train the Model
- Loss function: `SparseCategoricalCrossentropy`
- Optimizer: `Adam`
- **Epochs**: 10

### 📊 4. Evaluate Model
- Compute test accuracy
- Plot accuracy & loss graphs 📈

### 🔍 5. Predictions & Visualization
- Model makes predictions on **test images**.
- Correct predictions **(Blue)**, Incorrect **(Red)**.

---

## ▶️ Run the Project
To execute the code, run:

```bash
python image_classification.py
```

---

## 📌 Results
✔️ **Test Accuracy**: ~71.46%  
✔️ Loss & Accuracy plots generated 📊  
✔️ Model successfully predicts CIFAR-10 images! 🎯

---

## 📷 Sample Output
📸 **Example of Test Images with Predictions:**  
🔹 **Blue** = Correct Prediction ✅  
🔸 **Red** = Incorrect Prediction ❌  

---

## 🚀 Future Improvements
🔹 Train for more epochs  
🔹 Use data augmentation  
🔹 Experiment with deeper architectures  

---

## 🤝 Contributing
Feel free to **fork** this repo and contribute! 💡 If you find any issues, open an **issue** or submit a **PR**! 🚀

---

## 📝 License
This project is **open-source** and available under the **MIT License**. 🔓

---
