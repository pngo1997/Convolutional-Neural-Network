# 🏆 Intel Image Classification with CNNs  

## 📜 Overview  
This project focuses on **experimenting with Convolutional Neural Networks (CNNs)** to classify images from the **Intel Image Classification** dataset. The dataset consists of **17,000 color images (150x150 pixels)** across **6 categories**:  
- 🏢 **Buildings**  
- 🌲 **Forest**  
- ❄️ **Glacier**  
- ⛰️ **Mountain**  
- 🌊 **Sea**  
- 🏙️ **Street**  

📌 **Goals**:  
1. **Train a CNN from scratch** to classify images.  
2. **Experiment with different model architectures and hyperparameters**.  

## 🏗️ Model Development & Hyperparameter Tuning  
✅ **Data Augmentation is permitted.**  

### **Model Hyperparameters to Experiment With**  
- **Convolutional Layers**:  
  - 🏗️ Number of layers  
  - 🎛️ Filter size (e.g., 3x3, 5x5, 7x7)  
  - 🔍 Number of filters  
- **Fully Connected Layers**:  
  - 💡 Number and size of layers  
- **Regularization Techniques**:  
  - 🔄 Dropout layers & percentages  
  - 📏 L1/L2 Regularization  
  - 📊 Batch Normalization  

### **Training Hyperparameters**  
- 🎯 **Learning rate**  
- 🎭 **Regularization method**  
- 🎲 **Dropout percentage**  
- 📦 **Mini-batch size**  

📌 **Goal**: Experiment with **different configurations** and analyze their impact on model performance.  

## 📊 3️⃣ Model Evaluation  
- **Loss Function**: `categorical_crossentropy`  
- **Evaluation Metric**: `log_loss` (log likelihood)  

### **Other Performance Considerations**  
✅ **Model Complexity** (Fewer parameters = faster inference)  
✅ **Computational Efficiency** (Training time & memory usage)  
✅ **Learning Stability** (Smooth convergence vs. overfitting)  

## 📌 Summary  
✅ Built a CNN from scratch for Intel Image Classification.

✅ Experimented with different model architectures & hyperparameters.
