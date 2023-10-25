# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
 Import the module numpy and assign the numpy as np
### Step 2: 
Initial a variable a and use np.array(),we can make a array
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
Print the value
## Program:
```py 
#Program to find the rank of a matrix.
#Developed by:SANJAY C
#RegisterNumber:23013498
import numpy as np
A = np.array([[3,2,5],[1,1,2],[3,3,6]])
rank = np.linalg.matrix_rank(A)
print(rank)
```
## Output:
![](./EXP02.png)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

