# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1 :
Import the numpy module to use the built-in functions for calculation

## Step 2:
Prepare the lists from given matrix and assign in np.array()

## Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

## Step 4:
End of the programm.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Kannan N
#RegisterNumber:23013389
import numpy as np
A=np.array([[2,2],[1,3]])
eigenvalues, eigenvectors =np.linalg.eig(A)
print("Eigen values are",eigenvalues,"and","Eigen Vectors are",eigenvectors)
```

## Output:
![image](https://github.com/kannan-nagaraju/EIGENVALUES-AND-EIGENVECTORS/assets/145742755/5b1b244a-fb44-4acf-8c87-dbcbc13dd237)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
