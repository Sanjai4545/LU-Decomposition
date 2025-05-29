# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. find the l and u matirx by using numpy and linalg from scipy
2.print the l matrix and u matirx
3.find the lu decomposition by using numpy and lu_factor and lu_solve
4.print the the following matrix

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```
(ii) To find the LU Decomposition of a matrix
```
/*
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)
```

## Output:
![image](https://github.com/user-attachments/assets/6d2200c5-c101-4b1f-9b8e-e653434a37d7)
![image](https://github.com/user-attachments/assets/340a63e9-af70-4b28-9858-67e77f4a5e08)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
