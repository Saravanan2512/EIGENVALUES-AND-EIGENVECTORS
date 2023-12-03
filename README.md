# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy as np
### Step 2: 
Define the matrix 'a'
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the eigenvalues and eigenvectors

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: SARAVANAN G
#RegisterNumber:23005445

import numpy as np
a=[[4,2],[2,4]]
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![image](https://github.com/Saravanan2512/EIGENVALUES-AND-EIGENVECTORS/assets/144979117/d2ffa069-a278-4908-b3f9-cf2b68db5fed)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
