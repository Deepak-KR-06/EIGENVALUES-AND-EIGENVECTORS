# exp 4 - EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step 1: Import the numpy library to handle the matrix data structures and mathematical operations.
### Step 2: Define the 3x3 square matrix using np.array().
### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the calculated eigenvalues and eigenvectors to the console to view the results.

## Program:

```py
#Program to find the eigen values and eigen vectors.
#Developed by: Deepak K R
#RegisterNumber: 212225040057

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
matrix = np.array([[2, -3, 0], [2, -5, 0], [0, 0, 3]])
eigenvalues, eigenvectors = np.linalg.eig(matrix)
print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
```
## Output:

<img width="1297" height="372" alt="image" src="https://github.com/user-attachments/assets/72fb3987-dd35-4bcd-a56d-baa2f668c4ad" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
