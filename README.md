# Easy-Visa-

Easy-Visa is a company that the OFLC has hired to help filter potential candidates for visa approval to work in the USA using machine learning models.

## Objective
- Due to a significant increase in the number of visa applicants, manual screening has become inefficient.
- The objective is to build machine learning models to improve the efficiency and accuracy of the screening process.

## Techniques
- XGBoost
- AdaBoost
- Gradient Boosting
- Bagging with Decision Trees
- Random Forest
- Random Search CV for hyperparameter tuning

## Results
- XGBoost showed the smallest performance gap between training and validation data.
- The choice of Metric was F1 to have a balance between Recall and Precision.
- No significant performance difference was observed between undersampled, oversampled, and original datasets due to overlapping distributions in numerical variables.
- Education level plays an important role in visa application rejection.
- Asian applicants constitute the majority, with significantly fewer applications from Africa, North America, Europe, South America, and Oceania.
