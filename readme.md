# Overview

In this assignment, I will do Data Prepocessing (Data Cleansing).

The steps that will be taken are:
- Looking for a valid customer ID (telphone number)
- Overcoming empty data (Missing Values)
- Addressing the Outliers of each Variable
- Standardize the Value of the Variable

# Library
1. Pandas   
    Pandas (Python for Data Analysis) is a Python library that focuses on data analysis processes such as data manipulation, data preparation, and data cleaning.   
    - read_csv() used to read csv files
    - str.match() used to match certain characters
    - drop() used to delete
    - count() used to calculate each variable
    - drop_duplicates() used to delete duplicate rows
    - fillna() used to fill in with a specific value
    - quantile() used to view the quantile to a particular
    - mask() used to replace a specific value if the condition satisfies it
    - astype() used to change data type
    - value_counts() used to count the uniqueness of a column
    - sort_values() used for sort values
    - isnull() used to detect missing values
    - dropna() used to remove missing values
    - replace() used to replace values
2. Matplotlib   
    Matplotlib is a Python library that focuses on visualizing data such as plotting graphs. Matplotlib can be used in Python scripts, Python and IPython shells, web application servers, and several other graphical user interface (GUI) toolkits.   
    - figure() used to create new figure figures
3. Seaborn   
    Seaborn builds on Matplotlib and introduces additional plot types. It also makes your traditional Matplotlib plot look a little prettier.  
    - box_plot() used to make a box plot

# Dataset
For the dataset used has been provided in csv format, it can be loaded via this [link](https://dqlab-dataset.s3-ap-southeast-1.amazonaws.com/dqlab_telco.csv)   

The detailed data are as follows:
* UpdatedAt: Periode of Data taken
* customerID: Customer ID
* gender: Whether the customer is a male or a female (Male, Female)
* SeniorCitizen: Whether the customer is a senior citizen or not (1, 0)
* Partner: Whether the customer has a partner or not (Yes, No)
* Dependents: Whether the customer has dependents or not (Yes, No)
* tenure: Number of months the customer has stayed with the company
* PhoneService: Whether the customer has a phone service or not (Yes, No)
* MultipleLines: Whether the customer has multiple lines or not (Yes, No, No phone service)
* InternetService: Customer’s internet service provider (DSL, Fiber optic, No)
* OnlineSecurity: Whether the customer has online security or not (Yes, No, No internet service)
* OnlineBackup: Whether the customer has online backup or not (Yes, No, No internet service)
* DeviceProtection: Whether the customer has device protection or not (Yes, No, No internet service)
* TechSupport: Whether the customer has tech support or not (Yes, No, No internet service)
* StreamingTV: Whether the customer has streaming TV or not (Yes, No, No internet service)
* StreamingMovies: Whether the customer has streaming movies or not (Yes, No, No internet service)
* Contract: The contract term of the customer (Month-to-month, One year, Two year)
* PaperlessBilling: Whether the customer has paperless billing or not (Yes, No)
* PaymentMethod: The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
* MonthlyCharges: The amount charged to the customer monthly
* TotalCharges: The total amount charged to the customer
* Churn Whether: the customer churned or not (Yes or No)


