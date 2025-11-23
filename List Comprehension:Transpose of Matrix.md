### EX: 9.2 LIST COMPREHENSION
### Aim: To Write a Python class program to generate all even numbers between 200 and 300 and store in a list using list comprehension.
### Algorithm:
STEP 1: Start.

STEP 2: Create a class.

STEP 3: Create variable a,b, and c for upper limit,lower limit and condition.

STEP 4: Intialise the values in the class.

STEP 5 : Define a method and using list comprehension calculate the result.

STEP 6: Print the result.

STEP 7 : Stop.

### Program:
```
reg no:212223070021
name:ragunandhan S
class program:

      def  __init__(self,a,b,c):
                self.a=a
                self.b=b
                self.c=c
        def display(self):
               even = [i for i in range(self.a,self.c+1,self.b)]
               print(even)
a = int(input())
b = int(input())
c = int(input())

obj = program(a,b,c)
obj.display()
```
### Output:
![image](https://github.com/user-attachments/assets/0bbace20-aa99-41c4-a05c-63b5dcf04a7d)

### Result: Thus, the given program is implemented and executed successfully .

