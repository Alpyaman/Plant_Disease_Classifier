# 🧪 Plant Disease Classifier

A deep learning-based image classification project to detect and classify plant diseases using transfer learning with MobileNetV2.

## 🔍 Dataset

- **PlantVillage Dataset**: A publicly available dataset with labeled plant leaf images.

## 📦 Features

- Uses `MobileNetV2` pretrained on ImageNet
- Image preprocessing, augmentation, and validation split
- Training and fine-tuning phases
- Evaluation via accuracy, loss, and classification report

## 🧠 Model Summary

- Input: 128x128 RGB images
- Output: Softmax across multiple plant disease classes
- Optimizer: Adam
- Loss: Categorical Crossentropy

## 🛠 Installation

```bash
pip install -r requirements.txt
```

## 🚀 Run the Project

Run the Jupyter notebook:
```bash
jupyter notebook plant_disease_classifier.ipynb
```

## 📬 Author

Alpyaman  
[GitHub Profile](https://github.com/Alpyaman)

---

_This project was built and trained using Google Colab and exported for public use._
