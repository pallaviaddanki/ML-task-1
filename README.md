# task-1
This project demonstrates a complete data preprocessing workflow commonly used in machine learning and data analysis. The steps include handling missing data, encoding categorical variables, feature scaling, and outlier treatment.

# 🧹 Task-1: Data Preprocessing Pipeline

This project demonstrates a complete data preprocessing workflow commonly used in machine learning and data analysis. The steps include handling missing data, encoding categorical variables, feature scaling, and outlier treatment.

## ✅ Steps Performed

1. **Import and Explore Dataset**
   - Loaded dataset using Pandas.
   - Inspected data types, null values, and structure using `.info()`, `.head()`, `.isnull().sum()`.

2. **Handle Missing Values**
   - Replaced missing numerical values using:
     - **Mean** imputation for normally distributed features.
     - **Median** imputation for skewed features.
   - Imputed missing categorical values using **mode**.

3. **Encode Categorical Variables**
   - Used **Label Encoding** and **One-Hot Encoding** for categorical columns.

4. **Normalize/Standardize Features**
   - Applied **StandardScaler** or **MinMaxScaler** to scale numerical features.

5. **Outlier Detection and Removal**
   - Visualized outliers using **boxplots**.
   - Removed outliers using the **IQR (Interquartile Range)** method.

## 🛠️ Tools Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📁 Files in Repository
task-1/
├── README.md # Project description
├── preprocessing.ipynb # Notebook with preprocessing steps
├── data/
│ └── matches.csv # Input dataset (from Kaggle)
└── images/ # Visualizations like boxplots

