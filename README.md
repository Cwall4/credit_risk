# Credit Risk

For Module 17's challenge, I analyzed credit risk for "LendingClub". The model used was logistic regression, and four were fitted. Each used different methods of sampling:
* Oversampling the data using the RandomOverSampler and SMOTE algorithms.
* Undersampling the data using the cluster centroids algorithm.
* Use a combination approach with the SMOTEENN algorithm.

"credit_risk_resampling(Challenge_v2).ipynb" offers the more complete analysis, and (with some qualifiers) recommends the SMOTEENN algorithm.

The data provided was transformed, and is included in this repository as "challenge_data_encoded.csv.zip".
