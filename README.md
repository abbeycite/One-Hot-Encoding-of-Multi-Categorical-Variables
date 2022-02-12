# One-Hot-Encoding-of-Multi-Categorical-Variables
I performed feature engineering for Variables with multiple categories/labels through One hot encoding...
I will be performing feature engineering(one-hot encoding) on the Mercedesbenz dataset from kaggle(https://www.kaggle.com/aditya1702/mercedes-benz-data-exploration/data). This is a special case because there are multiple categories/labels in each variable, which requires some methodologies that will enable us check overfitting.

The idea is to fetch 10 most frequent categories in each variables, encode them as one(1) binary variable while other categories are group into the 0 binary variable. In summary, This is equivalent to grouping all the other labels/categroies under a new category, that in this will be dropped. Thus, the 10 new dummy variables indicate if one of the 10 most frequent labels is present(1) or not(0) for a particular observation.

Please the code file for codes and comments for explanations...
