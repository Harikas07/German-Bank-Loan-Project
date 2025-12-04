German Bank Loan Prediction Project
Overview:
This project focuses on predicting loan defaults for a German bank using various machine learning models. The goal is to identify the most accurate model for predicting whether a customer will default on their loan based on historical data.

Dataset:
The dataset used in this project is German_bank.csv. It includes 1000 rows and 17 columns, with each row representing a customer. The columns contain various features such as:

1.checking_balance: Amount of money available in the account of customers
2.months_loan_duration: Duration since the loan was taken
3.credit_history: Credit history of each customer
4.purpose: Purpose of the loan
5.amount: Amount of the loan taken
6.savings_balance: Balance in account
7.employment_duration: Duration of employment
8.percent_of_income: Percentage of monthly income
9.years_at_residence: Duration of current residence
10.age: Age of the customer
11.other_credit: Any other credits taken
12.housing: Type of housing (rent or own)
13.existing_loans_count: Existing count of loans
14.job: Job type
15.dependents: Any dependents on the customer
16.phone: Phone ownership status
17.default: Default status (target column)

Project Structure:
1.Data Preprocessing:
	The dataset was cleaned and categorical variables were encoded into numeric values using LabelEncoder.
	Missing values were checked, and none were found.

2.Exploratory Data Analysis (EDA):
	Histograms and heatmaps were used to visualize data distributions and correlations.

3.Machine Learning Models:
Five different machine learning models were implemented to predict loan defaults:
	1.Logistic Regression
	2.Support Vector Machine (SVM)
	3.Random Forest
	4.Gradient Boosting
	5.Naive Bayes
Each model was trained on 70% of the dataset and tested on the remaining 30%.

Results:
1.Logistic Regression:
Accuracy: Moderate performance with balanced precision and recall.

2.SVM:
High accuracy but struggled with class imbalance.

3.Random Forest:
High accuracy and balanced performance, particularly good at identifying defaults.

4.Gradient Boosting:
The best-performing model with the highest accuracy and balanced metrics.

5.Naive Bayes:
Useful but less effective compared to ensemble methods.

Conclusion:
This project demonstrates that machine learning models, particularly Random Forest and Gradient Boosting, are effective tools for predicting loan defaults. These models provide high accuracy and are well-suited for managing loan risks. Continuous model updates with new data can further improve prediction accuracy.

How to Run the Project:
1.Install required libraries:
	pip install pandas numpy scikit-learn seaborn matplotlib

2.Run the analysis:
	Execute the Jupyter Notebook or Python script to perform the analysis.
