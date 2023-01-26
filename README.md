# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: SWETHA P
RegisterNumber: 22008542
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: SWETHA P
RegisterNumber: 22008542
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu,piv = lu_factor(A)
x = lu_solve((lu, piv), b)
print (x)
*/
```

## Output:
(i) To find the L and U matrix
![lu1](https://user-images.githubusercontent.com/120623583/214823526-604a0058-c8a6-4a50-b04c-415bef8c8f9b.png)

(ii) To find the LU Decomposition of a matrix
![lu2](https://user-images.githubusercontent.com/120623583/214823599-676bd6db-eabc-463f-9e95-8a5a42f3d87e.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

