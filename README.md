# Waste Classification using Machine Learning

## 📌 Project Overview

This project uses **Machine Learning** techniques to classify waste as **Organic** or **Recyclable** based on extracted features from images.

### 🔹 Key Features:

- **Image Preprocessing** using OpenCV
- **Data Augmentation** with `ImageDataGenerator`
- **Deep Learning Model (CNN)** for classification
- **Real-time Accuracy & Loss Monitoring**
- **Evaluation using Confusion Matrix & Sample Predictions**

---

## 📂 Dataset

The dataset is too large to be included in this repository. 📥 [**Download it from Kaggle**](https://www.kaggle.com/datasets/techsash/waste-classification-data/data
)**.**

📁 **Folder Structure (After Extraction):**

```
dataset/
├── Train/
├── Test/
```

---

## 🛠️ Installation & Setup

### 🔹 Step 1: Clone this Repository

```bash
git clone https://github.com/imhomi/Waste_classification.git
cd Waste_classification
```

### 🔹 Step 2: Install Dependencies

Run the following command to install the required libraries:

```bash
pip install tensorflow opencv-python numpy matplotlib seaborn
```

### 🔹 Step 3: Run the Jupyter Notebook

```bash
jupyter notebook wasteclassification.ipynb
```

---

##  Model Architecture

The CNN model consists of: 
✅ **3 Convolutional Layers** (32, 64, 128 filters) for feature extraction  
✅ **Batch Normalization** for stabilizing training  
✅ **MaxPooling Layers** to reduce spatial dimensions  
✅ **Dropout Layers (0.5 rate)** to prevent overfitting  
✅ **Flatten & Dense Layers** for classification  
✅ **Softmax Activation** for categorical classification  

---

##  Training Process & Results

✅ **Training on Augmented Data** using `ImageDataGenerator`  
✅ **Tracking Model Performance** using real-time accuracy/loss plots  
✅ **Confusion Matrix & Classification Report** for evaluation  

---

##  Next Steps

🔹 **Analyze model performance** using different hyperparameters  
🔹 **Test predictions on unseen images**  
🔹 **Optimize CNN by adjusting dropout, learning rate, and filters**  
🔹 **Deploy model for real-world applications**  

---
## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any improvements or features.
