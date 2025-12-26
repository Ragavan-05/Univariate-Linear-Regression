# Implementation of Univariate Linear Regression
## Aim:
To implement univariate Linear Regression to fit a straight line using least squares.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1:
Import required libraries and store the input data � and �.
Step 2:
Calculate the mean of � and �.
Step 3:
Compute the slope � using the least squares formula.
Step 4:
Calculate the intercept �.
Step 5:
Form the regression equation � and predict the output.
## Program
```py
inport numpy as np
ieport matplotlib.pyplot as plt
t Preprocessing Input data
X* np.array([o, 1, 2, 3, 4, 5, 6,7, 8, 9])Y s np.array([, 3, 2, 5, 7, 8, 8, 9, 10, 12])plt.scatter(X，Y)
plt.show()
2
# Buildina the model
X nean s np.mean(X)Ymean s np.mean(Y)num 80
den s 0
for i in range(len(X)):
num s (X[]·X_mean)*(Y[1]·Y_mean)
den f= (x[1].xmean)**2
m = num / den
cs Ymean .m*x_mean
print (m, c)
#Mukiny predictions
Y pred a e'x+e
print(Y_pred)
plt.scatter(x, Y) Iactuol
plt. scatter(x, Y.pred, colo-'red')
plt.plot(lein(x), x(x)1,lain(Y.pred), sr(Y pred)l, colore'red') t predictn
plt.shcmo






```
## Output
</br>
</br>
</br>
</br>

## Result
Thus the univariate Linear Regression was implemented to fit a straight line using least squares.
