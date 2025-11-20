# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```
Write a program to find the eigenvalues and associated eigenvectors for the matrix
[-2,2,-3],[2,1,-6],[-1,-2,0]

#Program to find the eigen values and eigen vectors.
#Developed by: DHAMODHARAN S 
#RegisterNumber: 25009463

import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```

## Output:
<img width="1851" height="925" alt="ex4 ss1" src="https://github.com/user-attachments/assets/290623a4-fb7d-44d8-9376-277433491a22" />
<img width="1860" height="965" alt="ex4 ss2" src="https://github.com/user-attachments/assets/06e09443-31d1-4fcf-8b30-f70e4a547c58" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
