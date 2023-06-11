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
df=pd.read_csv("/content/cars (1).csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("coefficient",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))




```
## Output:

![2023-06-08 (2)](https://github.com/kathiravan13/Multivariate-Linear-Regression/assets/119831303/495dce25-12fc-4617-aadf-ccdb2796b0c1)


### Insert your output

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
