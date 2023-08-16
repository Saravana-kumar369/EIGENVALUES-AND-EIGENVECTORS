# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy library.
### Step 2:
Initialize the value of matrix in A
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print the eigenvalues and eigenvectors

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: SARAVANA KUMAR
#RegisterNumber:212222230133
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![image](https://github.com/Saravana-kumar369/EIGENVALUES-AND-EIGENVECTORS/assets/117925254/73b2dd18-101c-4bd2-a073-bf4b7bc42667)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
