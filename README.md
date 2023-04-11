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
*  The classification accuracy of the decision tree with imbalanced data and balanced data is around the same
*  From our boxplots of the 3 variables against the levels of HeartDisease, MaxHR had the most significance difference
*  MaxHR appeared highest up in the Decision Tree
*  MaxHR had the highest accuracy as well as magnitude for its coefficient for Logistic Regression

## What did we learn from this project?
* Handling imbalanced datasets with resampling
* Logistic Regression
* Plotting the levels of a Categorical variable on a histogram
* Collaborating through Github


## References
* https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction 
* https://www.kaggle.com/code/rafjaa/resampling-strategies-for-imbalanced-datasets/notebook
* https://realpython.com/logistic-regression-python/
