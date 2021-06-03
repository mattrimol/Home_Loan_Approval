### Predicting Loan Home Loan Approval

##### Question/Need

I have been hired by the Consumer Financial Protection Bureau (CFPB) to determine what factors best predict whether a someone will be approved for a home loan. The CFPB will use my findings for two main purposes:

1. To uncover any unfair bias in the approval process.
2. To provide consumers with information on how they can better set themselves up to be approved for a loan. For instance, this may involve suggesting the best agency to use or what income level may be required before applying in a certain location.

##### Data

Each year thousands of financial institutions report data about mortgages to the public, under the Home Mortgage Disclosure Act (HMDA).  The CFPB makes this data available for download. I will be using HMDA data from California for the year 2017, available though a CSV file. There are approximately 40 features, which fit into three broad categories: 

- Loan information (agency, amount, type, etc.)
- Applicant and co applicant demographic information
- Geographic information on demographics, income, and population

A **single row of data represents a single loan application** and the **target variable will be action taken** which indicates whether an application was approved, denied, or withdrawn/closed.

##### Main Tools

- Data Handling - Pandas & Numpy
- Modeling - Scikit Learn
- Visuals - Matplotlib & Seaborn

##### MVP

A basic classification model predicting home loan approval. From the MVP, I will improve the model through feature engineering, feature selection, and different types of classification models.