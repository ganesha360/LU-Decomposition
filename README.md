# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. First,we want to import nump
2. Then we want import scipy.linalg and import lu for lu decomposition
3. Then we want to assume a input
4. Then print a result.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Ganesh R
RegisterNumber: 22009090
*/
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Ganesh R
RegisterNumber: 22009090
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![output](./Web%20capture_12-1-2023_124520_lms.ai.saveetha.ac.in.jpeg)
![output](./Web%20capture_12-1-2023_124552_lms.ai.saveetha.ac.in.jpeg)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

