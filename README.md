# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import Numpy module and lu library from scilig modules
2.Declare the array
3.Using lu library calculate the Lower triangle matrix and upper triangle matrix
4.End the program

## Program:
(i) To find the L and U matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: Madhesh V
RegisterNumber: 212225040214
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
![WhatsApp Image 2026-03-28 at 8 54 52 AM](https://github.com/user-attachments/assets/ceb340d3-ac96-4804-a2db-1f636cbd6868)



(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Madhesh V
RegisterNumber: 212225040214
*/


# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```
<img width="1207" height="778" alt="519058241-e06ffe27-2f76-47be-a859-8216ff67e82e" src="https://github.com/user-attachments/assets/3b29546f-2152-48d9-86ba-d50bc5f76937" />

## Output:
<img width="1211" height="508" alt="519057864-a3121832-1f01-4f64-91c0-8536b8d7e759" src="https://github.com/user-attachments/assets/7e242d25-22f6-4f41-906f-0dcab2c58ea2" />
<img width="1211" height="271" alt="519058114-05c7859e-f837-43e6-9dd6-7cf8c7a60930" src="https://github.com/user-attachments/assets/d3ca8ff0-8648-4bb7-b386-5915579643e9" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

