# Cardiovasculardisease-analysis-Exploratory-Data-Analysis-with-Logistic-Regression
This is my project based on a dataset which has features telling about whether a person has Cardiovascular disease based on various features.

This dataset is also available on Kaggle

The following are the features of the dataset:-
1. Age | Objective Feature | age | int (days)
2. Height | Objective Feature | height | int (cm) |
3. Weight | Objective Feature | weight | float (kg) |
4. Gender | Objective Feature | gender | categorical code |
5. Systolic blood pressure | Examination Feature | ap_hi | int |
6. Diastolic blood pressure | Examination Feature | ap_lo | int |
7. Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal |
8. Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal |
9. Smoking | Subjective Feature | smoke | binary |
10.Alcohol intake | Subjective Feature | alco | binary |
11.Physical activity | Subjective Feature | active | binary |
12.Presence or absence of cardiovascular disease | Target Variable | cardio | binary |

I have performed various visualization techniques to understand the data properly and trained the model using the features.

Finally I have applied Logistic Regression to predict the target variable which was to tell whether a Person has Cardiovascular disease or not i terms of 1 and 0,
Where 1 - Person has disease
      0 - Person does not have the disease
This model has an accuarcy of 70.5%.

Any improvements to the code are welcomed through pull requests.
