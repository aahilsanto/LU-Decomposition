# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1: 
Import the numpy and scipy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the scipy.linalg.lu we can compute l and u matrix and find the decomposition of the matrix using lu_solve and lu_factor.
### Step 4: 
End the program 

## Program:

(i) To find the L and U matrix

```
'''Program to find L and U matrix using LU decomposition.
Developed by: A Ahil Santo
RegisterNumber: 212224040018
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```

(ii) To find the LU Decomposition of a matrix

```
'''Program to solve a matrix using LU decomposition.
Developed by: 
RegisterNumber: 
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
s=lu_solve((l,p),b)
print(s)
```

## Output:

L and U matrix

<img width="1022" height="810" alt="image" src="https://github.com/user-attachments/assets/a50008b2-cf66-41ac-b697-01e0816af0b7" />

LU Decomposition

<img width="1011" height="808" alt="image" src="https://github.com/user-attachments/assets/e08a2629-a377-4865-a26a-462dca08749d" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

