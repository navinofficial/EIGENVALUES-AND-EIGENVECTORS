# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by  : Bharathraj P
#RegisterNumber: 212223230031

import numpy as np
a = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors= np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![image](https://github.com/Bharathraj2006/EIGENVALUES-AND-EIGENVECTORS/assets/152376845/d8d59668-2b2c-49d9-92a1-74a6ae9b58b2)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program

