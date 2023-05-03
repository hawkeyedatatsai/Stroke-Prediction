
![image](https://user-images.githubusercontent.com/126204698/236042392-8184f68f-c2ad-4e97-b984-a6b83ccb56ae.png)

[image reference](https://insights.eisenhowerhealth.org/stroke-awareness-befast/)

# Stroke Prediction using Machine Learning Models
A classification dataset will be addressed with machine learning skills. 

1. Questions to be answered to general public and stakeholders.

- Which feature is most likely related with stroke?

- In a very imbalance data where only 5% of the people have stroke, how to train the machine learning models and best identify the risk of stroke?

2. Mahcine Results and Recommendations

![image](https://user-images.githubusercontent.com/126204698/236060305-ada4b62e-f929-4abe-a6ae-a919359907f3.png)

Among the models I used, oversampled logistic regression can predict over 70% of stroke. 


3. Key Insights - Age

![image](https://user-images.githubusercontent.com/126204698/236043513-aadadc10-c72f-4ced-97d2-ccf2c35d0909.png)

- From scatterplots , it is shown that strokes occurs on older population especially after 50 years old.


![image](https://user-images.githubusercontent.com/126204698/236043575-9256e9b2-5427-4b2a-9298-c15c23675915.png)

- Bar chart above suggest most of the stroke patient are within the age group of 60 to 80 years old.

4. Models - 

- Since it is a classification question, models include SVC, Logistic Regression, Random Forest, KNN and XGBooster are used.

- Models below suggest the best chance to predict stroke. Normalized TP (true positive) is listed as in reality we hope it to be over 70%.

5. Data source and description

The original date reference can be found in [here](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset).
On the stroke, our target, column, 1 stands for getting stroke and 0 for not getting stroke. Each rows provides relavant information, includig gender, age, smoking status and others, about the patient. Furthermore, data dictionary is listed below.

![image](https://user-images.githubusercontent.com/126204698/236043392-b2cece0a-f62b-4fc3-af8a-a0ce7f47933b.png)
