# Deforestation Monitoring Using Deep Learning and Transfer Learning

## Project Overview

This project presents a deep learning-based approach for automated deforestation monitoring using satellite imagery. Multiple Convolutional Neural Network (CNN) architectures were developed and evaluated to classify environmental land-cover categories from satellite images.

The study compares a Custom CNN model with two transfer learning models, EfficientNetB0 and ResNet50, to determine the most effective approach for environmental image classification.

---

## Project Objectives

- Develop a CNN-based image classification system for deforestation monitoring.
- Compare the performance of a Custom CNN with transfer learning models.
- Evaluate model performance using multiple evaluation metrics.
- Generate visualizations such as ROC curves, accuracy curves, loss curves, and model comparison charts.
- Identify the best-performing model for environmental monitoring applications.

---

## Dataset Information

### Dataset Name
Planets Dataset

### Dataset Source
Kaggle

### Dataset Link
https://www.kaggle.com/datasets/nikitarom/planets-dataset

### Dataset Description

The Planets Dataset contains satellite imagery used for environmental monitoring and land-cover classification. The images represent different geographical and environmental conditions that are useful for identifying deforestation-related patterns.

### Classes Used

- Agriculture
- Artisinal Mine
- Bare Ground
- Blooming
- Blow Down

### Image Type

Satellite Images

### Application Domain

Environmental Monitoring and Deforestation Detection

---

## Methodology

### 1. Data Preprocessing

The following preprocessing techniques were applied:

- Image resizing (224 × 224 pixels)
- Image normalization
- Data augmentation
- Dataset balancing
- Train-validation-test splitting

### 2. Model Development

Three models were developed and evaluated:

#### Model 1: Custom CNN

A CNN architecture built from scratch using:

- Convolution Layers
- Max Pooling Layers
- Dropout Layers
- Fully Connected Layers

#### Model 2: EfficientNetB0

Transfer learning model utilizing pretrained ImageNet weights.

#### Model 3: ResNet50

Transfer learning model utilizing pretrained ImageNet weights with residual connections.

---

## Evaluation Metrics

The models were evaluated using:

- Binary Accuracy
- Loss
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Classification Report

---

## Experimental Results

### Model Performance Comparison

| Model | Binary Accuracy | Loss |
|---------|---------|---------|
| Custom CNN | 0.9518 | 0.1217 |
| EfficientNetB0 | 0.9624 | 0.0977 |
| ResNet50 | 0.9593 | 0.1062 |

### Best Performing Model

EfficientNetB0 achieved the highest classification accuracy and lowest loss among all evaluated models.

### Key Findings

- Transfer learning models outperformed the Custom CNN architecture.
- EfficientNetB0 achieved the highest overall performance.
- ResNet50 demonstrated excellent ROC-AUC performance.
- Deep learning models can effectively support automated environmental monitoring tasks.

---

## Generated Outputs

The project generates:

### Figures

- Accuracy Curves
- Loss Curves
- ROC Curves
- Model Accuracy Comparison
- Model Loss Comparison
- Performance Heatmap

### Tables

- Classification Reports
- Model Comparison Tables
- Error Analysis Tables
- Final Conclusions

### Saved Files

- best_model.csv
- error_analysis.csv
- final_conclusion.csv
- model_accuracy_comparison.pdf
- model_loss_comparison.pdf
- performance_heatmap.pdf
- model_comparison_table.csv

---

## Project Structure

text Deforestation-Monitoring/  │ ├── Notebook_01_Dataset_Preparation.ipynb ├── Notebook_02_Custom_CNN_Model.ipynb ├── Notebook_03_EfficientNetB0_Model.ipynb ├── Notebook_04_ResNet50_Model.ipynb ├── Notebook_05_Model_Comparison_GradCAM_Error_Analysis.ipynb │ ├── outputs/ │   ├── figures/ │   ├── tables/ │   └── models/ │ ├── README.md │ └── requirements.txt 

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- Kaggle Notebooks

---

## How to Run

1. Clone the repository.

bash git clone <repository_link> 

2. Install dependencies.

bash pip install -r requirements.txt 

3. Download the dataset from Kaggle.

4. Update dataset paths in the notebooks.

5. Run notebooks sequentially:

- Notebook 1
- Notebook 2
- Notebook 3
- Notebook 4
- Notebook 5

6. Generated outputs will be saved automatically.

---

## Conclusion

This project demonstrates the effectiveness of deep learning and transfer learning techniques for automated deforestation monitoring using satellite imagery. Experimental results show that transfer learning approaches, particularly EfficientNetB0, provide superior classification performance and can support environmental monitoring and sustainable land management initiatives.

---

## Author

Sayan Kr Dutta

Bachelor of Computer Applications (BCA)

Machine Learning Course Project
