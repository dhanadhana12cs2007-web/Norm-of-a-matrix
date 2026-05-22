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
# Register No:212225220021
# Developed By:V.DHANADEVAN
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np


A = np.array(eval(input()))


norm = np.linalg.norm(A, 1)


print(f"{norm:.2f}")



# 2-Norm of a Matrix


import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np


A = np.array(eval(input()))


norm = np.linalg.norm(A,2)


print(f"{norm:.2f}")

# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array(eval(input()))


norm = np.linalg.norm(A, ord=np.inf)


print(f"{norm:.2f}")



```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="1208" height="496" alt="image" src="https://github.com/user-attachments/assets/1ff12899-452e-48d9-92f5-cdef9b12412e" />

### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="1143" height="375" alt="image" src="https://github.com/user-attachments/assets/87502549-6a58-4682-abb1-7c7bfa280d37" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="1106" height="358" alt="image" src="https://github.com/user-attachments/assets/22952fb9-696b-42b2-8d01-62b5b2a11502" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
