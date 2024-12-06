# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1
Import the numpy module to use the built-in functions for calculation

Step 2
Prepare the lists from each linear equations and assign in np.array()

Step 3
Using the np.linalg.solve(), we can find the solutions.

Step 4
End the program

## Program:
1. To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: KISHORE.V 
RegisterNumber: 24901341
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu (A)
print(L)
print(U)
```
2. To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: KISHORE.V 
RegisterNumber: 24901341
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
![image](https://github.com/user-attachments/assets/54aa6caa-1e87-4274-b20e-25e45b0c1808)


![image](https://github.com/user-attachments/assets/afc7024a-7420-4c24-82f0-e7edfb8b4446)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

