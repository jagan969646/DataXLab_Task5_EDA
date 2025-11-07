# 🛒 Superstore Sales - Exploratory Data Analysis (EDA)

### 🎯 Objective
The goal of this project is to perform **Exploratory Data Analysis (EDA)** on the **Superstore Sales dataset** to uncover business insights, identify trends, detect outliers, and understand relationships between sales, discounts, and profits across different regions and categories.

---

### 📁 Dataset Information
- **Name:** Superstore Sales Dataset  
- **Source:** Kaggle (https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)  
- **Rows:** ~10,000  
- **Columns:** 13  
- **Domain:** Retail / E-commerce  

**Key Features**
- `Order ID`, `Order Date`, `Ship Date`, `Ship Mode`
- `Segment`, `Country`, `Region`, `Category`, `Sub-Category`
- `Sales`, `Quantity`, `Discount`, `Profit`

---

### ⚙️ Technologies Used
- **Programming Language:** Python  
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `statsmodels`  
- **Environment:** Jupyter Notebook / VS Code  

---

### 📊 Steps Performed
1. **Data Loading & Inspection**  
   - Checked dataset shape, data types, duplicates, and missing values.

2. **Data Cleaning**  
   - Handled missing and duplicate records, corrected data types, formatted dates.

3. **Univariate Analysis**  
   - Distribution plots (Sales, Profit, Discount, Quantity)  
   - Frequency counts for categorical variables.

4. **Bivariate Analysis**  
   - Sales vs Profit  
   - Category-wise and Region-wise performance  
   - Discount vs Profit relationship  

5. **Multivariate Analysis**  
   - Correlation heatmap, pairplot, and VIF analysis to detect multicollinearity.

6. **Outlier & Skewness Handling**  
   - Identified outliers using IQR method  
   - Applied log transformations for right-skewed data.

7. **Summary of Findings**  
   - Highlighted key trends and actionable business insights.

---

### 🔍 Key Insights
- **High discounts** negatively impact profit margins.  
- **Technology** category generates the highest profits.  
- **Furniture** (especially Tables) shows frequent losses.  
- **West** and **East** regions perform better than **South**.  
- **Standard shipping** is used in most orders, suggesting a potential upsell for faster delivery modes.

---

### 💡 Recommendations
- Optimize discount strategy to improve profitability.  
- Prioritize marketing and inventory in high-performing regions.  
- Investigate loss-making categories (Furniture) for supplier or pricing issues.  
- Encourage higher-margin segments through personalized offers.

---

### 📦 Folder Structure
