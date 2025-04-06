# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program 

## Program:

```
#Program to find the eigen values and eigen vectors.
#Developed by: K.Mohamed Althaf
#RegisterNumber: 212224240089
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigenvalues,eigenvectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(eigenvalues,eigenvectors))
```

## Output:

![Screenshot 2025-03-23 164904](https://github.com/user-attachments/assets/a38705fb-8f33-49ad-b504-5a85f0df24ab)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
