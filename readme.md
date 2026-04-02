**Project Overview**
- The objective of this project is to build a machine learning model that can accurately predict rental prices based on input features

**Features Used**
- House Type
- Locality
- City
- Area
- Number of Bedrooms
- Number of Bathrooms
- Number of Balconies
- Furnishing Status
- Area Rate

**Exploratory Data Analysis(EDA)**
- Histogram
- Boxplot
- Scatterplot
- Heatmap

**Data Preprocessing**
 * One-Hot Encoding:
 - Furnishing
 - Property type
 - City
 * Target Encoding:
 - Locality
 * Outlier Handling:
 - Outliers were present but considered valid
 - Log transformation was applied to normalie the data

**Models Used**
 - Linear Regression
 - Lasso Regression
 - Ridge Regression

**Model Performance**
**Linear Regression**
 - Train MSE:0.05
 - Train R2:0.94
 - Test MSE:0.06
 - Test R2:0.93

**Lasso Regression**
 - Train MSE:0.105
 - Train R2:0.89
 - Test MSE:0.120
 - Test R2:0.87

**Ridge Regression**
 - Train MSE:0.05
 - Train R2:0.94
 - Test MSE:0.06
 - Test R2:0.93

**Results**
 - Linear Regression and Ridge Regression performed best with high R2 scores
 - Lasso Regression showed slightly lower performance due to feature regulariation
 - Log transformation helped improve model stability and performance

 

