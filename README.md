# Exploratory Data Analysis Telco Customer Churn
Find insight from the data.
You can see the full comment in my post on medium https://medium.com/@yodialfariz/exploratory-data-analysis-telco-customer-churn-1dd47a41e33

## Data Dictionary
- customerID: Customer ID
- gender: Whether the customer is a male or a female
- SeniorCitizen: Whether the customer is a senior citizen or not (1, 0)
- Partner: Whether the customer has a partner or not (Yes, No)
- Dependents: Whether the customer has dependents or not (Yes, No)
- Tenure: Number of months the customer has stayed with the company
- PhoneService: Whether the customer has a phone service or not (Yes, No)
- MultipleLines: Whether the customer has multiple lines or not (Yes, No, No phone service)
- InternetService: Customer’s internet service provider (DSL, Fiber optic, No)
- OnlineSecurity: Whether the customer has online security or not (Yes, No, No internet service)
- OnlineBackup: Whether the customer has an online backup or not (Yes, No, No internet service)
- DeviceProtection: Whether the customer has the device protection or not (Yes, No, No internet service)
- TechSupport: Whether the customer has the tech support or not (Yes, No, No internet service)
- StreamingTV: Whether the customer has TV streaming or not (Yes, No, No internet service)
- StreamingMovies: Whether the customer has movie streaming or not (Yes, No, No internet service)
- Contract: The customer’s contract
- PaperlessBilling: Whether the customer has paperless billing or not (Yes, No)
- PaymentMethod: The payment method opted by the customers
- MothlyCharges: The monthly charges paid by the customers
- TotalCharges: The total charges paid by the customers
- Churn: The customer churn status (1 - Yes, 0 - No)



## Step by step
### Data Understanding
### Data Cleansing
- Check Missing Value
- Duplicated value
### Univariate Analysis 
- Detect Outlier with Boxplot
- Knowing Distribution Form With KDE using histplot and distplot
- countplot categorical column
- Multivariate Analysis)
### EDA Question
- Who are the top 10 Customers who spend more money for Telco Company ?
- Who are the top 10 Churn Customers who spend more money for Telco Company ?
- Who are the top 10 Customers not churn who spend more money for Telco Company ?
- How many customers who curn and not churn
- how much money is made from internet services? show turnover by category
- How much average tenure and amount month who used our service, show by Churn, MultipleLines, PhoneService, and InternetService
- Show statistical summary from our service by TotalCharges !
- How many customers who used our service ? show per each category
- Show service on InternetService who used any features on services and still subscribe.
- How many customers who used InternetService per each category and still subscribe ?
- How many customers who used PhoneService per each category and still subscribe?
- How many customers who pay per each PaymentMethod ?
