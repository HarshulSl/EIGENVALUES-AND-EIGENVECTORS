# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :  import numpy modules as np
### Step 2: Define the matrix as numpy array.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the result using print() function

## Program:
```
#Developed by: Harshul SL
#RegisterNumber: 212224230090
import numpy as np
a = np.array([[2,2],[1,3]])
values,vectors = np.linalg.eig(a)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```
## Output:
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/df36a1c7-2581-47ee-bf40-896a3107e342" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
