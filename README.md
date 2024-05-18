# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>

### Step2
<br>

### Step3
<br>

### Step4
<br>

### Step5
<br>

## Program:
```
import pandas as pd
  from sklearn import linear_model
  df=pd.read_csv("cars (1).csv")
  a=df[['Weight','Volume']]
  b=df[['CO2']]
  regr=linear_model.LinearRegression()
  regr.fit(a,b)
  print("Coefficient: ",regr.coef_)
  print("Intercept:",regr.intercept_)
  print("Account",regr.predict([[3300,1300]]))

```
## Output:
![maths exp 10](https://github.com/Nakul1411/Multivariate-Linear-Regression/assets/138849780/833f77b9-d7e7-4b4d-bde1-fa84e733b917)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
