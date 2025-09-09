# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import NumPy library, np.linalg is its linear algebra module, which provides the eig() function to compute eigenvalues and eigenvectors.
### Step 2: Create a square matrix, Eigenvalues and eigenvectors can only be found for square matrices (same number of rows and columns).
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the result, This line displays the eigenvalues and eigenvectors.

## Program:
```Python
#Program to find the eigen values and eigen vectors.
#Developed by: Sitharth.B.S
#RegisterNumber:21224110048

import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eigen_values,eigen_vectors = np.linalg.eig(A)
print(f"Eigen values are {eigen_values} and Eigen Vectors are {eigen_vectors}")
```
## Output:
<img width="1313" height="826" alt="Screenshot 2025-09-09 140217" src="https://github.com/user-attachments/assets/1d9b1807-b5ff-4a46-aca2-b8778597454c" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
