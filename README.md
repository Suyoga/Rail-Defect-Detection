# Rail-Defect-Detection
This project focuses on detecting defects inside **MRT coaches** using deep learning models.   It was developed in collaboration with **SBS Transit** as part of an initiative to enhance rail maintenance and inspection processes in Singapore.

##  Objective
To automatically identify and classify potential visual defects (e.g., cracks, surface wear, loose fittings) in MRT coach interiors from inspection imagery.

---

##  Approach

1. **Data Preparation**
   - Image data preprocessing and normalization  
   - Data augmentation to improve robustness  
   - Train-test split using `scikit-learn`

2. **Model Architecture**
   - Transfer learning with **MobileNetV2 (TensorFlow/Keras)**  
   - Custom classification layers fine-tuned for defect detection  
   - Model trained on GPU for efficiency

3. **Evaluation**
   - Classification metrics: accuracy, precision, recall, F1-score  
   - Confusion matrix and detailed performance report  
   - Visualization using **Matplotlib** and **Seaborn**

---

## Technologies Used
- Python  
- TensorFlow / Keras  
- Scikit-learn  
- NumPy  
- Matplotlib & Seaborn  
- PIL (Image Processing)  
- Boto3 (Cloud Storage Integration)

---
