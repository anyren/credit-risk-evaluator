# Credit Risk Evaluator

In this assignment, we were tasked with building a machine learning model to predict whether a loan will be approved or not based on information about the applicant. We were required to build both a Logistic Regression model and Random Forest Classifier and to predict which would be more successful at predicting. The source data can be found in the `Resources` directory and all analysis and comments are in `Credit Risk Evaluator.ipynb`.

## Prediction
Before running the analysis, I predicted the logistic regression would score better. I based this on the fact that we are looking for a binary outcome (approved or not-approved) and that is what this algorithm was created to do.

## Outcome
Both models scored very high accuracy on the test data, though the logistical regression edged out the random forest classifier by a fraction of a percent (99.4% versus 99.2% respectively). The largest difference was in time to run; the random forest classifier took significantly longer. This would present more of a challenge for large datasets.