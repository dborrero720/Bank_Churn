# Bank Customer Churn: EDA and Classification 

The main goal of this analysis was to determine the optimal model for predicting bank churn based on accuracy, sensitivity, and specificity.  Three classification models were build and evaluated:

1. Decision Tree
2. Logistic Regression
3. Random Forest

with “Churn” as our target variable.

After the initial steps of identifying the problem and preparing the data, EDA was performed.  For each variable we calculated the rate of churn, so we could see how the rate differed within each variable.  Lastly, a correlation heat map was created to see which variables were most correlated with churn.  The variable “Age” had the strongest correlation with “Churn”

<img width="400" alt="Screen Shot 2021-02-04 at 12 53 20 PM" src="https://user-images.githubusercontent.com/56644186/106963757-10dcac80-670f-11eb-85ab-1057e6eb4ec7.png">

Comparing the models, the Random Forest outperformed the other models in every measure, so this was chosen as our optimal model.

<img width="200" alt="Screen Shot 2021-02-04 at 12 53 39 PM" src="https://user-images.githubusercontent.com/56644186/106963582-c824f380-670e-11eb-8653-eb7a35792ffa.png">

The last step was to view the feature importance of the Random Forest model to see which features were most important in predicting churn, and we saw that “Age” was most important.

<img width="400" alt="Screen Shot 2021-02-04 at 12 53 53 PM" src="https://user-images.githubusercontent.com/56644186/106963602-d115c500-670e-11eb-8ac4-be2b54f93593.png">
