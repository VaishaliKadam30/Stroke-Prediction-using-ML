# Stroke-Prediction-using-ML

According to the World Health Organization (WHO) stroke is the 2nd
leading cause of death globally, responsible for approximately 11% of
total deaths. This dataset is used to predict whether a patient is likely
to get a stroke based on the input parameters like gender, age, various
diseases, and smoking status.

Background
Stroke is a condition that occurs when the blood supply to the brain is interrupted or reduced due to a blockage (ischemic stroke) or rupture of a blood vessel (hemorrhagic stroke). Without blood, the brain will not get oxygen and nutrients, so cells in some areas of the brain will die. This condition causes parts of the body controlled by the damaged area of the brain to not function properly.

Stroke is an emergency condition that needs to be treated as soon as possible, because brain cells can die in just a matter of minutes. Prompt and appropriate treatment measures can minimize the level of brain damage and prevent possible complications.

In this machine learning project, the overall topic that will be resolved is in the health sector regarding stroke, where it will try to predict the possibility of a stroke in a person with certain conditions based on several factors including: age, certain diseases (hypertension, heart disease) who are at high risk of developing stroke. strokes, cigarettes, etc.

As previously explained, stroke can kill the sufferer in a matter of minutes. Detecting stroke with the existing causative factors with the help of machine learning can be very useful in the world of health to detect stroke early in order to increase the sense of heart among sufferers so that strokes can be prevented early.

Business Understanding
To solve the problem of predicting stroke in a person, machine learning can be done that helps detect the possibility of stroke from the existing signs.

Problems to solve: Detection (Prediction) of the possibility of a stroke in a person

The purpose of making Machine Learning Model: The model can classify more than 90% of cases with certain conditions

Solution: Making Machine Learning with the KNearestNeighbors Algorithm that can classify someone who has the potential to have a stroke

Following is a description of each variable in the Dataset.

Variable Definition

● Id : unique identifier.
● Gender : "Male", "Female" or "Other".
● Age : age of the patient.
● Hypertension : 0 if the patient doesn't have
hypertension, 1 if the patient has hypertension
● Heart_disease : 0 if the patient doesn't have any heart.
diseases, 1 if the patient has a heart disease.
● Ever_married : "No" or "Yes".
● Work_type : "children", "Govt_jov", "Never_worked",
"Private" or "Self-employed".
● Residence_type : "Rural" or "Urban".
● Avg_glucose_level : average glucose level in blood.
● Bmi : body mass index.
● Smoking_status : “formerly smoked”, “never smoked”, “smokes” or
“Unknown”.
● Stroke : 1 if the patient had a stroke or 0 if not.

Target: stroke : Prediction target if the patient has a stroke then 1, otherwise 0 [int]

In the project, it can be seen from the number of targets, the number of patients who had a stroke was very small compared to patients who did not have a stroke. And with the heatmap it can be seen that gender does not affect a person can have a stroke or not.

Closing
Machine Learning Model to predict stroke in humans can be used because it reaches a recall score of 90.64% which is where this model can predict stroke very well although it still needs to be improved even up to a recall score of 100%.



