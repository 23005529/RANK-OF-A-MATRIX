# RANK-OF-A-MATRIX
## AIM :
To write a python program to find the rank of a matrix
## EQUIPEMENT'S REQUIRED :
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM :
### Step 1: 
Import the numpy module to use the built-in function for calculation.  
### Step 2:
Prepare the lists from linear equation and assign in np.array().
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End the Program.
## PROGRAM :
```
#Program to find the rank of a matrix.
#Developed by: ALIYA SHEEMA
#RegisterNumber: 23005529

import numpy as np
A=np.array([[1,2,3],[3,6,9]])
solution=np.linalg.matrix_rank(A)
print(solution)
```
## OUTPUT :

Python program to find the rank of a matrix.

![Alt text](output.png)

## RESULT :
Thus the rank for the given matrix is successfully solved by  using a python program.

