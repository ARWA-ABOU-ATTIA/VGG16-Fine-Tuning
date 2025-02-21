# 🐶🐱 Fine-Tuning `VGG16` for Cats & Dogs Classification  

🚀 **Fine-Tuning a Pre-Trained CNN for Image Classification**  
This project focuses on modifying and fine-tuning a **pre-trained VGG16 model** to classify images of cats and dogs. It incorporates **Transfer Learning**, **Data Augmentation**, and **Hyperparameter Optimization** to enhance model performance.  

📌 This is part of an **exercise assigned by Dr. Noha** to apply fine-tuning on pre-trained CNN models for a specific case study.  

---

## 🌟 Key Features  
✅ **Uses VGG16 as a base model** with additional custom layers  
✅ **Fine-tuned specific layers** to adapt to our dataset  
✅ **Applied Data Augmentation** to prevent overfitting  
✅ **Evaluated performance using Confusion Matrix & Classification Report**  
✅ **Experimented with different learning rates and optimizers**  

---

## 📌 Model Architecture  

### **🧩 Base Model (Before Modifications)**  
The original VGG16 model used as a feature extractor:  
![Base Model Summary](https://github.com/user-attachments/assets/1add889c-a07c-4641-bb83-f31dc1c498d7)  

### **🔧 Fine-Tuned Model (After Modifications)**  
After applying custom layers, unfreezing selective layers, and tuning hyperparameters:  
![Fine-Tuned Model Summary](https://github.com/user-attachments/assets/2e831e21-c7c6-49ac-8010-6aad7d5c5e8d)  

---

## 📥 Installation & Usage  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/ARWA-ABOU-ATTIA/VGG16-Fine-Tuning
cd VGG16-Fine-Tuning
```

### **2️⃣ Install Dependencies**  
Ensure you have the required packages installed:  
```bash
pip install tensorflow keras numpy matplotlib scikit-learn
```

### **3️⃣ Train the Model**  
Run the following command to train the model:  
```bash
python train.py
```

### **4️⃣ Test the Model**  
Classify new images by running:  
```bash
python predict.py --image sample.jpg
```

---

## 📊 Results  

### **Confusion Matrix**  
The model's performance can be visualized using the confusion matrix:  
![confusion_matrix](https://github.com/user-attachments/assets/88bac5dc-391b-4c57-b01e-96e504ae4aa8)


### **Classification Report**  
```
              Precision    Recall  F1-score   Support
       Cats       0.50      0.54      0.52      2500
       Dogs       0.50      0.46      0.47      2500
    Accuracy                           0.50      5000
```
✅ **Final Accuracy: ~50%** → Room for improvements!  

---

## 🚀 Areas for Improvement  
- **Experiment with different architectures** (EfficientNet, Vision Transformers)  
- **Optimize hyperparameters** (learning rate, batch size)  
- **Fine-tune additional layers** for better feature extraction  
- **Address class imbalance** to enhance model generalization  
---

## 🤝 Contributing  
Contributions are welcome! Feel free to **open an issue** or **submit a pull request**. 🎯  

📩 **Contact:**  
[📧 Email](mailto:arwaabouattia@gmail.com)  
```
