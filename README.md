
![image](https://user-images.githubusercontent.com/126204698/236042392-8184f68f-c2ad-4e97-b984-a6b83ccb56ae.png)

[image reference](https://insights.eisenhowerhealth.org/stroke-awareness-befast/)

# Project Description and Objective
A binary classification dataset on predicting stroke is addressed with machine learning models. 

# Data Source and Description
The original date can be found [Kaggle](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset). On the stroke, our target, column, 1 stands for getting stroke and 0 for not getting stroke. Each rows provides relavant information, including gender, age, smoking status and others, about the patients. Furthermore, data dictionary is listed below.

![image](https://user-images.githubusercontent.com/126204698/236043392-b2cece0a-f62b-4fc3-af8a-a0ce7f47933b.png)

# Analytical Insights from Data Analysis

![image](https://user-images.githubusercontent.com/126204698/236043513-aadadc10-c72f-4ced-97d2-ccf2c35d0909.png)

- From scatterplots , it is shown that strokes occurs on older population especially after 50 years old.

![image](https://user-images.githubusercontent.com/126204698/236043575-9256e9b2-5427-4b2a-9298-c15c23675915.png)

- Bar chart here suggests most of the stroke patient are within the age group of 60 to 80 years old.

![image](https://github.com/hawkeyedatatsai/Stroke-Prediction/assets/126204698/40c7f7c5-3ebb-418d-a16b-f8e576963ece)

- The youngest and oldest of stroke patient is shown on the line chart above. Also noted that a huge amount of patients are over 70 years old.

# Machine Learning Models Approach and Results

![image](https://user-images.githubusercontent.com/126204698/236104979-1cf31caf-67ac-4cb4-ab12-4042297f4444.png)

- Model Selection: Since this is a classification question, models include SVC, Logistic Regression, Random Forest, KNN and XGBooster are used. The value of true positive (TP) is emphasized because ideally we want to precisely predict the stroke.

- Among the models I applied, ***oversampled logistic regression*** can predict over 70% of stroke. My recommendation is to use this model to identify individuals who may require medication or other interventions to reduce their risk of having a stroke.

- Resampling method makes impact as all models with TP >.5 are resampled.

- SMOTE Logistic Regresion, tuned SMOTE Logistic Regresion and tuned oversampling Logistic Regresioncan can identify more than 70% of TP. These models are more likely to be used and applied in the real world.

- Model tuning does not make much impact as tuned models have same or lower TP as models before tuning.

- Featured engineering strategy is applied by creating one extra column 'high_glucose'. It has the similiar chance to identify stroke as original data.

# Summary and Recommendation 

1. Questions to be answered to general public and pharmaceutical company stakeholders.

- Which features are most likely related with stroke?

- In a very imbalance data where only 5% of the people have stroke, how to train the machine learning models that best identify the risk of stroke and eventually apply to company decisions?

2. From Data Analysis and Machine Learning Models, here are the repsonses.

- For general public who are 50 year or older, it is suggested to actively check the [symptom of stroke](https://www.cdc.gov/stroke/signs_symptoms.htm) to raise the awareness of it. Meanwhile, other traits we studied from the dataset that could lead to stroke include : female, married, living at urban, working in private sector and never smoked. However, it does not suggest that a 25 yr old single male who smokes two packs of cigarette a day will not get stroke. In fact, these traits is describing the stroke at a broader sense. For instance, we observe there are more female than male that had stroke, and it could be related to pregancy or longer life. Working in a private sector at downtown big cities would probably generate more stress and imbalance work and sleep time, which ultimately cause bad health then the risk of stroke. Not to mention, CDC has asserted that [secondhand smoke increases the risk for stroke by 20−30%.](https://www.cdc.gov/tobacco/campaign/tips/diseases/heart-disease-stroke.html#:~:text=Secondhand%20smoke%20increases%20the%20risk%20for%20stroke%20by,increase%20your%20risk%20of%20having%20a%20heart%20attack.)




# Contact Info

Please direct all communications to hawkeyedatatsai@gmail.com
