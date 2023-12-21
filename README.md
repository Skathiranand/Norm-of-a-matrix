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
# Register No:Kathir anand S
# Developed By:212223100018
# 1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print('{:.2f}'.format(norm))

# 2-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))

# Infinity Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print('{:.2f}'.format(norm))
```
## Output:
### 1-Norm of a Matrix
![1 norm](https://github.com/Skathiranand/Norm-of-a-matrix/assets/147141136/b7e2ed03-3be7-4d62-8837-a041adff2e95)

### 2-Norm of a Matrix
![2 norm](https://github.com/Skathiranand/Norm-of-a-matrix/assets/147141136/c6cd1541-4162-4d54-b291-d53fe02707ad)

### Infinity Norm of a Matrix
![infinity norm](https://github.com/Skathiranand/Norm-of-a-matrix/assets/147141136/634bf62e-d18e-43a9-a2df-ad2a5162b1a4)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
