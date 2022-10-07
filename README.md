**Background**
---
A lending company has a problem where it requires efficiency and speed in receiving loans from each customer.As a Data Science Intern from ID/X Partners, we will to process data and create models that are able to predict and assess optimal credit applications and predict existing risks. To facilitate the assessment, we will create a credit score based on the logistic regression model. Finally, we will provide solutions for lending companies how the insights we get.

**Data Pre-processing**
---
1. Handling Missing Value
2. Feature Encoding
3. Feature Engineering Using Weight of Evidence and Information Value
4. Feature Selection
5. Imbalance Data Handling

**Modelling**
---
1. Evaluation target is AUC Score 
2. Logistic Regression Model are tested and compared between without tuning & with hyperparameter tuning result to get best AUC Score value
3. Logistic Regression with hyperparameter tuning get better result where the AUC Score value obtained is 93.53%
4. Generated best model using Logistic Regressiong with score 0.75 on Kolmogorov–Smirnov (KS - Statistic).
![Kolmogrov-Smirnov](https://user-images.githubusercontent.com/68262798/194569140-e2ea4c7b-dff1-4e4c-ac64-38759763faf3.png)
![ROC CURVE](https://user-images.githubusercontent.com/68262798/194569176-9201cadb-d374-406e-8664-53173209497a.png)

**Credit Score**
---
1. Obtain scorecard each feature based on coefficient of Logistic Regression
2. Define min and max credit score based on fico score (300-850)
4. Show top 10 importance feature that can boost credit score customer and can reduce credit score customer
![10 HIGH FEATURE](https://user-images.githubusercontent.com/68262798/194567844-1e106237-dfc7-4af6-99f6-58ffe4556cfd.png)
![10 LOW FEATURE](https://user-images.githubusercontent.com/68262798/194567867-c7d69508-2160-4767-be7c-ba60672facfc.png)

5. Predict how much credit score each customer get based on scorecard 
For More Detail Credit Score Result [Here](https://docs.google.com/spreadsheets/d/1n1XGrjIUdIzlcMO4ZVTzmXzuvRpE2bgN1qCO-qTNUx4/edit?usp=sharing)


**Business Insight**
---
![Bad loan on last payment](https://user-images.githubusercontent.com/68262798/194567641-17c0114c-c8a2-4a64-b153-f74290a7dc4e.png)
![bad loan last payment](https://user-images.githubusercontent.com/68262798/194567667-e08d9c60-6bce-4acf-b190-319e98238bb7.png)
![tren![Trend bad loan interest rate](https://user-images.githubusercontent.com/68262798/194567760-36910a46-6e04-4cff-af15-d88deae6a741.png)
d bad loan emp length](https://user-images.githubusercontent.com/68262798/194567741-80abb80f-300c-4523-bd4f-c95a0f03bb6c.png)
![trend bad loan payment time](https://user-images.githubusercontent.com/68262798/194567775-62ff8592-4c20-42df-a548-baf6b5fb8f70.png)

**Summary**
---
1.Loan Amount; The amount of the loan given is related to the interest rate that must be paid. The larger the loan amount, the higher the interest rate that must be paid.Loan amount more than 28100 not recommended to offer for customer.
2. Last Payment Amount; More payment amount that customer take, lower the risk of the customer becoming a bad loan. Lending Companies can set a minimum amount that must be paid starting from 1500 for the amount of payment each time it is due.
3. Payment Time; The longer time that must be paid by the customer, the higher the risk of the customer becoming a bad loan. Limiting the payment time max 6 years can reduce the risk of bad loans
4. Interest Rate; More interest rate that customer take, increasing more bad loan rate. Ideally if lending companies want to keep bad loan low, they can offer interest rate below 14%. Lending companies must avoid to offer loan with interest rate more than 20%.
5. Employment Length; It has been proven that the longer the customer's work experience, the more capable the customer is to repay the loan thereby increasing the good loan.
