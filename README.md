**About the dataset:** 

- __Description:__ This dataset contains credit card transactions made by European cardholders in the year 2023, downloaded from kaggle dataset. It comprises over 550,000 records, and the data has been anonymized to protect the cardholders' identities. 
- __Description:__ This dataset contains credit card transactions made by European cardholders in the year 2023, downloaded from kaggle dataset. It comprises over 550,000 records, and the data has been anonymized to protect the cardholders' identities.
Links: https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023?resource=download

- __Key features:__

  - id: Unique identifier for each transaction
  - V1-V28: Anonymized features representing various transaction attributes (e.g., time, location, etc.)
  - Amount: The transaction amount
  - Class: Binary label indicating whether the transaction is fraudulent (1) or not (0)
    
**Reason for choosing Logistic Regression:**

Logistic regression was chosen as the training model for the following reasons:

- **Binary classification:** The problem at hand involves binary classification, where the goal is to predict whether a transaction is fraudulent or not based on given features. Logistic regression is well-suited for binary classification tasks.

- **Interpretability:** Logistic regression provides interpretable coefficients, allowing us to understand the impact of each feature on the probability of a transaction being fraudulent. 

- **Low Variance:** Logistic regression tends to have low variance and is less prone to overfitting, especially when the number of features is relatively high compared to the number of observations. 

- **Basic concept:** Logistic regression serves as a baseline model against which more complex algorithms can be compared. 
