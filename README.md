# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy and scipy packages. 
2.  Read the input matrix as two dimensional array
3. Call the Built in function lu() to decompose the array.
4. print the output.

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: dhivyapriya. r
RegisterNumber: 22008389
```
import numpy as np

from scipy.linalg import lu

A=np.array(eval(input()))

P,L,U=lu(A)

print(L)

print(U)

(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: dhivyapriya. r
RegisterNumber: 22008389
```
import numpy as np

from scipy.linalg import lu_factor,lu_solve

A=np.array(eval(input()))

b=np.array(eval(input()))

lu,piv=lu_factor(A)

x=lu_solve((lu,piv),b)

print(x)

## Output:
i)![ludecomposition](./images/ludecomposition.png)
ii)![ludecomposition1](./images/ludecomposition1.png)


## Result:
Thus the program to find the L and U Decomposition and LU Decomposition of a matrix are written and verified using python programming.

