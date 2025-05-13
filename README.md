# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Get the input matrix using np.array()   
### Step 2:
Find the 2-norm of the matrix using np.linalg.norm()
### Step 3:
Print the norm of the matrix in two decimal places.
### Step 4:
End the program.
## Program:
```
'''
Program to find 2-norm of a matrix.
Developed by: PAKANATI MONISH
RegisterNumber: 212224240109
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: PAKANATI MONISH
RegisterNumber: 212224240109
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

# Infinity Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: PAKANATI MONISH
RegisterNumber: 212224240109
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/da3f4b6c-7665-4d5d-834a-f43564460624)

### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/9eeec5c2-3f17-4a4c-b09d-31d0e143bc5f)

### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/69ae35fc-1bb9-4ad5-865b-1f0c47619bb6)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
