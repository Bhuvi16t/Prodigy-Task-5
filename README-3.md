Task-03: Decision Tree Classifier for Predicting Customer Purchases
Overview
This project involves building a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. For this task, we use the Bank Marketing dataset from the UCI Machine Learning Repository.

Dataset
The Bank Marketing dataset contains information on customer demographics and their interaction with a bank's marketing campaigns. The goal is to predict whether a customer will subscribe to a term deposit based on their data.

Attributes
The dataset includes the following features:

Age: Age of the customer.
Job: Type of job (categorical).
Marital: Marital status (categorical).
Education: Education level (categorical).
Default: Has credit in default? (binary: "yes", "no").
Balance: Average yearly balance in euros.
Housing: Has housing loan? (binary: "yes", "no").
Loan: Has personal loan? (binary: "yes", "no").
Contact: Contact communication type (categorical).
Day: Last contact day of the month.
Month: Last contact month of the year.
Duration: Last contact duration, in seconds.
Campaign: Number of contacts performed during this campaign.
Pdays: Number of days since the client was last contacted from a previous campaign.
Previous: Number of contacts performed before this campaign.
Poutcome: Outcome of the previous marketing campaign (categorical).
Y: Target variable - has the client subscribed to a term deposit? (binary: "yes", "no").
Requirements
To complete this task, you will need:

Python 3.x
Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn (for data visualization)
Steps to Complete the Task
Data Preprocessing

Load the dataset.
Handle missing values.
Encode categorical variables.
Split the data into training and testing sets.
Model Building

Initialize the decision tree classifier.
Train the model on the training data.
Make predictions on the testing data.
Model Evaluation

Evaluate the model using appropriate metrics such as accuracy, precision, recall, and F1-score.
Visualize the decision tree.
Results Interpretation

Analyze the results and discuss the performance of the model.
