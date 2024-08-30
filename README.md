# DATE:
# EX-4 EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm: 
### Step1 :
Import the numpy module to use the built-in functions for calculation.
### Step 2:
Prepare the lists from each equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program
## Program:
```
#Developed by: BHUVANESHWARI M
#RegisterNumber: 212223230033
import numpy as np
a=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
val,vec=np.linalg.eig(a)
print(f"Eigen values are {val} and Eigen Vectors are {vec}")
```
## Output:
![Screenshot 2024-08-30 202409](https://github.com/user-attachments/assets/e4a0005d-8aac-40e9-b5a7-85b2142417f3)
![Screenshot 2024-08-30 202433](https://github.com/user-attachments/assets/d5941259-42cd-4465-8dc8-0d16ae710541)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
