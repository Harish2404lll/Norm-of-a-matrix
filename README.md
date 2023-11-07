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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import numpy as np 
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)



# 2-Norm of a Matrix
import numpy as np 
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)



# Infinity Norm of a Matrix
import numpy as np 
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Harish2404lll/Norm-of-a-matrix/assets/141472096/9989e302-6e2a-4054-a43a-fbdb357fd8ed)


### 2-Norm of a Matrix
![image](https://github.com/Harish2404lll/Norm-of-a-matrix/assets/141472096/fd9a1157-17fe-4498-8aa1-87f96bf5452d)



### Infinity Norm of a Matrix
![image](https://github.com/Harish2404lll/Norm-of-a-matrix/assets/141472096/f11ee8cf-2ecd-4ac9-8e4f-12423cbee6f0)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
