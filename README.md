# 12-Class Garbage Classification Using MobileNetV2

This repository contains the Deep Learning implementation using the MobileNetV2 architecture to automatically classify 12 types of waste based on visual features. This project was developed by Group 10 to fulfill the requirements for the SSI course at BINUS University.

## 📊 Dataset Information

This project utilizes a publicly available dataset hosted on Kaggle:

- **Dataset Name:** Garbage Classification (12 Classes)
- **Dataset Author:** Mostafa Abla
- **Dataset Link:** [Kaggle Garbage Classification Dataset](https://www.kaggle.com/datasets/mostafaabla/garbage-classification)

### Dataset Description

The dataset is specifically designed for benchmarking computer vision models in recognizing waste objects to support automated recycling systems. It consists of a total of **15,515 images** distributed across 12 discrete categories:

1. **Battery** (945 images)
2. **Biological** (985 images)
3. **Brown-glass** (607 images)
4. **Cardboard** (891 images)
5. **Clothes** (5,325 images) - _Majority Class_
6. **Green-glass** (629 images)
7. **Metal** (769 images)
8. **Paper** (1,050 images)
9. **Plastic** (865 images)
10. **Shoes** (1,977 images)
11. **Trash** (697 images)
12. **White-glass** (775 images)

## 🚀 Final Model Performance

After undergoing a systematic _Hyperparameter Tuning_ phase (utilizing a Learning Rate of `0.0001`, a Dropout rate of `0.4`, and cost-sensitive `class_weight` balancing), the model successfully achieved:

- **Global Accuracy (Evaluation Data):** **90%**
- **Curve Characteristic:** _Good Fit_ (Stable convergence between training and validation curves without signs of overfitting).
