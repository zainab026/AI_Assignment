# AI_Assignment
Linear Regression project predicting salaries
# AI Assignment: Linear Regression Project

## 1. Project Title
**Predicting Employee Salaries Using Linear Regression**

---

## 2. Introduction
This project demonstrates the application of **Linear Regression**, a fundamental supervised machine learning technique, to predict employee salaries based on a job dataset.  
The primary objective is to analyze the relationship between a candidate’s **Age** and their **Average Salary (K)**, and build a model capable of predicting salaries accurately.  

Linear Regression models the relationship between a dependent variable (target) and one or more independent variables (features) by fitting a linear equation.  
This project highlights the complete AI workflow: **data exploration → preprocessing → model training → evaluation → interpretation**.

---

## 3. Dataset Overview
- **Source:** Kaggle  
- **Dataset File:** `data_cleaned_csv2021.csv`  
- **Number of Records:** 742  

**Key Features:**  
1. `Age` → Independent variable (input)  
2. `Avg Salary(K)` → Target variable (output)  

The dataset also contains additional information such as job titles, company details, required skills, and company ratings. For this project, only the most relevant features were selected for Linear Regression analysis.

**Dataset Insights:**  
- Checked for missing values and inconsistencies.  
- Analyzed descriptive statistics to understand distributions of key variables.  
- Observed correlation between age and salary to inform model development.

---

## 4. Project Methodology
The methodology followed in this project includes:

1. **Data Exploration**  
   - Inspected dataset structure and summary statistics.  
   - Identified missing values and inconsistencies.  

2. **Feature Selection**  
   - Selected `Age` as the independent variable and `Avg Salary(K)` as the target variable.  

3. **Data Preparation**  
   - Split the dataset into **training (80%)** and **testing (20%)** sets.  

4. **Model Development**  
   - Trained a Linear Regression model on the training data.  

5. **Prediction and Evaluation**  
   - Predicted salaries for the testing dataset.  
   - Evaluated performance using **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, and **R² Score**.  

6. **Result Interpretation**  
   - Analyzed predicted vs actual salaries.  
   - Identified trends and areas for future improvement.

---

## 5. Results and Analysis
- The Linear Regression model was able to predict salaries based on age with reasonable accuracy.  
- Evaluation metrics indicated that the model captures the general trend of salary progression with experience.  
- While the model uses only a single feature, additional variables (skills, experience, company rating) could enhance predictions.  

**Key Observations:**  
- Salaries generally increase with age, reflecting experience and seniority.  
- Outliers suggest potential improvements if more features are added.

---

## 6. Conclusion
This project successfully demonstrates the use of Linear Regression to predict employee salaries.  

**Contributions of this Project:**  
1. Provides hands-on experience with the complete AI workflow.  
2. Demonstrates the applicability of Linear Regression to real-world datasets.  
3. Highlights the importance of feature selection and evaluation metrics in predictive modeling.  

**Future Work:**  
- Incorporate multiple features for multivariate regression.  
- Explore advanced machine learning models (Decision Trees, Random Forest, Gradient Boosting).  
- Apply feature engineering and handle outliers for better performance.

---

## 7. GitHub Repository
https://github.com/zainab026/AI_Assignment
