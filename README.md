# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the vari
4. Print the variable 'X'

## Program:
(i) To find the L and U matrix

```
/*
Program to find the L and U matrix.
Developed by: Shanthosh G
RegisterNumber: 2305003008

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix

```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Shanthosh G
RegisterNumber: 2305003008

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
*/
```

## Output:
![Screenshot 2024-05-23 040044](https://github.com/shanthosh397/LU-Decomposition/assets/153431200/1b3366d5-f478-4db2-b379-c96e4e2824f8)

![Screenshot 2024-05-23 040111](https://github.com/shanthosh397/LU-Decomposition/assets/153431200/2e6b08c4-9935-4814-addf-b824d5944971)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

