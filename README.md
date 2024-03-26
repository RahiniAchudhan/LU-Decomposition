# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step 1:
Import numpy library using import statement.
## Step 2:
From scipy package import lu().
## Step 3:
Get input from user and pass it as an array.
## Step 4:
Get P, L, U matrix using lu()
## Step 5:
Print L and U matrix
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: RAHINI.A 
RegisterNumber: 212223230165
*/
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: RAHINI.A
RegisterNumber: 212223230165
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)

```
## OUTPUT:
(i) To find the L and U matrix
![Screenshot (213)](https://github.com/RahiniAchudhan/LU-Decomposition/assets/145742838/d5a47ca7-b442-4474-998e-d92e401b409f)

(ii) To find the LU Decomposition of a  matrix
![Screenshot (214)](https://github.com/RahiniAchudhan/LU-Decomposition/assets/145742838/17f51b24-a3a7-4c97-bba9-c3228f1fe893)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

