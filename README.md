# 🩺 Breast Cancer Histopathologic Image Classification (CNN)

## 📌 Project Overview  
This project uses a **Convolutional Neural Network (CNN)** to classify **histopathologic breast cancer images** as either **positive (malignant)** or **negative (benign)**.  
The dataset contains microscopic images of breast tissue, labeled `0` (negative) and `1` (positive).  
The goal is to assist in **early detection of breast cancer** using automated image analysis.

---

## ✨ Features
- Binary image classification (**Malignant vs Benign**)
- Data augmentation (rotation, zoom, flips) for improved generalization
- Custom train/validation/test split from raw dataset
- Visualization of training performance (Accuracy & Loss curves)
- Works in both **Google Colab** and **Jupyter Notebook**

---

## 📂 Dataset
- **Source:** [Kaggle Breast Histopathology Images](https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images) or similar dataset
- Original dataset contains images inside `0` and `1` folders (representing negative and positive cases)
- Custom Python script splits the dataset into:
  - `train/` (70%)
  - `val/` (15%)
  - `test/` (15%)


---

## 🛠 Tech Stack
- **Python 3**
- **TensorFlow / Keras**
- **NumPy, Pandas, Matplotlib**
- **scikit-learn** (for splitting dataset)
- **ImageDataGenerator** (for loading & augmenting images)

---

## 🚀 How to Run

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/breast-cancer-cnn.git
cd breast-cancer-cnn

### **Install Dependencies**
pip install tensorflow numpy pandas matplotlib scikit-learn

### **Prepare Dataset**
Download dataset from Kaggle
Place images in the following format:
dataset/
├── 0/
├── 1/

### **Train the Model**
Run in Jupyter Notebook:
jupyter notebook breast_cancer_cnn.ipynb


##**Results**
Achieved 85–95% test accuracy depending on hyperparameters and augmentation.
