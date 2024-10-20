# PRODIGY_ML_04

### **Project Overview**
This project involves building a **hand gesture recognition model** using Convolutional Neural Networks (CNNs) to classify hand gestures from image/video data. The goal is to improve **human-computer interaction** through gesture-based control systems for various applications, such as **gaming** and **assistive technologies**.

### **Dataset**
The dataset comes from the **Leap Gestures Dataset** on Kaggle. It includes diverse hand gestures like palm, thumb, and index finger, captured in different positions and lighting conditions.

### **Model Architecture**
- **CNN (Convolutional Neural Network)** with:
  - **Conv2D layers** (ReLU activation)
  - **Max Pooling layers** for down-sampling
  - **Dropout layers** to prevent overfitting
  - **Dense layers** for classification
- **Trainable parameters**: 1,649,280
- **Non-trainable parameters**: 0

### **Training and Validation**
- **Epochs**: 7
- **Batch size**: 32
- **Training accuracy**: Above 99%
- **Validation accuracy**: Slightly lower, indicating good generalization.

### **Steps to Run the Project**
1. **Clone the repository** and install dependencies from `requirements.txt`.
2. **Download the dataset** from Kaggle and extract it.
3. **Train the model** using `train_model.py`.
4. **Test the model** with new gesture data using `test_model.py`.

### **References**
- Dataset: [Leap Gestures Dataset on Kaggle](https://www.kaggle.com/datasets/gti-upm/leapgestrecogv

