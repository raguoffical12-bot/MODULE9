### EX: 9.4 find the square root of all elements in a list using list comprehension.     
### Aim: Write a Python program to calculate the square root of all elements in a given list using list comprehension.


### Algorithm:

Start
Read the number of elements 
Initialize an empty list to store the input numbers.
For 𝑖=1i=1 to 𝑛 n:
Read the number and append it to the list.
Use list comprehension with the math.sqrt() function to calculate the square root of each element in the list.
Print the original list.
Print the list of square roots.
End

### Program:
```
reg no:212223070021
name:Ragunandhan S
n=int(input())
l=[]
for i in range(n):
    x=float(input())
    l.append(x)
sq_l=[item**0.5 for item in l]
print(l)
print(sq_l)

```
### Output:
![image](https://github.com/user-attachments/assets/ab25c3bf-1a04-43cb-be5e-c3cb149fa06a)


### Result: Thus, the given program is implemented and executed successfully.
 

 

