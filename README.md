# Heart-Disease
## About
This is our mini-project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on Predicting Heart Disease. [(Dataset)](heart.csv). 
Please view our [code](Project_0404.ipynb) in order from:
1. Data Extraction
2. Data Visualization
3. Data Resampling and Splitting
4. Decision Tree Classification (without resampling)
5. Decision Tree Classification (with resampling)
6. Logistic Regression

## Contributors
* @matthewtan01
* @eezzatt
* @shaojunL

## Problem Definition
* Which easily measured factor is most useful when predicting the possibility of Heart Disease for people above 50 years of age?
* Which model is best to predict the possibility of Heart Disease?

## Models Used
* Decision Tree Classification
* Logistic Regression

## Conclusion
*  Resampling imbalanced data did not improve decision tree model by a significant difference
*  When it comes to predicting the likelihood of someone having Heart Disease, the factors that carry the most weight in descending order are MaxHR, Cholesterol, and RestingBP

Reasons:
*  From our boxplot, MaxHR against the levels of HeartDisease had the most significant difference
*  MaxHR appeared highest up in the Decision Tree
*  MaxHR had the highest accuracy as well as magnitude for its coefficient for Logistic Regression

## What did we learn from this project?
* Handling imbalanced datasets with resampling
* Logistic Regression
* Plotting Histogram with respect to Categorial Values
* Collaborating through Github


## References
* https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction 
* https://realpython.com/logistic-regression-python/
