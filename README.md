# Leptospirosis Prediction
Leptospirosis is a bacterial infection caused by spirochetes of the genus Leptospira. It is a zoonotic disease, meaning it can be transmitted from animals to humans, and is commonly found in soil and water, particularly in areas with warm temperatures and high rainfall. Leptospirosis poses a global health concern, affecting both humans and a wide range of animals.

The symptoms of leptospirosis can vary, but commonly include high fever, headache, muscle aches, chills, vomiting, and red eyes. In severe cases, the infection can lead to organ damage, such as liver or kidney failure, and in rare instances, it can be fatal. Prompt diagnosis and treatment are important to prevent complications and ensure a successful recovery.

In this project, the leptospirosis dataset will be used to develop a machine learning model capable of predicting the leptospirosis status of patients (1-confirmed, 2-not detected) based on symptoms, clinical tests, demographic details, and other relevant factors. The significance of different variables in predicting leptospirosis status will be explored, and the performance of models incorporating various combinations of these variables will be compared.

Random Forest Provided the highest accuracy as 0.924460432    with hyper parameters 
Random Forest Best Parameters: {'classifier__max_depth': None, 'classifier__min_samples_leaf': 1, 'classifier__min_samples_split': 5, 'classifier__n_estimators': 100}
Random Forest Best Cross-Validation Accuracy: 0.9314907667848844
Random Forest Test Accuracy: 0.9244604316546763

# Description of the dataset

 leptospirosis_dataset contains data of 1387 patients related to leptospirosis and 806 variables. The variable “Final” (last column) reports the leptospirosis status of the patient (1-confirmed, 2-not detected).
