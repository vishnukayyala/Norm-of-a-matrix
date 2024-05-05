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
'''
Program to find 2-norm of a matrix.
Developed by: yourname: VISHNU K.M
RegisterNumber: 212223240185

import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


Program to find 2-norm of a matrix.
Developed by: yourname : VISHNU K.M
RegisterNumber: 212223240185

import numpy as np

# Type your code here
import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


Program to find 2-norm of a matrix.
Developed by: yourname : VISHNU K.M
RegisterNumber: 212223240185
import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
## Output:
### 1-Norm of a Matrix
![WhatsApp Image 2024-05-05 at 15 47 09_dda339d6](https://github.com/vishnukayyala/Norm-of-a-matrix/assets/151489368/17a41ece-6435-4550-9f30-7f742c0b2270)


### 2-Norm of a Matrix
![WhatsApp Image 2024-05-05 at 15 47 39_d8d99615](https://github.com/vishnukayyala/Norm-of-a-matrix/assets/151489368/fb9156ae-653c-410e-b856-8994d071b206)

### Infinity Norm of a Matrix
![WhatsApp Image 2024-05-05 at 15 48 50_21200ff7](https://github.com/vishnukayyala/Norm-of-a-matrix/assets/151489368/a5f906a8-eab1-4ecc-8f9e-c62c08b7fe21)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
