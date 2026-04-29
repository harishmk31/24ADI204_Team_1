
---

## 📌 Notebook Overview  

This notebook contains the **complete data science workflow** for analyzing the IPL 2025 auction dataset.  
It covers all stages from raw data processing to insight generation and visualization.

---

## 🔄 Workflow Covered  

### 🔹 1. Data Loading  
- Loaded dataset using Pandas  
- Initial inspection using `head()`, `info()`, `describe()`  

---

### 🔹 2. Data Cleaning  
- Removed unnecessary rows and columns  
- Converted reserve price into numeric format (Lakhs)  
- Handled missing values (Median & Mode)  
- Corrected inconsistent data types  
- Verified dataset integrity  

---

### 🔹 3. Exploratory Data Analysis (EDA)  
- **Univariate Analysis:** Distribution of age, price, roles  
- **Bivariate Analysis:** Relationship between features and price  
- Visualizations:
  - Histogram  
  - Box Plot  
  - Scatter Plot  
  - Bar Chart  

---

### 🔹 4. Correlation Analysis  
- Generated correlation matrix  
- Identified relationships among numerical features  
- Reduced redundancy using feature insights  

---

### 🔹 5. Feature Engineering  
- Created new features:
  - `Total_Caps`  
  - `Age_Group`  
  - `Player_Type`  
- Applied encoding (Label & One-Hot)  
- Performed scaling (Standardization)  

---

### 🔹 6. Data Transformation  
- Applied **log transformation** to handle skewness  
- Improved data distribution  

---

### 🔹 7. Dimensionality Reduction  
- Applied **Principal Component Analysis (PCA)**  
- Reduced feature dimensionality  
- Visualized principal components  

---

### 🔹 8. Visualization & Insights  
- Generated plots for understanding patterns  
- Identified pricing trends and player characteristics  

---

## 📊 Key Outputs  

- Cleaned dataset ready for analysis  
- Visualizations showing data distribution and relationships  
- Correlation matrix  
- PCA plots  
- Key insights for player valuation  

---

## 🛠️ Libraries Used  

- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🧪 How to Run  

1. Install required libraries:
2. Open the notebook in Jupyter/Colab  
3. Run all cells sequentially  

---

## 🧠 Key Highlights  

- End-to-end data science pipeline implemented  
- Real-world dataset handling  
- Feature engineering and dimensionality reduction  
- Strong focus on visualization and insights  

---

## 📌 Note  

> The notebook is structured step-by-step to ensure clarity, reproducibility, and alignment with the final report and dashboard.
