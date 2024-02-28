# Loan_Risk_Predictor_With_PySpark
Predicting if a customer will default on their loan based on customer data

#### Goal:
To produce an end-to-end pipeline for predicting a loan default using PySpark

#### Progress:
- Preliminary EDA
- Data visualisation
- Data preprocessing
- Initial models created with small hyperparameter variation inc. cross-validation
- Predictions made and evaluated
- Started investigation into feature reduction

#### Future Work:
- Complete investigation into feature reduction
- Final model selection
- Hyperparameter fine-tuning

#### The following information was used in analysis:

1. Applicant_ID: Unique identifier for each loan applicant.
2. Annual_Income: Annual income of the loan applicant.
3. Applicant_Age: Age of the loan applicant.
4. Work_Experience: Number of years of work experience of the loan applicant.
5. Marital_Status: Marital status of the loan applicant.
6. House_Ownership: Ownership status of the applicant's residence.
7. Vehicle_Ownership(car): Ownership status of the applicant's vehicle.
8. Occupation: Profession or occupation of the loan applicant.
9. Residence_City: City where the loan applicant resides.
10. Residence_State: State where the loan applicant resides.
11. Years_in_Current_Employment: Number of years the applicant has been in their current job.
12. Years_in_Current_Residence: Number of years the applicant has been residing in their current residence.
13. Loan_Default_Risk: Indicator of loan default risk, with values indicating whether the loan applicant is at risk of defaulting on the loan.

The data was obtained from Kaggle datasets: https://www.kaggle.com/datasets/yaminh/applicant-details-for-loan-approve/data
