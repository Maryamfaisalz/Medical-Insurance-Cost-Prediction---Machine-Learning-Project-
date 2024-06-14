# Medical Insurance Cost Prediction- Machine Learning Project 

![image](https://github.com/Maryamfaisalz/Medical_Insurance_Cost_Prediction/assets/79410940/d4a134d5-11cf-4d96-8e92-5f0a1371abf8)

**Problem Statement**

The goal of this project is to predict the insurance charges for individuals based on their personal information such as age, sex, BMI, number of children, smoker, and region. This can help insurance companies to set fair prices and customers to understand their insurance costs better.

**About the Dataset**

The dataset used in this project contains information about individuals and their insurance charges. The key features in the dataset are:

**Age:** The age of the individual.
**Sex:**  The gender of the individual (male/female).
**BMI:**  Body Mass Index, a measure of body fat based on height and weight.
**Children:**  The number of children/dependents covered by the insurance.
**Smoker:**  Whether the individual is a smoker (yes/no).
**Region:**  The residential region of the individual in the US (southeast, southwest, northeast, northwest).
**Charges:**  The insurance charges billed to the individual.

**Data Analysis**

We performed exploratory data analysis (EDA) to understand the dataset better:

1) Age Distribution:
Plotted the age distribution to see the spread of ages.

2) Gender Distribution:
Visualized the number of male and female individuals.

3) BMI Distribution:
Examined the distribution of BMI values.

4) Children Distribution:
Looked at how many children individuals have.

5) Smoker Distribution:
Compared the number of smokers to non-smokers.

6) Region Distribution:
Checked the distribution of individuals across different regions.

7) Charges Distribution:
Analyzed how the insurance charges are spread.

**Data Pre-processing**

To prepare the data for modeling, we encoded the categorical features into numerical values:

**Sex:** male (0), female (1)
**Smoker:** yes (0), no (1)
**Region:** southeast (0), southwest (1), northeast (2), northwest (3)

**Model Training**

We used Linear Regression to train our model:

1) Split the data into training and testing sets.
2) Trained the model using the training data.

**Model Evaluation**

We evaluated our model using the R-squared value, which tells us how well the model explains the variability of the target variable:

1) R-squared value on training data: 0.751
2) R-squared value on testing data: 0.744



