# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy as np
### Step 2: 
We have created a matrix using array and we will find inverse of this.
### Step 3: 
We can find the inverse of the martix by using np.linalg.inv and passing the matrix.
### Step 4: 
Finally, print the value of the inverse of the matrix.

## Program:
```python
#Program to find the inverse of a matrix.
#Developed by: SHANMUGAVEL.RM
#RegisterNumber: 22004339
import numpy as np
a=np.array([[2,1,1],[1,1,1],[1,-1,2]])
res=np.linalg.inv(a)
print(res)
```
## Output:
![output](/inv.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program

