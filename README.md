# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. intialize numpy from python library using import
2. declare variable A as a matrix and get input from user 
3. formulate lu decomposition formula to declaring variables
4. print the declared variables for output

## Program:
(i) To find the L and U matrix
```

Program to find the L and U matrix.
Developed by: Ranjan Kumar .G
RegisterNumber: 212223240138

```

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
Developed by: Ranjan kumar .G
RegisterNumber: 212223240138
*/
```
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b= np.array(eval(input()))
lu, piv lu_factor(A)
x = lu_solve((lu, piv), b)
print (x)
```

## Output:

![alt text](<Screenshot 2024-04-22 122658.png>)
![alt text](<Screenshot 2024-04-22 122725.png>)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

