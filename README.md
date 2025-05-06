# Income Prediction AI Project

## 📄 Overview
This project aims to predict income levels using various machine learning classification models. The workflow includes extensive data preprocessing, feature selection, model training, evaluation, and a performance comparison across different classifiers.

## 🚀 Features
- Data Cleaning and Preprocessing
- Feature Engineering and Scaling
- Outlier Detection and Removal
- Feature Selection (Chi-Square, Mutual Information, Kendall’s Tau)
- Machine Learning Classification (Decision Tree, SVM, Logistic Regression)
- Model Evaluation and Performance Comparison
- Final Report Documentation

## 📂 Project Structure

## 🛠️ Tech Stack
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- SciPy

## 🔎 Project Details

### 1. Data Preprocessing
- **Libraries Used**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SciPy
- **Data Handling**: Loading and concatenating training/testing datasets.
- **Missing Values**: Replaced missing categorical values (" ?") with column modes.
- **Categorical Variables**: Converted into numerical codes.
- **Feature Scaling**: Applied MinMaxScaler for scaling features.
- **Outlier Detection and Removal**: Used the IQR method and median replacement.

### 2. Feature Selection
- **SelectKBest with Chi-Square**: Top 10 features selected.
- **Mutual Information**: Calculated feature importance scores.
- **Kendall's Rank Correlation Coefficient**: Selected features based on correlation values.

### 3. Classification Models
- **Decision Tree Classifier**:
  - Criterion: Entropy
  - Max Depth: 3
  - Accuracy: 84%
- **Support Vector Machine (SVM)**:
  - Models with different `C` values (1 and 33)
  - Best Accuracy: **85%**
- **Logistic Regression**:
  - Tolerance: 0.0001
  - `C` Value: 100
  - Accuracy: 82%

### 4. Performance Summary
- **Best Model**: Support Vector Machine (SVM)
- **Highest Accuracy Achieved**: 85%

## 📊 Metrics Used
- Accuracy Score
- Classification Report (Precision, Recall, F1-Score)

## 🔥 How to Run
1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/income-prediction.git
cd income-prediction
