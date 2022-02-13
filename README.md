# Inverse-of-matrix

## AIM:
To inverse of Matrix
## ALGORITHM:
### Step 1:
import numpy 
### Step 2:
create an empty list
### Step 3:
get input from the user
### Step 4:
use inverse fuction
### Step 5:
run and end the program

## PROGRAM:

import numpy as np
l1,l2=[],[]
n1,n2=int(input()),int(input())
for i in range (n1):
    for j in range (n2):
        values=int(input())
        l1.append(values)
    l2.append(l1)  
    l1=[]
print(l2)
Matrix=np.array(l2)
inverse=np.linalg.inv(Matrix)
print(inverse)

## OUTPUT:

![Output](.//p1.png)

## RESULT:

inverse of matrix is completed