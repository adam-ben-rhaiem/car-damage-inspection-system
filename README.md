
# 🚗 Car Damage Inspection System

## 📌 Overview
This application is designed to **automatically detect car damage** and classify which parts are affected using deep learning. It's a step towards automating insurance claims, reducing human error, and accelerating inspection workflows.

🔍 **Key Features:**
- Classification of damaged car parts using images  
- Comparison between three different CNN models:
  - ✅ MobileNetV2
  - ✅ VGG16
  - ✅ Custom CNN (built from scratch)

---

## 📂 Dataset

We used a publicly available dataset from Kaggle for training and evaluation:

🔗 [Car Damage Assessment Dataset (Kaggle)](https://www.kaggle.com/datasets/hamzamanssor/car-damage-assessment)

---

## 🧠 Models and Results

### 1️⃣ MobileNetV2
> A lightweight yet powerful convolutional neural network suitable for mobile and embedded vision applications.

**📊 Validation vs Training Accuracy**  
![MobileNetV2 Accuracy](https://github.com/user-attachments/assets/2146cff4-7f6f-4daa-990f-b9f9cc88365b)

**📉 Validation vs Training Loss**  
![MobileNetV2 Loss](https://github.com/user-attachments/assets/9bbcd9d7-8a9f-4c6b-ae3a-fe5290ac28c8)

**🧾 Classification Report**  
![MobileNetV2 Report](https://github.com/user-attachments/assets/945222c2-01a8-4da9-820f-e18bb1670e83)

**🧪 Test Loss & Accuracy**  
![MobileNetV2 Test](https://github.com/user-attachments/assets/43642dac-47c7-47dc-b86f-f7ea70a6c41a)

---

### 2️⃣ VGG16
> A deep CNN architecture with 16 layers, known for its simplicity and effectiveness in image classification.

**📊 Validation vs Training Accuracy**  
![VGG16 Accuracy](https://github.com/user-attachments/assets/7ef19266-9124-482f-bab3-6513ee649d99)

**📉 Validation vs Training Loss**  
![VGG16 Loss](https://github.com/user-attachments/assets/2c67c4b7-f8ea-4601-bea8-b7afa54b9137)

**🧾 Classification Report**  
![VGG16 Report](https://github.com/user-attachments/assets/b5788d3f-b2be-4683-aa39-9b0f1b3fce8c)

**🧪 Test Loss & Accuracy**  
![VGG16 Test](https://github.com/user-attachments/assets/50731dd2-b3e0-4711-a8ca-8e9e58e3ac30)

---

### 3️⃣ CNN from Scratch
> A custom lightweight convolutional neural network trained from the ground up.

**📊 Validation vs Training Accuracy**  
![Custom CNN Accuracy](https://github.com/user-attachments/assets/9f66a661-2dff-4339-9ec2-03af12a4ab28)

**📉 Validation vs Training Loss**  
![Custom CNN Loss](https://github.com/user-attachments/assets/acb9ed5c-f8d3-4a43-96ab-ab8d02ffe6ae)

**🧾 Classification Report**  
![Custom CNN Report](https://github.com/user-attachments/assets/7a02e878-8f6a-4569-8c4f-098e02ee0351)

**🧪 Test Loss & Accuracy**  
![Custom CNN Test](https://github.com/user-attachments/assets/2ab379ef-3840-4f62-8586-f22b04ecfa78)

---

## 🚀 Future Work
- Integration with mobile applications (real-time damage detection)
- Bounding box prediction for object localization
- Multi-label classification for complex damage scenarios

---

## 📬 Contact
For questions, contributions, or collaborations:

**Ils — Data Scientist & AI Developer**  
📧 Email: [your-email@example.com]  
🌐 GitHub: [your-github-profile-link]



