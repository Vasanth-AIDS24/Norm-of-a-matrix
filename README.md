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
# Register No:24900136
# Developed By:Vasanth P
# 1-Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,1)
print(result)



# 2-Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,2)
print(f"{result:.2f}")



# Infinity Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,np.inf)
print(result)




```
## Output:
### 1-Norm of a Matrix![Screenshot from 2024-12-02 20-39-18](https://github.com/user-attachments/assets/acbaf96c-47e2-4cca-9e10-dbf876f3b4d5)

<br>
<br>
<br>

### 2-Norm of a Matrix![Screenshot from 2024-12-02 20-39-56](https://github.com/user-attachments/assets/f981b317-ae61-4147-8d1e-9900bb2a9f9e)

<br>
<br>
<br>

### Infinity Norm of a Matrix![Screenshot from 2024-12-02 20-40-48](https://github.com/user-attachments/assets/05089697-ed7a-46a1-b76a-52fcae345b2f)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
