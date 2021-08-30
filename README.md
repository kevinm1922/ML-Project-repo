# Predictive Modeling for the Overall Risk of Heart Disease from Patient Data

**Background**


During the last century, there has been a rise inheart disease within the United States (U.S.) population due to genetic inheritance and the offset of many people choosing unhealthy lifestyle choices. Undesirable lifestyle patterns include smoking, poor diet, lack of physical activity, and consumption of excess alcohol which can promote the development of heart disease and exacerbate pre-existing conditions. According to the CDC, heart disease, which alludes to various types of heart conditions, is one of the mostleading and prevalent chronic diseases that affect all age groups, genders, and causes 1 in 4 deaths in the United States [link]( https://www.cdc.gov/heartdisease/facts.htm#:~:text=Heart%20disease%20is%20the%20leading,1%20in%20every%204%20deaths.). One common type of heart disease is known as coronary artery disease (CAD) which can detrimentally affect a person’s life by a heart attack [link](https://www.cdc.gov/heartdisease/index.htm). A variety of continual preventive efforts need to be established in order to disseminate the awareness of heart disease and improve health across a person’s life span. Therefore, from the Framingham heart disease dataset, the objective of this project is to predict the outcome (overall risk of developing heart disease) against the features (relevant/risk factors).


**Data**

This project will use a dataset provided by kaggle.com [link](https://www.kaggle.com/dileep070/heart-disease-prediction-using-logistic-regression) that focuses on a cardiovascular study on residents of the town of Framingham, Massachusetts. There are 4238 observations in the dataset. The dataset includes 1 response (10-year risk of coronary heart disease CHD) and 15 predictors (gender, age, education, current smoker, cigs per day, BP meds, prevalent stroke, prevalent hyp, diabetes, tot chol, sys BP, dia BP, BMI, heart rate, and glucose). We will perform a 80/20 split of the data for our training and test sets, since there are no site or longitudinal parameters that would make sense to split on.

**Proposed Methods** 

The plan is to accomplish our objective by filtering, cleaning the data, and using a logistic regression framework to assess the predicted outcome (10 year risk of CHD) versus the 15 features provided. The goal is to begin with logistic regression modeling, since this is the most straightforward, and there are literature examples from heart disease datasets available to build off of. If we are unable to learn a suitable model using a logistic regression framework, we may progress to more advanced machine learning models. We will perform an 80/20 split of the data for our training and test sets, since there are no site or longitudinal parameters that would make sense to split on. 
