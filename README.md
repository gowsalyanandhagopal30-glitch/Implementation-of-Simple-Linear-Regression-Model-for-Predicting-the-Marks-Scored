# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm

1. Import required libraries for data handling and model building.
  
2. Load the dataset and separate input (hours) and output (marks).
 
3. Split the data into training and testing sets.
 
4. Train the linear regression model using training data.
 
5. Predict and evaluate the marks using the trained model. 

## Program:
```
/*

Developed by: N.Gowsalya
RegisterNumber:  212225230085

import numpy as np
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression
X = np.array([1, 2, 3, 4, 5]).reshape(-1, 1)
Y = np.array([35, 50, 65, 70, 85])
model = LinearRegression()
model.fit(X, Y)
m = model.coef_[0]
b = model.intercept_

print("Slope (m):", m)
print("Intercept (b):", b)
x_input = float(input("Enter hours studied: "))
predicted_marks = model.predict([[x_input]])
print("Predicted Marks:", predicted_marks[0])
Y_pred = model.predict(X)

plt.scatter(X, Y, label="Actual Data")
plt.plot(X, Y_pred, label="Regression Line")
plt.xlabel("Hours Studied")
plt.ylabel("Marks Scored")
plt.title("Simple Linear Regression (Using sklearn)")
plt.legend()
plt.show()
*/
```

## Output:

<img width="718" height="646" alt="Screenshot 2026-04-22 092549" src="https://github.com/user-attachments/assets/905afb6b-5e5a-4752-b040-f4efd9c9e0d7" />



## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
