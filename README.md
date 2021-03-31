# HomeCreditDefaultRisk

Dataset can be downloaded at  https://drive.google.com/drive/folders/16MhhITTm2dOxRPrU9DLMudQm2X-7lTj1?usp=sharing

Objective: To Predict how capable each applicant is of replaying a loan

Dataset: Data file contains 7 various CSV files .Later these files were merged with the unique customer ID, resulted in 188678 rows and 168 columns.

Approach: Data Preprocessing, Exploratory Data Analysis, performed re-sampling techniques on Imbalanced Dataset, Feature Selection techniques- IV (information value), Multicollinearity test using VIF, Build Logistic Regression model on selected Features, HyperParameter tunning, check over-fit or not with 5-fold cross-validation, model evaluation using Confusion Matrix.

Outcome: The model was trained on 333735 samples with 21 variables, train accuracy resulted in 61.8% and 83434 test samples model test accuracy resulted in 61.9%.
