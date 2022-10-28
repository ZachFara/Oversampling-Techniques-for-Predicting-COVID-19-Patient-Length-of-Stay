# Oversampling-Techniques-for-Predicting-COVID-19-Patient-Length-of-Stay
In this project we used a novel deep learning hyperparameter selection pipeline to optimize the classification of severe COVID-19 cases.

# Abstract

COVID-19 is a respiratory disease that caused a global pandemic in 2019. It is highly infectious and has the following symptoms: fever or chills, cough, shortness of breath, fatigue, muscle or body aches, headache, the new loss of taste or smell, sore throat, congestion or runny nose, nausea or vomiting, and diarrhea. These symptoms vary in severity; some people with many risk factors have been known to have lengthy hospital stays or die from the disease. In this paper, we analyze patients' electronic health records (EHR) to predict the severity of their COVID-19 infection using the length of stay (LOS) as our measurement of severity. This is an imbalanced classification problem, as many people have a shorter LOS rather than a longer one. To combat this problem, we synthetically create alternate oversampled training data sets. Once we have this oversampled data, we run it through an Artificial Neural Network (ANN), which during training has its hyperparameters tuned by using bayesian optimization. We select the model with the best F1 score and then evaluate it and discuss it.

However, the data for this project cannot be shared publicly. Only the code and results can be shared.

Here is the results of sweeping for every combination of data, please view the WandB results

Raw training data:
https://wandb.ai/zachs_team/keras_covid_project_imb?workspace=user-zfarahany

Weighted training:
https://wandb.ai/zachs_team/keras_covid_project_weights?workspace=user-zfarahany

Oversampled:
https://wandb.ai/zachs_team/keras_covid_project_oversampling?workspace=user-zfarahany

Undersampled:
https://wandb.ai/zachs_team/keras_covid_project_undersampling?workspace=user-zfarahany

SMOTE-NC data:
https://wandb.ai/zachs_team/keras_covid_project_smote?workspace=user-zfarahany
