# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import the numpy module to use the built-in function for calculation
2.Assign in np.array()
3.Using the np.linalg.solve(),we can find the solution.
4. End the program.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: praveen s
RegisterNumber: 22009060
*/
import numpy as np 
from scipy.linalg import lu 
A= np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:praveen s 
RegisterNumber: 22009060
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print (x)
```

## Output:


![Screenshot_20230125_035747](https://user-images.githubusercontent.com/120218611/214587159-b2e40ac2-8b33-414f-a51f-52257094ac59.png)

![Screenshot_20230125_035759](https://user-images.githubusercontent.com/120218611/214587190-e00ddcbb-760f-4ade-b367-0c32e6ab3fd0.png)


## result:

Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

