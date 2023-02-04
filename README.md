# deep-learning-challenge

## Report

### Overview
This project created a predictive model to determine whether applicants would be successful if funded by a nonprofit foundation called Alphabet Soup.
To achieve this, data was preprocessed to remove any irrelevant columns, rare variable values binned and categorical data was converted into numerical data for modelling.
The initial model fell slightly below 75% so another attempt was made to optimise the model and increase its accuracy.


### Results

Data Preprocessing

What variable(s) are the target(s) for your model?
IS_SUCCESSFUL

What variable(s) are the features for your model?
APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.

What variable(s) should be removed from the input data because they are neither targets nor features?
EIN and NAME
