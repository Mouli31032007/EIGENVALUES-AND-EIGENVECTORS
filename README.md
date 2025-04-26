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
## Developed by: S.MOULIDHARAN
## Register number :212224240095
import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {}'.format(values,vectors))
```
## Output:
![image](https://github.com/user-attachments/assets/59593738-626b-42c9-8268-9ff9a271a52f)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
