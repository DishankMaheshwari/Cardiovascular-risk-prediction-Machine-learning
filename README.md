# Cardiovascular-risk-prediction-Machine-learning

Index:

1.Business context

2.Problem statement

3.Importing the libraries and the dataset

4.Understand the data

5.Data cleaning

6.Handling missing data

7.Exploratory data analysis

8.Feature selection

9.Data preprocessing

10.ML model implementation

11.Results

12.Summary and conclusions

13.References

# Business Context
The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients' information. It includes over 4.000 records and 15 attributes. Each attribute is a potential risk factor. There are both demographic, behavioral, and medical risk factors.

# Problem Statement
The aim of this capstone project is to develop a predictive model using a dataset from an ongoing cardiovascular study conducted in Framingham, Massachusetts. With over 4,000 records and 15 attributes, the goal is to accurately classify patients and determine their 10-year risk of future coronary heart disease (CHD). By analyzing demographic, behavioral, and medical risk factors, this project seeks to provide valuable insights and predictions that can assist healthcare professionals in identifying individuals at higher risk of developing CHD, enabling early intervention and personalized preventive measures.

# Data Description
Demographic:

Sex: male or female ("M" or "F")

Age: Age of the patient (Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)

Education: The level of education of the patient (categorical values - 1,2,3,4)

Behavioral:

is_smoking: whether or not the patient is a current smoker ("YES" or "NO")

Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any 
number of cigarettes, even half a cigarette.)

Medical (history):

BP Meds: whether or not the patient was on blood pressure medication (Nominal)

Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)

Prevalent Hyp: whether or not the patient was hypertensive (Nominal)

Diabetes: whether or not the patient had diabetes (Nominal)

Medical (current):

Tot Chol: total cholesterol level (Continuous)

Sys BP: systolic blood pressure (Continuous)

Dia BP: diastolic blood pressure (Continuous)

BMI: Body Mass Index (Continuous)

Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)

Glucose: glucose level (Continuous)

Predict variable (desired target):

10-year risk of coronary heart disease CHD(binary: “1”, means “Yes”, “0” means “No”)
