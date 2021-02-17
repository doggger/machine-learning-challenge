Logistic Regression Model:

The overall score of the tuned model was ~0.87. Upon closer analysis the model was very precise in predicting False_Positive, correctly predicting the class 98% of the time. The model struggled more in predicting the other two classes, only correctly predicting the CONFIRMED class 75% of the time. 

Support Vector Model:
The overall score of the tuned model was again ~0.87. The model also was very precise in predicting False_Positives, again correctly predicting the class 98% of the time. This model was slightly less precise in predicting CONFIRMED but slightly more precise in predicting CANDIDATE classes than the logistic regression model.

Overall Interpretation:
In summary, the logistic regression model fit the data better but only just slightly. The performance of the two models was very similar overall and accross the predicted classes. Since these models predict the false positive class with a very high degree of precision, this model could be used a screen to remove these data before using a more rigorous model to confirm the existance of an exoplanet. Knowing more about the data itself (the meaning behind all the numbers) may help in feature selection and in model selection. Models that employ self learning may result in more accuracy and precision.
