# Supervised Machine Learning Homework - Predicting Credit Risk
## A review of the results

## Fit a LogisticRegression model and RandomForestClassifier model

Create a LogisticRegression model, fit it to the data, and print the model's score. Do the same for a RandomForestClassifier. You may choose any starting hyperparameters you like. Which model performed better? How does that compare to your prediction? Write down your results and thoughts.

        I used a Random Forest Classifier with a random state of 1 and 100 estimators and received a high score. Based on the predictors I expected a lower score based on any parameters I could have used. I was especially surprise after receiving score for the Balanced Random Forest Classifier model.

## Revisit the Preprocessing: Scale the data

The data going into these models was never scaled, an important step in preprocessing. Use `StandardScaler` to scale the training and testing sets. Before re-fitting the LogisticRegression and RandomForestClassifier models on the scaled data, make another prediction about how you think scaling will affect the accuracy of the models. Write your predictions down and provide justification.

        I expect there to be less accuracy when scaling since the size of our data  used in the homework is so large/robust. 

Fit and score the LogisticRegression and RandomForestClassifier models on the scaled data. How do the model scores compare to each other, and to the previous results on unscaled data? How does this compare to your prediction? Write down your results and thoughts.

        The accuracy for both LogisticRegression and RandomForestClassifier models reduced significantly after being scaled, especially when compared to the unscaled data.
