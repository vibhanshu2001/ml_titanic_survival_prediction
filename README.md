# Titanic Survival Prediction Model
This project uses a logistic regression model to predict the survival rate of passengers on the Titanic with an accuracy score of approximately 80%. The model is built using data from the famous Titanic dataset, which includes information on passenger demographics and whether or not they survived the sinking of the ship.

The following libraries are used in this project:

- numpy: a library for numerical computing in Python
- pandas: a library for data manipulation and analysis
- matplotlib: a plotting library for creating visualizations in Python
- seaborn: a data visualization library based on matplotlib
- scikit-learn: a machine learning library for Python
<br>The project begins by importing the necessary libraries and loading the Titanic dataset into a pandas DataFrame. The data is then cleaned and preprocessed, with missing values imputed and categorical variables encoded using techniques such as one-hot encoding or label encoding.

<br>After preprocessing the data, it is split into training and testing sets using scikit-learn's train_test_split function. A logistic regression model is then fit on the training set and evaluated on the testing set using accuracy as the evaluation metric. The accuracy score achieved by the model is approximately 80%.

<br>Finally, the model can be used to make predictions on new data or deployed in a production environment to automatically classify the survival rate of new passengers based on their demographic information.
<br>
Overall, this project demonstrates the use of logistic regression and various data preprocessing techniques in predicting survival rates on the Titanic with an accuracy score of approximately 80%.
