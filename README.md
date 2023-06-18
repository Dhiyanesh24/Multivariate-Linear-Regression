# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import pandas as pd

### Step2 : Read the csv file.

### Step3 : Get the value of X and y variables.

### Step4 : Create the linear regression model and fit.

### Step5 : predict the CO2 emission of a car where the weight is 2300kg, and the volume is 1300cm3.

### Step6 : Print the predicted output.

## Program:
```
#Developed by : Dhiyaneshwar P
#Register Number : 212222110009
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars (1).csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))

```
## Output:
![image](https://github.com/Dhiyanesh24/Multivariate-Linear-Regression/assets/118362288/23f36791-622e-41ba-aed0-af02621230c7)



## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
