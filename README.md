

##  Title Page
**Assignment Title:** Electric Vehicle Range Prediction using Linear Regression  
**Name:** [K ABHISHEK]  
**Date:** [6/10/25]  
**Course:** [DATA ANALYST - DA17]  

---

##  Introduction
This project analyzes a dataset related to electric vehicles to understand the factors that influence the **Electric Range** of vehicles.  
The objective of this analysis is to build a **Linear Regression Model** that can predict the electric range based on various features such as **Model Year, Base MSRP, and Make**.

The project follows a structured data analysis workflow including data cleaning, exploration, visualization, and model building.



##  Section 1: Data Cleaning
- Checked for and handled **missing values** using appropriate methods (e.g., mean/median imputation or row removal).  
- Removed **duplicate records** to ensure data integrity.  
- Corrected **data type mismatches** and standardized categorical values.  
- Verified consistency across key columns (e.g., Make, Model, Year).

---

##  Section 2: Data Exploration
Explored the dataset to understand key patterns and relationships:
- Summary statistics (mean, median, min, max, std)
- Distribution of numeric features (e.g., Base MSRP)
- Relationship between features and Electric Range
- Identified trends across model years and manufacturers

---

##  Section 3: Data Visualization
Visualizations created using **Matplotlib** and **Seaborn**:
- Histogram: Distribution of Electric Range  
- Line chart: EV adoption by model year
- Scatter Plot: Electric Range vs Base MSRP  
- Bar Chart: Top 5 Ev Makes and model by count  

Each visualization is followed by interpretation of insights.

---

##  Section 4: Linear Regression Model
- **Model Used:** Multiple Linear Regression (from `sklearn.linear_model`)  
- **Features:** Model Year, Base MSRP, Make (encoded)  
- **Target Variable:** Electric Range  
- **Steps:**
  - Encoded categorical variables using `pd.get_dummies()`
  - Split data into training and testing sets (80/20)
  - Trained a Linear Regression model
  - Evaluated performance using:
    - R² Score
    - Mean Squared Error (MSE)
    - Mean Absolute Error (MAE)

**R² Score Interpretation:**  
Indicates how well the model explains the variability of Electric Range — a higher score shows better prediction accuracy.

---

##  Conclusion
- Identified key factors influencing Electric Range.  
- Found a positive relationship between **Base MSRP** and **Electric Range**, suggesting higher-priced EVs tend to have better range.  
- The Linear Regression model provides moderate prediction accuracy.

---

##  Appendix
- Python code files 
- Dataset source and citation <a href="https://catalog.data.gov/dataset/electric-vehicle-population-data">DataSet</a>
- Additional charts and raw output tables 

##  Author
[K ABHISHEK]
- LinkedIn: [https://linkedin.com/in/abhishek-k-78020a383]
- GitHub: [https://github.com/ABHI91827]
- Email: [abhishekkarnam18@gmail.com]

  This project demonstrates end-to-end data analysis and data science workflow including EDA, feature engineering, model building, and business insights generation.

