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
