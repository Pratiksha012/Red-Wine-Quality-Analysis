# Project Title: Red Wine Quality Analysis Using Regression and Machine Learning Techniques

## Introduction
This project is a comprehensive analysis of the Red Wine dataset obtained from Kaggle, conducted as part of the Regression Analysis subject in the 3rd year, 6th semester of my academic curriculum. The primary goal of this project is to analyze the characteristics of red wine and predict its quality using various regression and machine learning techniques.

## Dataset Description
The dataset used for this analysis is the Red Wine Quality dataset available on Kaggle. The dataset contains various chemical properties of red wine and their corresponding quality ratings. Below is a description of each column in the dataset:

### Columns Description
- **fixed acidity**: Primary fixed acids found in wine are tartaric, succinic, citric, and malic acids.
- **volatile acidity**: The gaseous acids present in wine.
- **citric acid**: A weak organic acid, found in citrus fruits naturally (e.g., lemon, orange).
- **residual sugar**: The amount of sugar left after fermentation.
- **chlorides**: The amount of salt present in wine.
- **free sulfur dioxide**: SO2 is used to prevent wine from oxidation and microbial spoilage.
- **pH**: In wine, pH is used for checking acidity.
- **density**: Density is a physical property that measures the mass per unit volume of a substance.
- **sulphates**: Added sulfites preserve freshness and protect wine from oxidation and bacteria.
- **alcohol**: The percentage of alcohol present in wine.

## Project Structure
1. **Data Import and Preprocessing**: Imported the dataset and performed necessary preprocessing steps such as handling missing values and encoding categorical variables.
2. **Exploratory Data Analysis (EDA)**: Conducted EDA to understand the distribution and relationships between different features in the dataset.
3. **Correlation Analysis**: Analyzed the correlation between each feature and the target variable (wine quality) to identify important predictors.
4. **Simple Linear Regression (SLR)**: Implemented SLR to analyze the relationship between individual features and wine quality.
5. **Multiple Linear Regression (MLR)**: Implemented MLR to analyze the combined effect of multiple features on wine quality.
6. **Machine Learning Models**: Implemented various machine learning models to predict wine quality:
   - k-Nearest Neighbors (KNN)
   - Support Vector Machine (SVM)
   - Logistic Regression
   - k-Means Clustering
7. **Hypothesis Testing**: Conducted hypothesis testing to validate the significance of the findings.

## Results
- **Correlation Analysis**: Identified the most significant features affecting wine quality.
- **Regression Models**: Analyzed the performance of SLR and MLR models in predicting wine quality.
- **Machine Learning Models**: Evaluated the performance of KNN, SVM, and Logistic Regression models. Clustered the wines into different quality groups using k-Means Clustering.
- **Hypothesis Testing**: Verified the statistical significance of the results obtained from the regression and machine learning models.

## Conclusion
This project provides a comprehensive analysis of the factors affecting the quality of red wine. The regression and machine learning models implemented in this study offer valuable insights into predicting wine quality based on its chemical properties.

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

