This project aims to explore the bank marketing data.
Particularly, it is to build a classification model to predict if the client will subscribe the term deposit.

Data: Bank Marketing
The data is related to the direct marketing campaigns of a Portuguese banking institution. 
These campaigns were based on phone calls. Often, more than one contact with the same client was required to ascertain whether the product (bank term deposit) would be subscribed to or not.

Mission:
In this project, I will utilize k-nearest neighbors (knn) to build a classification model to predict the target variable, which indicates whether the client subscribes to the bank term deposit.

Data Transformation:
For data transformation, I used StandardScaler to standardize numerical variables, and for categorical variables, I transformed them into dummy variables.

Model training:
For model training, I divided the data into an 80% training set and a 20% test set to determine the optimal value for n. 
After finding the optimal n, I utilized it to predict the entire dataset and generated a confusion matrix and ROC curve to evaluate the model's performance.
