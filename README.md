# Credit-Scoring-and-Segmentation-Analysis

**Author**: *Chioma Kamalu*  
**Last Updated**: 24 February  

## 📘 Project Overview

This project demonstrates an end-to-end analysis of **credit scoring** and **segmentation** using a synthetic dataset of 1,000 entries. Credit scoring is a critical aspect of financial risk analysis, helping organizations assess the creditworthiness of individuals. The project also explores segmentation based on credit scores to categorize individuals into risk-based clusters.

---

## 🏆 Objectives
1. **Understand Credit Scoring Factors**:  
   Examine key factors influencing credit scores, including:
   - Credit Utilization Ratio
   - Payment History
   - Number of Credit Accounts
   - Education Level
   - Employment Status

2. **Visualize Distributions and Trends**:  
   Use visualizations to analyze features like:
   - Distribution of credit utilization ratios and loan amounts.
   - Correlation between different variables.

3. **Calculate Credit Scores**:  
   Utilize a custom formula based on **FICO scoring principles** to calculate credit scores for each individual.

4. **Customer Segmentation**:  
   Perform segmentation using **K-Means clustering** to group customers based on their credit scores into categories:
   - Excellent
   - Good
   - Low
   - Very Low

5. **Generate Insights**:  
   Provide actionable insights for understanding customer creditworthiness and risk segmentation.

---

## 📂 Dataset Overview
- **Source**: Synthetic Dataset
- **Shape**: 1,000 entries × 12 features
- **Key Columns**:
  - `Age`, `Gender`, `Marital Status`, `Education Level`, `Employment Status`
  - `Credit Utilization Ratio`, `Payment History`, `Loan Amount`, etc.
- **Target Output**: Calculated `Credit Score` and segmented customer `Category`.

---

## 🛠️ Features and Tools
- **Libraries Used**:
  - `pandas` and `numpy` for data manipulation
  - `matplotlib` and `seaborn` for visualization
  - `plotly` for interactive charts
  - `sklearn` for machine learning (clustering)

- **Analysis Steps**:
  1. **Data Loading and Cleaning**:
     - Verify dataset shape, structure, and handle missing values.
  2. **Feature Engineering**:
     - Map categorical features to numeric values.
     - Calculate credit scores using a weighted formula.
  3. **Exploratory Data Analysis**:
     - Visualize data distributions and correlations.
  4. **Segmentation**:
     - Apply K-Means clustering to categorize credit scores.
     - Visualize segments and analyze mean credit scores for each category.

---

## 📊 Key Outputs
1. **Credit Score Distribution**:
   - Visualized using histograms and box plots.
2. **Segmentation Insights**:
   - Scatter plots of credit scores grouped by segment.
   - Statistical summaries of segments.
3. **Cluster Labels**:
   - Map cluster indices to descriptive categories (e.g., "Excellent").

---

## 🚀 How to Use
1. **Prerequisites**:
   - Install the required Python libraries: `pandas`, `numpy`, `plotly`, `seaborn`, and `sklearn`.
2. **Run the Notebook**:
   - Execute cells sequentially for a complete analysis.
3. **Modify for Your Needs**:
   - Replace the dataset with your own credit data for similar insights.
   - Adjust parameters in the credit score formula or clustering for domain-specific use cases.

---

## 🔍 Insights and Applications
- **Financial Insights**: Identify high-risk vs. low-risk customers for targeted interventions.
- **Credit Limit Decisions**: Assist in determining creditworthiness thresholds.
- **Marketing and Retention**: Tailor financial products to customer segments.

---

Feel free to fork this repository or reach out for any clarifications or improvements!
