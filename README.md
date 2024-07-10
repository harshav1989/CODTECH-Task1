# CODTECH-Task1

### **Name**: Harsha Vardhini V
### **Company**: CODTECH IT SOLUTIONS
### **ID**: CT08DS1883
### **Domain**: MACHINE LEARNING
### **Duration**: JUNE to JULY 2024
### **Mentor**: SRAVANI GOUNI



## Overview of the Project

**Project**: Linear Regression on Housing Prices 

**Objective**: The objective of this project is to build a predictive model using linear regression to estimate house prices based on various features such as square footage, number of bedrooms, bathrooms, stories, parking spaces, and other relevant attributes. This model aims to help potential buyers, sellers, and real estate professionals make informed decisions.

**Key Activities**:
1. **Data Loading and Inspection**: 
   - Load the housing dataset and inspect its structure.
   - Check for data types, missing values, and basic statistics.

2. **Data Cleaning**: 
   - Handle any missing values (if present).
   - Identify and treat outliers to ensure the data quality is suitable for modeling.

3. **Exploratory Data Analysis (EDA)**:
   - Visualize the relationships between features and the target variable (house price).
   - Use plots like pairplots, boxplots, and heatmaps to identify potential correlations and distributions.

4. **Data Preparation**:
   - Convert categorical variables to numerical values using binary mapping and dummy variables.
   - Split the data into training and testing sets to evaluate the model's performance.

5. **Rescaling Features**:
   - Normalize features using Min-Max scaling to ensure all features are on a comparable scale.
   - This helps in stabilizing and improving the performance of the linear regression model.

6. **Feature Selection and Model Building**:
   - Use Recursive Feature Elimination (RFE) to select the most important features.
   - Build the linear regression model using the selected features and evaluate its performance using statistical metrics.

7. **Model Evaluation**:
   - Assess the model's performance on the training set using metrics like R-squared and adjusted R-squared.
   - Evaluate the model's performance on the test set using R-squared and visualize the predictions vs. actual values.

**Technologies Used**:
- **Programming Languages**: Python
- **Libraries**: 
  - Data Manipulation: Pandas, Numpy
  - Data Visualization: Matplotlib, Seaborn
  - Machine Learning: Scikit-learn, Statsmodels

**Key Insights**:
1. **Data Quality**: The dataset was clean with no missing values, but outliers were present in features like `price` and `area`, which were treated to improve model performance.
2. **Feature Importance**: The feature `area` was found to be highly correlated with `price`, indicating its significance in predicting house prices.
3. **Model Performance**: The linear regression model provided a reasonable fit to the data, with selected features contributing significantly to the prediction of house prices.
4. **Error Analysis**: The residuals of the model were normally distributed, indicating a good fit.
5. **Practical Application**: The model can be used by real estate professionals to estimate house prices, aiding in decision-making processes for buying and selling properties.
