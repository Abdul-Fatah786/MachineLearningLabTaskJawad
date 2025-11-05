# 🏠 House Price & Category Prediction

A comprehensive Machine Learning project demonstrating both **regression** and **classification** models on house pricing data.

## 📋 Project Overview

This project implements two machine learning models:
1. **Linear Regression** - Predicts continuous house prices (SalePrice)
2. **Random Forest Classifier** - Classifies houses into price categories (Low, Medium, High)

## 🎯 Objectives

- Demonstrate end-to-end machine learning workflow
- Implement data preprocessing and feature engineering
- Train and evaluate regression and classification models
- Compare model performance using appropriate metrics

## 📊 Dataset

- **Source**: Kaggle "House Prices: Advanced Regression Techniques"
- **File**: `train.csv`
- **Size**: 1000 samples, 44 features
- **Target Variables**: 
  - SalePrice (continuous) - for regression
  - Price_Category (Low/Medium/High) - for classification

## 🛠️ Technologies Used

- **Python 3.x**
- **Libraries**:
  - pandas - Data manipulation
  - numpy - Numerical computing
  - scikit-learn - Machine learning models and tools
  - matplotlib/seaborn - Data visualization (optional)

## 📁 Project Structure

```
JawadML/
│
├── House_Price_Prediction.ipynb    # Main Jupyter notebook with complete code
├── train.csv                        # Dataset
├── Lab_Report_Complete.html         # HTML report with code and outputs
├── README.md                        # Project documentation
└── .gitignore                       # Git ignore file
```

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy scikit-learn jupyter
```

### Running the Project

1. Clone the repository:
```bash
git clone https://github.com/yourusername/JawadML.git
cd JawadML
```

2. Open the Jupyter notebook:
```bash
jupyter notebook House_Price_Prediction.ipynb
```

3. Run all cells or execute them sequentially

## 📈 Methodology

### 1. Data Loading & Exploration
- Load dataset from CSV
- Initial data analysis
- Check data types and structure

### 2. Data Preprocessing
- Handle missing values (median for numerical, 'None' for categorical)
- Create target variable 'Price_Category' using `pd.cut()`
- Separate features and targets

### 3. Feature Engineering
- One-Hot Encoding for categorical variables
- Feature scaling using StandardScaler

### 4. Model Training

**Regression Model:**
- Algorithm: Linear Regression
- Features: Scaled numerical and encoded categorical features
- Target: SalePrice

**Classification Model:**
- Algorithm: Random Forest Classifier
- Features: Same as regression
- Target: Price_Category (Low/Medium/High)

### 5. Model Evaluation

**Regression Metrics:**
- R-squared (R²) Score
- Root Mean Squared Error (RMSE)

**Classification Metrics:**
- Accuracy Score
- Confusion Matrix

## 📊 Results

The project demonstrates successful implementation of:
- ✅ Complete data preprocessing pipeline
- ✅ Feature engineering with categorical encoding
- ✅ Train-test split (70/30 ratio)
- ✅ Model training for both regression and classification
- ✅ Comprehensive evaluation metrics

*Note: Specific metrics will vary based on dataset and random state.*

## 📝 Key Features

- **Comprehensive Pipeline**: End-to-end ML workflow from data loading to evaluation
- **Dual Model Approach**: Both regression and classification in one project
- **Professional Code**: Well-documented, structured, and reusable
- **Detailed Evaluation**: Multiple metrics for thorough performance assessment

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 📄 License

This project is open source and available for educational purposes.

## 👤 Author

**Muhammad Jawad**
- Roll Number: [Your Roll Number]
- GitHub: [@yourusername](https://github.com/yourusername)

## 🙏 Acknowledgments

- Dataset: Kaggle House Prices Competition
- Course: Machine Learning Lab
- Institution: [Your Institution Name]

---

⭐ If you found this project helpful, please consider giving it a star!
