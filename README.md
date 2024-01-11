# House Price Regression Project

## Kaggle Competition - Rank 293 out of 20,000+ Entries

This project focuses on predicting house prices using regression techniques. The dataset contains 79 features, including MSSubClass, MSZoning, LotFrontage, LotArea, Street, Alley, and many more.

### What I Learned from this Project:

1. Identified skewness, missing data, and unbalanced data during Exploratory Data Analysis (EDA).
   
2. Advanced Missing Value Imputation:
   - Implemented techniques like K-Nearest Neighbors (KNN) for filling missing values.

3. Discovered new ways of combining features and doing feature engineering the right way to enhance model accuracy.

4. Transformation Techniques:
   - Applied log transformations for skewed features.
   - Used trigonometric transformations for cyclic features.

5. Model Selection and Ensemble:
   - Utilized PyCaret to find the best models for the data.
   - Created a weighted ensemble of these models for enhanced accuracy.

### Dataset Overview:

- **Number of Features:** 79
- **Example Features:**
  - MSSubClass, MSZoning, LotFrontage, LotArea, Street, Alley, LotShape, LandContour, Utilities, LotConfig, LandSlope, Neighborhood, Condition1, Condition2, BldgType, HouseStyle, OverallQual, OverallCond, YearBuilt, YearRemodAdd, RoofStyle, RoofMatl, Exterior1st, Exterior2nd, etc.
  
- **Target Variable:**
  - SalePrice

### Data Preprocessing:

- **Handling Missing Values:**
  - LotFrontage: 259 missing values, Alley: 1369 missing values, etc.
