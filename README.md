# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Impotr the numpy to use built-in functions for calculation.
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
end the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: JEEVAGOWTHAM S
#RegisterNumber:22008760
import numpy as np
a=np.array([[2,-3,0,],[2,-5,0],[0,0,3]])
result,v=np.linalg.eig(a)
print("Eigen values are",result,"and Eigen Vectors are",v)
```

## Output:
![output](/image/expected.png)
![output](/image/got.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
