# Medical Insurance Charges Analysis

## Project Overview
This project explores **insurance costs** based on various factors such as age, sex, BMI, and number of children. The goal is to build a predictive model for estimating insurance premiums, leveraging data analysis and machine learning techniques.

## Skills Highlighted

- **Data Collection and Cleaning**: Using **Pandas** to load and clean the dataset, including handling missing values and converting categorical data into numerical formats using **Label Encoding** and **One-Hot Encoding**.
- **Exploratory Data Analysis (EDA)**: Utilizing **Matplotlib** and **Seaborn** for data visualization to explore relationships between variables, trends, and distributions.
- **Statistical Analysis**: Applying correlation analysis and basic statistical methods to understand data characteristics.
- **Feature Engineering**: Creating new variables and transforming existing ones, such as scaling numerical data using **MinMaxScaler** or **StandardScaler**.
- **Modeling**: Building predictive models using **Scikit-Learn**, such as **Linear Regression**, **Decision Trees**, and **Random Forest**.
- **Model Evaluation**: Evaluating models using **cross-validation**, and measuring performance with metrics like **RMSE**, **MAE**, and **R-squared**.
- **Communication and Reporting**: Presenting findings through well-organized reports and visualizations.

## Project Steps

### 1. Data Collection
- The dataset used for this project is sourced from a publicly available CSV file containing information such as:
  - **Age**
  - **Sex**
  - **BMI**
  - **Number of Children**
  - **Smoking Status**
  - **Region**
  - **Insurance Charges** (target variable)

### 2. Data Preprocessing
- **Handling Missing Data**: Ensuring the dataset is clean by filling or dropping missing values.
- **Encoding Categorical Data**: Converting categorical columns like **sex** and **region** using **Label Encoding** or **One-Hot Encoding**.

### 3. Exploratory Data Analysis (EDA)
- Visualizing distributions using **histograms** and **box plots**.
- Analyzing correlations using a **heatmap**.
- Investigating trends and patterns in the data, particularly how **age**, **BMI**, and **smoking status** influence **insurance charges**.

### 4. Feature Engineering
- Scaling numerical features such as **BMI** and **age** to improve model performance.
- Creating interaction terms or polynomial features to capture more complex relationships in the data.

### 5. Model Building
- Splitting the data into training and testing sets using **train_test_split** from **Scikit-Learn**.
- Training various models:
  - **Linear Regression**: For baseline performance.
  - **Decision Trees**: To capture non-linear relationships.
  - **Random Forest**: To improve predictive power with ensemble learning.

### 6. Model Evaluation
- Comparing model performance using **cross-validation**.
- Evaluating models with metrics such as **RMSE**, **MAE**, and **R-squared**.
- Selecting the best-performing model for predicting insurance costs.

### 7. Reporting Results
- Presenting key findings through data visualizations and summary statistics.
- Writing a detailed report outlining the steps, analysis, and model outcomes.
