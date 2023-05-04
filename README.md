
![image](https://user-images.githubusercontent.com/126204698/236042392-8184f68f-c2ad-4e97-b984-a6b83ccb56ae.png)

[image reference](https://insights.eisenhowerhealth.org/stroke-awareness-befast/)

# Stroke Prediction using Machine Learning Models
A classification dataset will be addressed with machine learning skills. 

1. Questions to be answered to general public and stakeholders.

- Which feature is most likely related with stroke?

- In a very imbalance data where only 5% of the people have stroke, how to train the machine learning models that best identify the risk of stroke?

2. Key Insights - Age

- For general public who are 50 year or older, it is suggested to actively check the [symptom of stroke](https://www.cdc.gov/stroke/signs_symptoms.htm). Refer to visulizations below for more.
 
![image](https://user-images.githubusercontent.com/126204698/236043513-aadadc10-c72f-4ced-97d2-ccf2c35d0909.png)

- From scatterplots , it is shown that strokes occurs on older population especially after 50 years old.

![image](https://user-images.githubusercontent.com/126204698/236043575-9256e9b2-5427-4b2a-9298-c15c23675915.png)

- Bar chart here suggests most of the stroke patient are within the age group of 60 to 80 years old.


3. Mahcine Learning Results and Recommendations

![image](https://user-images.githubusercontent.com/126204698/236104979-1cf31caf-67ac-4cb4-ab12-4042297f4444.png)


- Among the models I applied, oversampled logistic regression can predict over 70% of stroke. 


- Model Selection: Since this is a classification question, models include SVC, Logistic Regression, Random Forest, KNN and XGBooster are used.


4. Data source and description

The original date can be found [here](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset).
On the stroke, our target, column, 1 stands for getting stroke and 0 for not getting stroke. Each rows provides relavant information, includig gender, age, smoking status and others, about the patient. Furthermore, data dictionary is listed below.

![image](https://user-images.githubusercontent.com/126204698/236043392-b2cece0a-f62b-4fc3-af8a-a0ce7f47933b.png)
