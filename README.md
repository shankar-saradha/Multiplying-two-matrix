# Multiplying-two-matrix

## AIM:  python program to multiply two arrays using numpy

## ALGORITHM:

### Step 1:import numpy module 
### Step 2: create two empty list 
### Step 3:initate for loop and get inputs 
### Step 4:call numpy function 
### Step 5:print the out put 

## PROGRAM: 
~~~
import numpy as np 
a=list()
b=list()
c=int(input())
for i in range(c):
    a.append(int(input()))
for j in range(c):
    b.append(int(input()))
arr1=np.array(a)
arr2=np.array(b)
product=np.multiply(a,b)
print("Product of two arrays is:",product)
~~~

## OUTPUT:
![Screenshot 2022-02-11 113818](https://user-images.githubusercontent.com/93978702/153544932-4d2cc543-3132-4546-b662-3d1c2908695d.png)


## RESULT:
Hence the output has been achieved 
