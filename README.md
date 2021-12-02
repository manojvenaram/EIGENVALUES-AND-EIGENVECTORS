# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in function for calculation.
### Step 2: 
Prepare the list from each linear equation and assign in np.array().
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.
## Program:
```import numpy as np
a=np.array([[2, 2], [1, 3]]) 
values,vectors=np.linalg.eig(a) 
print("Eigen values are",values,"and Eigen Vectors are",vectors) 
```
## Output:
![git logo](output1.jpeg)
![git logo](output2.jpeg)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
