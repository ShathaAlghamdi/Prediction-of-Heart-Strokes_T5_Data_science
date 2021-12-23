# Prediction of Strokes
## Data Overview
According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths. 
This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

![name-of-you-image](https://raw.githubusercontent.com/ShathaAlghamdi/Prediction-of-Heart-Strokes_T5_Data_science/main/pics/hed.webp?token=AG55IGZBHQDY2XWRWDAOTCLBXEMGI)

## Table of contents
* [Data Description](#data-description)
* [Questions](#questions)
* [Algorithms](#algorithms)
* [Tools](#tools)
* [Source](#source)
* [MVP goals](#mvp-goals)
* [Authors](#authors)

## Data Description
The dataset consists of 12 features and 5110 observations.
Below is a description of the features: 

| Feature name  | Description   | Data type |
| ------------- | ------------- | ------------- |
| id       | Identification number of the individual |  int          |
| age       | age of the patient | float           |
| gender        | male or female | object       |
| hypertension           | person age    | int           |
| heart_disease        | Health related parameter, does person have heart disease | int         |
| ever_married        | Personal information, is person married on not? | object         |
| work_type      | Nature of work place | object      |
| Residence_type    | Residence type of the individual | object |
| avg_glucose_level     | average glucose level in blood for the individual | float |
| bmi      | body mass index of the individual | float |
| smoking_status      | Habitual information | object |
| stroke      | Our target, is person suffered heart attack | int |


## Questions
1. Does age has impact on strokes?

2. Does body mass index and glucose levels in a person, propel a heart stroke?

3. Assumption: Smoking can induce Stroke, is it true?

4. Assumption: Heart with a Heart Disease is prone to Stroke, is it true?

5. Assumption: Workload results in high blood pressure and that could lead to Stroke, is it true?

6. Assumption: Males are most susceptible to strokes due to high work related stress, is it true?

## Algorithms
- KNN
- Logistic Regression
- Random Forest
- Decision Tree
- Naive Bayes
- XGBoost
- SVM
- Gradient Boosting
- LightGBM

## Tools
- Libraries: 

![Pandas](https://img.shields.io/badge/pandas-330F63??style=flat&logo=pandas&logoColor=white)
![seaborn](https://img.shields.io/badge/seaborn-%2006600.svg??style=flat&color=blue)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg??style=flat&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg??style=flat&logo=scikit-learn&logoColor=white)
![nltk](https://img.shields.io/badge/nltk-%2006600.svg??style=flat&color=red)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg??style=flat&logo=plotly&logoColor=white)
![matplotlib](https://img.shields.io/badge/matplotlib-%233F4F75.svg??style=flat&color=9cf)
![pywaffle](https://img.shields.io/badge/pywaffle-%233F4F75.svg??style=flat&color=yellow)

- Softwares: 

![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg??style=flat&logo=jupyter&logoColor=white&color=orange)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg??style=flat&logo=visual-studio-code&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg??style=flat&logo=github&logoColor=white)
![Trello](https://img.shields.io/badge/Trello-%23026AA7.svg??style=flat&logo=Trello&logoColor=white)
![Microsoft Office](https://img.shields.io/badge/Microsoft_Office-D83B01??style=flat&logo=microsoft-office&logoColor=white)
![zoom](https://img.shields.io/badge/Zoom-2D8CFF??style=flat&logo=zoom&logoColor=white)
![Flask](https://img.shields.io/badge/flask-%23000.svg??style=flat&logo=flask&logoColor=white)


## Source
from Kaggle website [here](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset)

## MVP goals
- Awaring of the most common causes of strokes.
- Concluding who are the most susceptible to strokes from people.
- Realizing the difference between smokers and non-smokers in having strokes.
- Knowing the ages most likely to have strokes.

# Authors
[@rymyf](https://github.com/rymyf)

[@Munira-Alshahrani](https://github.com/Munira-Alshahrani)

[@ShathaAlghamdi](https://github.com/ShathaAlghamdi)
