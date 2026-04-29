
---

## 🔍 Dataset Overview  

This dataset contains information about players participating in the **IPL 2025 auction**, including their demographics, experience, and pricing details.

- **Total Records:** ~575 players  
- **Type:** Mixed (Numerical + Categorical)  
- **Target Variable:** `Reserve_Price_Numeric`  

---

## 📦 Raw vs Cleaned Dataset  

⚠️ Both **raw and cleaned data exist within the same dataset pipeline** (not separate files).

### 🔹 Raw Dataset  
The original dataset contained:
- Mixed formats (e.g., price in *Cr* and *Lakhs*)  
- Missing values in caps and other features  
- Inconsistent column naming  
- Categorical irregularities  
- Non-numeric values in numeric columns  

---

### 🔹 Data Cleaning Performed  

The dataset was cleaned and transformed using the following steps:

#### ✅ 1. Column Standardization  
- Renamed columns for clarity and consistency  

#### ✅ 2. Price Conversion  
- Converted `Reserve Price` from **Cr/Lakh format → Numeric (Lakhs)**  
- Created new column: `Reserve_Price_Numeric`

#### ✅ 3. Missing Value Handling  
- Numerical → Filled using **median**  
- Categorical → Filled using **mode / logical replacement**

#### ✅ 4. Data Type Correction  
- Converted object columns to numeric using `pd.to_numeric()`

#### ✅ 5. Outlier Handling  
- Detected using **IQR method**  
- Outliers retained (represent real star players)

#### ✅ 6. Feature Engineering  
- Created:
  - `Total_Caps`  
  - `Age_Group`  
  - `Player_Type`

#### ✅ 7. Encoding & Scaling  
- Applied Label Encoding / One-Hot Encoding  
- Standardized numerical features  

#### ✅ 8. Log Transformation  
- Applied `log1p()` on price to reduce skewness  

---

## 📊 Final Cleaned Dataset  

After preprocessing, the dataset became:
- Structured and consistent  
- Free from missing values  
- Suitable for EDA and modeling  
- Optimized for visualization and PCA  

---

## 📈 Key Features  

- Age  
- Role  
- Nationality  
- Test_Caps, ODI_Caps, T20_Caps  
- IPL_Matches  
- Reserve_Price_Numeric (Target Variable)  
- Engineered Features (Total_Caps, Player_Type, etc.)  

---

## 🧠 Key Note  

> The cleaned dataset is generated dynamically within the notebook, ensuring reproducibility and transparency in the data pipeline.

---

## 🧪 Usage  

The dataset is used for:
- Data Cleaning  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Dimensionality Reduction (PCA)  
- Dashboard Visualization  

