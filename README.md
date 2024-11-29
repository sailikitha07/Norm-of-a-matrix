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

```
# Register No:24009865
# Developed By:sai likitha
<<<<<<< HEAD
# 1-Norm of a Matrix
=======
#  1-Norm of a Matrix

```

import numpy as  np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,1)
norm_matrix="{:.2f}".format(result)
print(norm_matrix)


# 2-Norm of a Matrix



import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,2)
norm_matrix="{:.2f}".format(result)
print(norm_matrix)



# Infinity Norm of a Matrix

<<<<<<< HEAD
=======
```

>>>>>>> 841fce8ad153b1f34120ffc9c3c8a3d2bb163c7f
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,np.inf)
norm_matrix="{:.2f}".format(result)
print(norm_matrix)

```

## Output:
### 1-Norm of a Matrix

![output2](norm1.png)

### 2-Norm of a Matrix

![output1](norm2.png)

### Infinity Norm of a Matrix

![output](norm3.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
