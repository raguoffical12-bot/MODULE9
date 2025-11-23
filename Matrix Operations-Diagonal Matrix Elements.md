### EX: 9.3 ADVANCED LIST PROCESSING
### Aim: To Write a Python program to Find the transpose of a matrix using list Comprehension.

### Algorithm:

STEP 1: Start.

STEP 2: Create a variable r and c for rows and columns. 

STEP 3: Get the value of r and c from user.

STEP 4: Define a function to create the matrix.

STEP 5 : Using list comprehension find the transpose of the matrix.

STEP 6: Print the result.

STEP 7 : Stop.

### Program:
```
reg no:212223070021
name:Ragunandhan S
def create(r,c):
            M=[]
        for i in range(int(r)):
             R = []
        for j in range(int(c)):
             x = int(input())
             R.append(x)
           M.append(R)
 return M
r,c = input().split()
matrix = create(int(r),int(c))
print(matrix)
T = [[r[i]for r in matrix]for i in range(len(matrix[0]))]
 print(T)
```
### Output:
![image](https://github.com/user-attachments/assets/4f9b1d3d-84d8-4a05-8ffe-28c11a1283e5)


### Result: Thus, the given program is implemented and executed successfully .
