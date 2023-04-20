# machine-learning- Stroke Prediction
A classic classification problem with following descriptions will be addressed using my machine learning skills

1. Source of data

Data set is from Kaggle, and the original reference can be found in [here](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)

2. Brief description of data

According to the World Health Organization (WHO), stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.

3. What is the target?

I intend to predict whether a patient is likely to get stroke, 1 for getting stroke and 0 for not getting stroke,based on the features like gender, age, various diseases, and smoking status. 

4. What does one row represent? (A person?  A business?  An event? A product?)

Each row in the data provides relavant information about the patient.

5. Is this a classification or regression problem?

It is going to be a classification problem since we are predicting with 1 and 0  whilst 1 means if the patient had a stroke and 0 means if not.

6. How many features and rows does the data have?

There are 11 featues and 5110 rows in this data. 

7. What, if any, challenges do you foresee in cleaning, exploring, or modeling this dataset?


*   Cleaning: missing value

*   Exploring: finding out correlations between people with stroke AND their health ststus.

*   Modeling: will start with baseline, then add logreg, then end up with confusion matrix on oserving type 1 and type 2 errors.
