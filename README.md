# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculations.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
end the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: MANIKUMAR D.K
#RegisterNumber: 23013588
import numpy as np
A=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```


## Output:
![Screenshot 2024-04-07 105004](https://github.com/MANIKUMARDK/EIGENVALUES-AND-EIGENVECTORS/assets/147215581/34917523-1e0d-473b-b5b3-49ef9f95831b)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
