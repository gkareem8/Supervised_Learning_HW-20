# Supervised_Learning_HW-20
Provide an overview that explains the purpose of this analysis. 
Using a bulleted list, describe the accuracy, precision, and recall scores of the machine learning model.
Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning. 

The goal of this analysis is to build a Logistic Regression model to predict the loan status (whether a loan is healthy or high-risk) based on a set of financial features. The model uses historical data about loans to classify them as either healthy loans (0) or high-risk loans (1), which can assist financial institutions in identifying and managing risky loans. 

. Accuracy: The proportion of correct predictions (both true positives and true negatives) out of all predictions.
Example: Accuracy = (True Positives + True Negatives) / Total Predictions

.Precision: The ratio of correct positive predictions (true positives) to all predicted positives (true positives + false positives). Precision answers the question: "Of all the loans predicted as high-risk, how many actually were high-risk?"
Example: Precision = True Positives / (True Positives + False Positives)

.Recall: The ratio of correct positive predictions (true positives) to all actual positives (true positives + false negatives). Recall answers the question: "Of all the actual high-risk loans, how many were correctly predicted?"
Example: Recall = True Positives / (True Positives + False Negatives)

I would not recommend this model due to the company cannot afford to miss high-risk loans which could lead to financial loss. This model might need further improvements, particularly in recall. Consider testing other models or adjusting hyperparameters for a better balance between precision and recall. By balancing accuracy, precision, and recall, the model can be refined for optimal risk prediction performance.
