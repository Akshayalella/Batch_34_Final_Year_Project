# Deep Learning-Based Classification of Alzheimer's and Parkinson's Disease Using Brain MRI Images

## Project Description

This project focuses on classifying Alzheimer's disease and Parkinson's disease using brain MRI images and deep learning techniques. The main objective is to develop a model that can learn relevant image features and classify MRI images into different disease-related categories.

We collected and combined Alzheimer's and Parkinson's MRI datasets to create a six-class classification dataset. The images were checked for readability, converted to grayscale, resized to 224 × 224 pixels, and normalized to the range 0–1.

A **Basic Convolutional Neural Network (CNN)** was implemented and trained as the initial model. The model achieved a test accuracy of **67.12%** and a best validation accuracy of **71.02%**. Further work is in progress to improve classification performance by exploring advanced deep-learning and transfer-learning models and evaluating their ability to generalize to independent datasets.

## Datasets

### 1. Alzheimer's MRI Dataset
- **Total images:** 6,400
- **Categories:**
  - MildDemented
  - ModerateDemented
  - NonDemented
  - VeryMildDemented

### 2. Parkinson's MRI Dataset
- **Total images:** 4,990
- **Categories:**
  - Normal
  - Parkinson's Disease (PD)

### 3. Combined Dataset
- **Total images:** 11,390
- **Total categories:** 6
- All images were checked for readability.
- No corrupted images were found.

### 4. Data Splitting

The combined dataset was divided into training, validation, and testing sets using stratified splitting to maintain class distribution.

| Dataset split | Percentage | Number of images |
|---|---:|---:|
| Training | 70% | 7,973 |
| Validation | 15% | 1,708 |
| Testing | 15% | 1,709 |
| **Total** | **100%** | **11,390** |

### 5. Image Preprocessing
- Converted images to grayscale.
- Resized images to **224 × 224 pixels**.
- Normalized pixel values to the range **0–1**.

### Current Project Status

The Basic CNN has been implemented and evaluated as a baseline. Further experiments with advanced models and performance improvements are currently in progress.

**Note:** This is an academic research project and is not a clinically validated diagnostic system.
