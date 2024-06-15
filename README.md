![image](https://github.com/vansh-py04/British-Airways-Data-Science-Job-Simulation-/assets/128248352/c03cb510-d954-4c5c-a445-a0125261d02d)

## Task 1
Conduct web scraping on unstructured data retrieved from the British Airways airline reviews page on Airline Quality. https://www.airlinequality.com/airline-reviews/british-airways

Analyze customer reviews using sentimental analysis to sort positive and negative reviews.

Preparing a powerpoint representation to highlight our insights and analysis.

## Task 2
Creating a classification model to predict customer buying behavior.

# Best performing model
![image](https://github.com/vansh-py04/British-Airways-Data-Science-Job-Simulation-/assets/128248352/4b6f3bfb-3305-4095-8e70-616abc780264)

# Observation
Given the significant class imbalance in the dataset, each model faced notable difficulties in accurately predicting instances belonging to the positive class. This imbalance skewed predictions towards the majority class, affecting the models' ability to correctly identify instances where the outcome was positive. This observation was consistent across all models evaluated, highlighting the ongoing challenge posed by class imbalance in predictive modeling tasks. 

Before implementing SMOTE (Synthetic Minority Over-sampling Technique) to address the class imbalance, the model exhibited the following performance metrics:

Precision: The model correctly identified 86% of instances where the actual outcome was 0 (no event), but only 55% where the outcome was 1 (event).
Recall: It captured 98% of all actual instances of 0 but only 11% of instances of 1.
F1-score: The harmonic mean of precision and recall was 0.92 for class 0 and a significantly lower 0.19 for class 1.

In summary, the model's strong performance in negative class identification did not translate into overall robustness and reliability across both classes, highlighting its lack of generalizability in accurately predicting positive outcomes.

---

## Certificate
[Link](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/British%20Airways/NjynCWzGSaWXQCxSX_British%20Airways_QxKzXzWxhzdZTfESN_1718478074841_completion_certificate.pdf)

