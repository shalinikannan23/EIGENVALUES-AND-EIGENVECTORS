# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy as np
### Step 2: Initialize the matrix using np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the output
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: SHALINI.K
#RegisterNumber: 212222240095
import numpy as np
a=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {}'.format(values,vectors))
```
## Output:
![image](https://github.com/shalinikannan23/EIGENVALUES-AND-EIGENVECTORS/assets/118656529/3cb307c3-2131-4f4e-b17b-a9c8ff92d050)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
