INVERSE-OF-A-MATRIX
Aim:
To write a python program to find the inverse of a matrix

Equipment’s required:
Hardware – PCs
Anaconda – Python 3.7 Installation / Moodle-Code Runner
Algorithm:
Step1 :
Import the numpy module to use the built-in functions for calculation

Step 2:
Prepare the lists from each linear equations and assign in np.array()

Step 3:
Using np.linalg.inv(),we can find the inverse of a matrix

Step 4:
End the program

Program:
```
exp-03
#Program to find the inverse of a matrix.
#Developed by:BHAVITRA B
#RegisterNumber:212225040047
import numpy as np
A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
X=np.linalg.inv(A)
print(X)
```
Output:
<img width="1276" height="259" alt="Screenshot 2026-02-05 134820" src="https://github.com/user-attachments/assets/93ade166-ce75-4927-a556-c0add2e9e700" />

Result:
Thus the inverse of given matrix is successfully solved using python program
