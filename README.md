# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. give the prepared matrix and assign in np.array()
3. Using np.linalg.matrix_inv(),we can find the LU Decomposition of a matrix
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: v.sreeja
RegisterNumber:22004463 
*/
'''
import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: v.sreeja
RegisterNumber: 22004463
*/

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
```

## Output:
![output](Screenshot%20from%202023-01-25%2020-23-21.png)
![output](Screenshot%20from%202023-01-25%2020-23-32.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

