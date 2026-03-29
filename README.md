# pet-image-classification-deep-learning
Image classification project using CNNs and transfer learning  (MobileNet, ResNet, EfficientNet) on the Oxford-IIIT Pet dataset.

# Pet Image Classification with Deep Learning

This project focuses on image classification using Deep Learning techniques applied to the Oxford-IIIT Pet Dataset.  
The objective is to compare different convolutional neural network architectures and evaluate their performance.

---

## Problem Description

Image classification is a fundamental task in computer vision.  
In this project, we classify pet images into 37 different categories using both custom CNNs and transfer learning models.

---

## Dataset

We use the **Oxford-IIIT Pet Dataset**, which contains:

- 37 classes (cats & dogs breeds)
- ~7,300 images
- Variations in scale, pose, and lighting
- Includes segmentation masks (not used in this stage)

---

## Models Implemented

The following architectures were trained and evaluated:

- Custom CNN (from scratch)
- MobileNetV2 (Transfer Learning)
- EfficientNetB0 (Transfer Learning)
- ResNet50 (Transfer Learning)

---

## Techniques Used

- Convolutional Neural Networks (CNNs)
- Transfer Learning
- Data Augmentation
- Batch Normalization
- Dropout (Regularization)
- Early Stopping
- Fine-tuning

---

## Results

| Model            | Accuracy |
|------------------|--------- |
| CNN Base         | 6.9%     |
| MobileNetV2      | 80.1%    |
| EfficientNetB0   | 90.26%   |
| ResNet50         | 84.90%   |

## Best model: **EfficientNet**

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- Confusion Matrix

---

## Key Insights

- Transfer learning significantly improves performance over a CNN from scratch.
- EfficientNet and MobileNet showed strong generalization.
- Data augmentation helped reduce overfitting.
- Fine-tuning improved validation performance.

---

## Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/mannyctg/pet-image-classification-deep-learning.git
```

2. Install dependencies:
pip install -r requirements.txt

Open the notebook:
FinalDeepLearning.ipynb

Author

Manuel Alejandro Zuñiga Navarro
Data Analytics/Data Science/Deep Learning

LinkedIn: https://linkedin.com/in/TU_PERFIL
GitHub: https://github.com/TU_USUARIO

---

Final Note

This project showcases end-to-end development of a deep learning solution, from data preprocessing to model evaluation and comparison.

It reflects practical experience in computer vision, transfer learning, and performance analysis, aligning with real-world industry applications.
