---

# Breast Cancer Wisconsin (Diagnostic)

This project uses the Breast Cancer Wisconsin (Diagnostic) dataset to build a machine learning model for predicting whether a tumor is benign or malignant based on various cell features.

## 📁 Project Structure

- `data.csv`: The dataset containing features computed from digitized images of breast mass cell nuclei.
- `test.ipynb`: Jupyter Notebook with data preprocessing, analysis, model training, and evaluation.

## 🧪 Dataset

The dataset includes features such as:
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- ... and more (total 30 features)

Target Variable:
- **Diagnosis**: `M` = Malignant, `B` = Benign

## ⚙️ Methods

The notebook performs the following:
- Data Cleaning & Exploration
- Visualization of Feature Distributions
- Model Building using algorithms like:
  - Logistic Regression
  - Support Vector Machines
  - Random Forest
- Model Evaluation (Accuracy, Confusion Matrix)

## 📊 Results

The best performing model achieves high accuracy in classifying tumors with the dataset.

## 🛠️ Technologies Used

- Python
- Scikit-learn
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook

## 📈 Goal

To provide a machine learning-based diagnostic aid for breast cancer classification, helping reduce diagnostic errors.

## 🔗 References

- [UCI Machine Learning Repository - Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))

---
