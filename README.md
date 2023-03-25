# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
### Step 1: 
Import numpy as np
### Step 2: 
Assign the values of the matrix to a variable using np.array
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the eigen values and eigen vectors.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Sneha Basyal M
#RegisterNumber: 212222240101

import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
evalues,evectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(evalues,evectors))
```
## Output:
![EIGENVALUES-AND-EIGENVECTORS](eg.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
