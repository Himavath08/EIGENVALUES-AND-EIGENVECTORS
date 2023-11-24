# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :  we have imported numpy which is needed
### Step 2: we have created a matrix using np.array with different values in it
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: finally,print the values of the eigen values and eigen vectors.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: M Himavath
#RegisterNumber:23010121
import numpy as np
m=([2,-3,0],[2,-5,0],[0,0,3])
w,v=np.linalg.eig(m)
print("Eigen values are",w,"and Eigen Vectors are",v)
```
## Output:
![image](https://github.com/Himavath08/EIGENVALUES-AND-EIGENVECTORS/assets/139110631/d48e3365-15ae-4c66-b8e2-a644af97a737)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
