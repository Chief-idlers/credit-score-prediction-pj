# credit-score-prediction-pj
credit score prediction projectThis project focuses on predicting credit scores based on customer financial data. The dataset contains various features related to customers' financial behaviors, such as income, loans, credit history, and payment behaviors. The goal is to build a machine learning model that can accurately classify customers into different credit score categories (Good, Standard, Poor).       									                                                                                                          # Dataset Overview  
/content/drive/MyDrive/datasets/.  
 Key Features:  
- **Customer Information:** ID, Customer_ID, Name, Age, SSN, Occupation  
- **Financial Details:** Annual Income, Monthly In-Hand Salary, Number of Bank Accounts, Number of Credit Cards  
- **Loan/Credit Information:** Interest Rate, Number of Loans, Type of Loan, Outstanding Debt  
- **Credit History:** Credit Mix, Credit Utilization Ratio, Age of Credit History  
- **Payment Behavior:** Payment of Minimum Amount, Payment Behavior, Monthly Balance  
- **Target Variable:** Credit Score (Good, Standard, Poor)  
```
Data Cleaning Process  
The notebook encompasses a comprehensive data cleaning and processioning methodology:  
Initial Exploration:  
Assesses data dimensions (150,000 rows × 28 columns)  
Analyzes data types (a combination of numeric and categorical types)  
Discovers missing values across various columns  
Text Cleaning:  
Eliminates extraneous characters (underscores, spaces, commas, quotes)  
Substitutes invalid entries (empty strings, 'nan', '!@9#%8', '#F%$D@*&8') with NaN  
Data Type Conversion:  
Transforms suitable columns into numeric types (int/float)  
Addresses problematic numeric columns with special characters  
Visualization:  
Generates histograms for all numeric columns to elucidate distributions  
Key Observations  
The dataset comprises both numerical and categorical attributes pertaining to customer credit behavior.  
Numerous columns exhibit missing values necessitating resolution prior to modeling.  
Certain columns contain inconsistent data (e.g., Age with negative values -500).  
The target variable, Credit_Score, encompasses three classifications: Good, Standard, Poor.  
The data appears to exhibit time-series characteristics (organized by Month for each Customer_ID)  
The cleaned dataset will be primed for:  
Further feature engineering  
Addressing missing values  
Encoding categorical variables  
Segregating into train/test sets  
Constructing and assessing credit score prediction model                                                                                                                                    reach out at kelvinsang89@gmail.com i will appreciate your thoughts on the project
