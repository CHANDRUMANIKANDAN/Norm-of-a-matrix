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
# Register No:22009010
# Developed By:CHANDRU M
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
a=np.linalg.norm(mat,1)
norm="{:.2f}".format(a)
print(norm)



# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
a=np.linalg.norm(mat,2)
norm="{:.2f}".format(a)
print(norm)



# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
a=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(a)
print(norm)




```

## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>![Screenshot_20230124_085231](https://user-images.githubusercontent.com/118644502/214338048-d7755ba6-e680-4a6c-8b26-a5a99a441b7c.png)


### 2-Norm of a Matrix
<br>
<br>
<br>![Screenshot_20230124_085827](https://user-images.githubusercontent.com/118644502/214338067-f877090a-d7a8-4c7c-b73d-1bcaee718d4d.png)


### Infinity Norm of a Matrix
<br>
<br>
<br>![Screenshot_20230124_090041](https://user-images.githubusercontent.com/118644502/214338091-e08212ba-8e3b-473d-9a23-cc0af6090f99.png)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
