# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step1 :
 Import the numpy module to use the built-in functions for calculation.
 ## Step 2:
 Type the program to be executed.
 ## Step 3:
 Using the lu(), we can find the solutions.
 ## Step 4:
 Print the value and end the program

## Program:
(i) To find the L and U matrix
```python
  Program to find the L and U matrix.
 Developed by:DHARSHINI S 
RegisterNumber: 23010890
 import numpy as np
 from scipy.linalg import lu
 A=np.array(eval(input()))
 P,L,U=lu(A)
 print(L)
 print(U)


(ii) To find the LU Decomposition of a matrix
Program to find the LU Decomposition of a matrix.
 Developed by:DHARSHINI S 
RegisterNumber:23010890 
from scipy.linalg import lu_factor,lu_solve
 import numpy as np
 arr=eval(input())
 constant=eval(input())
 A=np.array(arr)
 B=np.array(constant)
 result=lu_factor(A)
 solution=lu_factor(A)
 solution=lu_solve(result,B)
 print(solution)
```

## Output:
![lu decomposition](./5.LU%201.png)
![lu decomposition](./5.LU%202.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

