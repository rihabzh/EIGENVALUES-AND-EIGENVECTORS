# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: RIHAB ZAKKAIR HUSSAIN
#RegisterNumber: 212225230226
import os 
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np

a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eigenvalues,eigenvector=np.linalg.eig(a)
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvector}")
```

## Output:
<img width="1394" height="761" alt="Screenshot 2026-08-08 143125" src="https://github.com/user-attachments/assets/8d4ece36-fefb-4e4d-bc34-4611ad317c8e" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
