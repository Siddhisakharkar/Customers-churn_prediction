# Customers-churn_prediction
The Customer Churn Prediction project uses Logistic Regression to predict customer churn based on demographics and account details. It helps businesses identify at-risk customers and improve retention.
# Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Jupyter Notebook 
# Steps Involved in the Project:
Data Preprocessing:

    Handle missing values in key columns.
    Convert categorical variables like Geography and Gender into numeric representations.
    Normalize numerical features to improve model performance.
    Drop irrelevant columns (such as RowNumber, CustomerId, and Surname) that do not contribute to the predictive model.

Model Training and Testing:

    Split the data into training and testing sets.
    Train a Logistic Regression model using the preprocessed data.
    Evaluate the model's performance using metrics like accuracy, precision, recall, F1-score, and confusion matrix.

Data Visualization:

    Visualize the distribution of churned vs. non-churned customers.
    Analyze the relationship between features such as Age, Balance, Tenure, and Exited.
    Display a correlation heatmap to visualize the relationships between numeric variables.

Model Evaluation:

    Assess the model's ability to classify customers into churn or non-churn categories.
    Visualize confusion matrices and classification reports for better interpretation of model results.

