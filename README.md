# bootcamp_hw20_credit-risk-classification
Alison McCondichie - Homework 20 - Supervised Learning

Overview: The purpose of this project is to train a machine learning model on lending data in order to analyze credit card loan risk. The machine learing model should be reiterable in order to test other types of machine learning models, and should easily display the results for quick comparison and accuracy testing. I created a formula to streamline the process of testing multiple models on one set of data. The rubric required a Logistic Regression model. I also ran the data through a Random Tree model and a KNN model to show comparison.

Results of the Logistic Regression Model:
- TAccuracy Score: The model has a promosing 99%. There are no problematic signs of overfitting in the training data. 
- Precision score: The precision score shows that the model is more accurate in predicting healthy risks loans, as opposed to high-risk loans. This imbalance in prediction lowers my confidence in the model a bit. 
- Recall score: Again, we see an imbalance. There is a Healthy Loan score of 100% and a High-Risk Loan Score of 95%. However, it is less significant than the precision score and still overall promosing. 

Summary: The Logistic Regression model has a slight tendency to return fasle positives and has the most accuracy with true negatives. Despite this imbalance, the accuracy scores are optimistic. 
Compared to other models I tested, the Logistic Regression was the most accurate. While the KNN model had slightly better metrics, it is known to struggle with large datasets and is at risk for dimensionality issues, so I would not sacrifice that for such a small boost in predictive metrics. 
In conclusion, though I do not have 100% confidence in the overall results, I would recommend the Logistic Regression model over the other models tested in this notebook. 