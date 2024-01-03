# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Import the numpy module to use the built-in functions for calculation 
### Step 2:Prepare the lists from each eigen values equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:End the program 

## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by:N.neethiventhan 
#RegisterNumber:23006643
import numpy as np
A = np.array([[2,2],[1,3]])
eigenvalues,eigenvectors = np.linalg.eig(A)
print("Eigen values are",eigenvalues,"and", "Eigen Vectors are",eigenvectors)
~~~
## Output:
![image](https://github.com/Neethiventhan123/EIGENVALUES-AND-EIGENVECTORS/assets/148514848/6fce606f-3b28-43ac-9c2b-cd61e5a2ff4d)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
