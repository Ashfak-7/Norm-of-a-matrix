# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:25003270
# Developed By:ASHFAK N

# 1-Norm of a Matrix

import numpy as np

i=np.array(eval(input()))

o=np.linalg.norm(i,1)

print(o)

# 2-Norm of a Matrix

import numpy as np

i=np.array(eval(input()))

o=np.linalg.norm(i,2)

print(f"{o:.2f}")


# Infinity Norm of a Matrix

import numpy as np

i=np.array(eval(input()))

o=np.linalg.norm(i,np.inf)

print(o)



```
## Output:
### 1-Norm of a Matrix


<img width="1282" height="368" alt="image" src="https://github.com/user-attachments/assets/f27b743f-f53e-48e3-bf61-0c67675e643e" />


### 2-Norm of a Matrix


<img width="1282" height="368" alt="image" src="https://github.com/user-attachments/assets/460cdee2-907f-405b-8c34-358cac8a0b71" />



### Infinity Norm of a Matrix


<img width="1282" height="368" alt="image" src="https://github.com/user-attachments/assets/898f8e62-4085-491a-9995-1c89d62d395b" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
