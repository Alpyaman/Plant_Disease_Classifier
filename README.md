# 🧪 Plant Disease Classifier

A deep learning-based image classification project to detect and classify plant diseases using transfer learning with MobileNetV2.

---

## 📊 Final Scores

| Phase                 | Train Accuracy | Val Accuracy |
|----------------------|----------------|--------------|
| CNN (custom)         | ~85.8%         | ~90.6%       |
| MobileNetV2 (frozen) | ~94.5%         | ~93.3%       |
| MobileNetV2 (finetuned) | ~91.9%      | **93.5%**     |

---

## 🔍 Dataset

- **PlantVillage Dataset**: A publicly available dataset with labeled plant leaf images.

---

## 🧠 Features

- Uses `MobileNetV2` pretrained on ImageNet
- Image preprocessing, augmentation, and validation split
- Training and fine-tuning phases
- Evaluation via accuracy, loss, and classification report
- Visualizations of training history included

---

## 📈 Training Curves

> These plots are from my Google Colab outputs.

![Frozen Training](mobilenetv2_frozen_accuracy.png)  
*Training/Validation Accuracy - MobileNetV2 Frozen*

![Finetuned Training](mobilenetv2_finetuned_accuracy.png)  
*Training/Validation Accuracy - MobileNetV2 Fine-tuned*

---

## Extra Visualizations

> Initial Model Accuracy

![Initial Model Accuracy](Initial_Model_Accuracy.png)

> Initial Model Loss

![Initial Model Loss](Initial_Model_Loss.png)

> Initial Model Confusion Matrix

![Initial Confusion_Matrix](Initial_Confusion_Matrix.png)

> MobileNetV2 Confusion Matrix

![MobileNetV2 Confusion Matrix](Confusion_Matrix_MobileNetV2.png)

---

## 🛠 Installation

```bash
pip install -r requirements.txt
```

---

## 🚀 Run the Project

Run the Jupyter notebook:

```bash
jupyter notebook plant_disease_classifier.ipynb
```

---

## 📬 Author

Alpyaman  
[GitHub Profile](https://github.com/Alpyaman)

---

_This project was built and trained using Google Colab and exported for public use._
