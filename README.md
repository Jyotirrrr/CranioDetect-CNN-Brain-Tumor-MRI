
---

## 📚 Dataset

- MRI brain scan dataset obtained from Kaggle.
- Contains two folders:
  - `yes/`: Brain MRIs with tumors
  - `no/`: Normal brain MRIs

---

## ⚙️ Tech Stack

- **Languages**: Python  
- **Libraries**: TensorFlow, Keras, NumPy, Matplotlib, PIL  
- **Tools**: Jupyter Notebook, Google Colab  

---

## 🧠 Model Architecture

The model uses a custom **Convolutional Neural Network (CNN)** with the following layers:
- Conv2D + ReLU
- MaxPooling2D
- Dropout (to reduce overfitting)
- Flatten + Dense layers
- Sigmoid output for binary classification

---

## 📈 Results

| Metric              | Value         |
|---------------------|---------------|
| Training Accuracy    | ~99.5%        |
| Validation Accuracy  | ~98.5%        |
| Model Type           | Custom CNN    |
| Loss Function        | Binary Crossentropy |

---

## 📊 Sample Visualizations

> Training Accuracy & Loss Curves

![Training Graph](https://i.imgur.com/NnWhzUH.png)  
*Note: Replace with your actual training graph if needed.*

---

## 🚀 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CranioDetect-CNN-Brain-Tumor-MRI.git
   cd CranioDetect-CNN-Brain-Tumor-MRI
