# credit-score-prediction-pj
Credit Score Prediction Project  
This project aims to predict credit scores based on customer financial data. The dataset includes various features related to customers' financial behaviors, such as, loans, credit history, and payment patterns. The objective is to develop a machine learning model capable of accurately classifying customers different credit score categories (Good Standard, Poor).  

Dataset Overview  
/contentdrive/MyDrive/datasets  
Key Features:  
- **Customer:** ID, Customer_ID, Name, Age,N, Occupation  
- **Financial Details:** Annual, Monthly In-Hand Salary, Number of Bank Accounts, Number of Credit Cards  
-Loan/Credit Information:** Interest Rate, Number of Loans Type of Loan, Outstanding Debt  
 **Credit History:** Credit Mix, Credit Utilization Ratio, Age of Credit  
- **Payment Behavior:** Payment of Amount, Payment Behavior, Monthly Balance  
- **Target Variable:** Credit Score (Good, Standard, Poor)  

Data Cleaning Process  
The notebook outlines a comprehensive data cleaning and processing methodology:  
- **Initial Exploration:**  
  - Anzes data dimensions (150,000 rows × 28 columns)  
  Evaluates data types (a combination of numeric categorical types)  
 - Identifies missing values across various columns  
 **Text Cleaning:**  
  - Removes extraneous characters (underscores, spaces, commas, quotes)  
  Replaces invalid entries (empty, 'nan', '!@9#%8', '#F%$D@*&8') with NaN  
- **Data Conversion:**  - Converts suitable columns into numeric (int/float  
  - Resolves issues in numeric columns with special characters  
- **Visualization:**  
  - histograms for all numeric columns to illustrate distributionsKey Observations  
The dataset comprises both numerical and categorical attributes related to customers.                                                                                                       reach out at kelvinsang89@gmail.com i will appreciate your thoughts on the project
