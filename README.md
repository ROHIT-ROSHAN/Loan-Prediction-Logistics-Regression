Such a model is created so that the loan providers can directly visit those customers who have 
high chances of taking a loan thereby reducing time and increase success ratio with minimal 
expenditure. This model is created by developing a classification model , “Logistics 
classifier”.
INPUTS:
The model will take various input parameters such as:

✓ Age: Customer’s age in completed years

✓ Experience: years of professional

✓ Income: Annual income of the customer ($000)

✓ Family: Family size of the customer

✓ CCAvg: Avg. spending on credit cards per month 

✓ Education: Education Level. 1: Undergrad; 2: Graduate; 3: Advanced/Professional

✓ Mortgage: Value of house mortgage if any.

✓ Securities Account: Does the customer have a securities account with the bank?

✓ CD Account: Does the customer have a certificate of deposit (CD) account with the bank?

✓ Online: Does the customer use internet banking facilities?

✓ Credit card: Does the customer use a credit card

EXPECTED OUTCOME: The model will take these input parameters from a dataset perform 
operations on it and will give values either 0 (“The customer won’t take a loan”) or 1(“Customer 
will take loan”)

PYTHON TOOLS USED:

✓ Pandas library to read from the dataset (csv) 

✓ train_test_split from sklearn.model_selection: To split data into training and testing 
samples

✓ Logistic Classifier from skleanr.linear_model: To train a model

✓ Pickle library: To save a model
