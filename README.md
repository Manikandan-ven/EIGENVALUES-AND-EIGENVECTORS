# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculations.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```
import numpy as np
a=np.array([[2,2],[1,3]])
values,Vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {}'.format(values,Vectors))
```

## Output:
![Screenshot 2024-12-02 091028](https://github.com/user-attachments/assets/434509a7-0e6a-43d1-bb8e-1add9463ef8b)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
