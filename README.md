# Credit-Risk-Assessment
This project aims to harness the power of machine learning algorithms to provide more accurate and efficient credit risk assessments in the financial sector.

Due to the kind of dataset that was gotten, I devised three strategies to predict the credit risk, supervised classification and regression method, and unsupervised clustering method. From the result, it can be observed that the Gradient Boost model performed the best for the regression method, K-means performed slightly better for the clustering method and for the classification method, while the ANN model seems to have performed better in terms of scores, the Gradient Boost is a better choice in terms of generalizability.

The development of this machine learning model involved these steps. 

a) Data collection: 
•	Compiled a thorough dataset with historical credit information, including information on the borrower's credit score, payment history, employment history, debt income ratio, loan amount, liquid asset and number of credit lines. 
•	This dataset was collected from (https://www.kaggle.com/datasets/ritayulfanii/credit-risk-dataset)
b) Data Cleaning and Preprocessing: 
•	Checked for missing values, duplicates, outliers, and handled where necessary. 
•	Performed exploratory data analysis by examining and analyzing the data to gain insights, identify patterns, and understand the underlying structure of the dataset. 
•	Conducted feature engineering to check for correlations amongst features and extract pertinent input features that are important for assessing credit risk (output feature). The categorical variable (credit risk feature) was encoded into numerical representations using label encoding. The input features were also scaled to improve the performance of the algorithm using standard scalar. Since the credit score feature alone is a strong determinant of credit risk (a high credit score means low credit risk and a low credit score means high credit risk), I used other input features to determine credit score in the regression model.

c) Model Selection: 
•	Compared several machine learning models, including random forest, k-nearest neighbors, decision tree, artificial neural network, logistic regression, support vector machine and gradient boosting techniques, for supervised learning method (classification and regression) and k-means and agglomerative clustering for unsupervised learning method. 
•	Compared the computational effectiveness, and performance metrics.

d) Model Development: 
•	The selected models were used to build the best predictive model using the preprocessed dataset.
•	The models were trained and optimized to find the best machine learning model. 
•	Methods like cross-validation were used to make sure the model is robust and generalizable.

