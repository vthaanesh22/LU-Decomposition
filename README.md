# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm for L and U
1. Import the numpy module to use in build-in function for calculation
2. from scipy.linalg import lu
3. Enter the lists from each linear equation and assign in np.array()
4. using lu() and store it in the three variables 
5. print L and U matrix
6. End the program

## Algorithm for LU Decomposition
1. Import the numpy module to use in build-in function for calculation
2. from scipy.linalg import lu_factor,lu_solve
3. Enter the lists from each linear equation and assign in np.array()
4. using lu_factor() and store it in the three variables 
5. using lu_solve() ,we can find L and U matrix
6. End the program
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: V.Thaanesh
RegisterNumber: 23003843

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)


*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: V.Thaanesh
RegisterNumber: 23003843

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)


*/
```

## Output:
![output](/Screenshot%202023-07-26%20143425.png)
![output](/Screenshot%202023-07-26%20143457.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

