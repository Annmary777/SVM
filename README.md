# Breast Cancer Diagnosis using SVM

This project demonstrates the application of Support Vector Machine (SVM) algorithms (Linear and Gaussian RBF kernels) on the Breast Cancer dataset to classify tumors as malignant or benign based on several features.

## 📁 Dataset

The dataset used is `Breast_cancer_data.csv`, which includes the following features:

- mean_radius
- mean_texture
- mean_perimeter
- mean_area
- mean_smoothness
- diagnosis (Target variable: 0 = Benign, 1 = Malignant)

## ✅ Tasks Performed

1. **Data Loading & Exploration**
   - Load CSV file into a DataFrame
   - Identify null values
   - View statistical summary and data types
   - Visualize correlations using heatmap

2. **Data Preprocessing**
   - Features (`X`) and Target (`y`) separated
   - Data split into training (80%) and testing (20%)

3. **Model Building**
   - Linear SVM using `SVC(kernel='linear')`
   - Gaussian RBF SVM using `SVC(kernel='rbf')`

4. **Model Evaluation**
   - Accuracy calculated using `accuracy_score`

## 📊 Results

- **Linear SVM Accuracy**: ~90.35%
- **Gaussian RBF SVM Accuracy**: ~63.15%

## 🚀 How to Run

1. Clone the repo or download the project files.
2. Ensure the dataset `Breast_cancer_data.csv` is placed in the working directory.
3. Run the Jupyter Notebook or Python script.

```bash
python svm_breast_cancer.py
