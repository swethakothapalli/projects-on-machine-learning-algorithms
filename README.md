# salary Prediction
Problem : Predict whether income exceeds $50K/yr based on census data. Also known as "Census Income" dataset

# Data Set Information:

Extraction was done by Barry Becker from the 1994 Census database. A set of reasonably clean records was extracted using the following conditions: ((AAGE>16) && (AGI>100) && (AFNLWGT>1)&& (HRSWK>0))

Prediction task is to determine whether a person makes over 50K a year.

# algorithms used:
used logistic regression, Random Forest, Naive Bayes and choose best one out of them

# Model Evaluation: 

For evaluating model used cross val score

finally saved the model as a okl object.
