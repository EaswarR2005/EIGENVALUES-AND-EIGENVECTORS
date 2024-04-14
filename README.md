# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step1 : 
Import the NumPy library and give it the alias 'np'. NumPy is used for numerical operations,
including finding eigenvalues and eigenvectors.
### Step 2: 
Create a 3x3 matrix 'A' using a nested list to represent rows.
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the calculated eigenvalues and eigenvectors to the console.
### Step 5:
End the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: EASWAR R
#RegisterNumber:212223230053
import numpy as np
matrix=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eigvalues,eigvectors=np.linalg.eig(matrix)
print("Eigen values are {:} and Eigen Vectors are {:}".format(eigvalues,eigvectors))
```
## Output:
![image](https://github.com/EaswarR2005/EIGENVALUES-AND-EIGENVECTORS/assets/146931525/522f0f50-d87e-4247-ae26-5594149009b0)
![image](https://github.com/EaswarR2005/EIGENVALUES-AND-EIGENVECTORS/assets/146931525/c10f97df-fc84-4a1c-b8ef-36256bba8bc0)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
