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
Prepare a list for each linear equation and assign in numpy.linalg()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the eigenvalue and eigen vector using print() function. End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:  JAYAVARTHAN P
#RegisterNumber:22008689
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
result,v=np.linalg.eig(a)
print("Eigen values are",result, "and Eigen Vectors are",v)
```

## Output:

![eigen 1](https://user-images.githubusercontent.com/121369281/209545255-86722490-5da1-4197-bfe7-4e3ede72594a.png)

![eigen2](https://user-images.githubusercontent.com/121369281/209545276-de56996d-7d26-472c-81d1-5d58f95c233d.png)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
