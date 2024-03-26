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
#Developed by  :   Navinkumar V
#RegisterNumber:  212223230141

import numpy as np
a = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors= np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![Screenshot 2024-03-26 143159](https://github.com/navinofficial/EIGENVALUES-AND-EIGENVECTORS/assets/151710204/5fe9958a-d87e-4819-8ceb-244e50601f31)



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program

