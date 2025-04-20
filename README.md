
---

## 📊 Problem Overview

- **Task**: Binary classification — classify image patches (96x96) as:
  - `1` = Contains metastatic tissue
  - `0` = Normal tissue
- **Dataset**: ~220,000 labeled training images
- **Challenge**: Small patch sizes, class imbalance, subtle differences

---

## 🔍 Approach

- Performed Exploratory Data Analysis (EDA) to understand class distribution and sample patterns
- Built and trained models using Keras/TensorFlow
- Compared simple ANN and CNN-based architectures
- Evaluated performance using accuracy, AUC, and confusion matrix
- Performed model tuning and tested augmentation strategies

---

## 🧠 Model Highlights

- ✅ Baseline: Flattened ANN with Dense layers
- ✅ Enhanced ANN: Added Dropout and BatchNormalization
- ✅ CNN: Introduced convolutional layers for spatial features
- ✅ Transfer Learning (optional): Experiments with ResNet, EfficientNet

---

## 📈 Results

- Training and validation accuracy tracked over epochs
- Kaggle submission with performance screenshot included
- Model comparison, tuning summary, and conclusions in notebook

---
