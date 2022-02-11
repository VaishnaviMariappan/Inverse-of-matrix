# Inverse-of-matrix

## AIM:
To write a python program for multiplying two matrix.
## ALGORITHM:
### Step 1:
Import Numpy module as np.
### Step 2:
Create empty lists.
### Step 3:
Get input from the user for number of rows and columns.
### Step 4:
Use nested lists to append list.
### Step 5:
Print the inverse of the array using np.linalg.inv

## PROGRAM:
```
To write a python program to find the inverse of the array.
Developed by: Vaishnavi M
Register no: 21500310

import numpy as np
no_of_rows=int(input())
no_of_cols=int(input())
l1,l2=[],[]
for i in range(no_of_rows):
    a=[]
    for j in range(no_of_cols):
        t=int(input())
        a+=[t]
    l1+=[a]
print(l1)
print(np.linalg.inv(l1))

```

## OUTPUT:
![ouput](./output1.png)

## RESULT:
Thus a program is written to find the inverse of the array. 
