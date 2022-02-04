# telco-customer-churn
------------

#### Dataset Information  
The dataset is named Telco Customer Churn which focused on customer retention  [IBM Sample Data Sets] https://www.kaggle.com/blastchar/telco-customer-churn. The dataset contains 7043 entries representing 7043 unique customers. There are 21 columns, with 18 categorical variables. 'Churn' is the target feature.  
  
#### Project Overview  
Firstly, data quality reports and visualizations have been made and data examined in detail. Empty values in the 'TotalCharges' column has been handled. Then, encoding the categorical features was made one hot encoder. After the encoding process, the number of columns increased to 41. And, unity-based normalization has been used for 3 numerical features. Finally, Logistic Regression, K-Nearest Neighbour, SGD, Decision Tree, Random Forest, SVC, Ada Boost Classifiers have been used to preprocessed data and evaluation of the models have been made.  
  
#### File Information
'data' folder contains the dataset file. And, 'telco_analysis.ipynb' file contains all the analysis and evaluation code.

