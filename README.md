Built-in Functions -Binary Conversion Using Built-in Functions in Python
🎯 Aim
```
To write a Python program to convert the number 16 into its binary representation using built-in Python functions.
```
🧠 Algorithm
```
1.Assign the value 16 to a variable a.
2.Use the built-in bin() function to convert the number to binary.
Print the result.
```
🧾 Program
```
a=16
binary_number= bin(x)
print(binary_number)
```
Output
<img width="827" height="150" alt="530061619-03af072d-3665-4200-b906-6526bd3c686b" src="https://github.com/user-attachments/assets/096b5737-67b9-4980-8e4e-3cb97f02b6c5" />
Result
Thus , the program has been executed succesfully.

Functions in Python: Modulo Calculator
🎯 Aim
```
To write a Python program that defines a function which accepts two values and returns their modulo using the % operator.
```
🧠 Algorithm
```
1.Define a function called result that takes two arguments a and b.
2.Inside the function, compute the modulo using a % b.
3.Print the result of the modulo operation.
4.Get two integer inputs from the user.
5.Call the result function with the user-provided values.
🧾 Program
```def result(a,b):
    mod=a%b
    
    print(f"modulo is {mod}")
a = int(input())
b = int(input())
```
Output
<img width="801" height="247" alt="530061853-d094024e-332f-4cc0-b9b8-41aae82a8250" src="https://github.com/user-attachments/assets/99aeb675-73c7-4078-8670-dfa54c1e0f47" />
Result
Thus , the program has been executed succesfully.

Lambda Function in Python: Addition of Two Numbers
🎯 Aim
```
To write a Python program that defines a lambda function which takes two arguments a and b, and returns their sum.
```
🧠 Algorithm
```
1.Get two integer inputs from the user.
2.Use a lambda function to define a function f that returns a + b.
3.Call the function with the user inputs and print the result.
🧾 Program
```a=int(input())
b=int(input())
f=lambda a,b:a+b
print(f(a,b))
```
Output
<img width="732" height="239" alt="530062156-b4ea5caa-a7e5-4034-85ba-3bf771924961" src="https://github.com/user-attachments/assets/48145b11-3585-41aa-9782-1875f0e1786d" />

Result
Thus , the program has been executed succesfully.

🔺 Looping(Patterns)-Pascal's Triangle Generator in Python
This project demonstrates a simple Python program to generate Pascal’s Triangle, where the number of rows is provided by the user.

🎯 Aim
```
To write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user.
```
🧠 Algorithm
```
1.Start the program.
2.Input the number of rows from the user.
3.Loop from 0 to the number of rows.
4.For each row:
5.Print appropriate spaces to shape the triangle.
6.Compute values using the formula:
[ C(n, k) = \frac{n!}{k!(n-k)!} ]
7.Print all rows of Pascal’s Triangle.
End the program.
```
🧪 Program
```
n = int(input())
for i in range(1,n+1):
    c=1
    for j in range(1,i+1):
        print(c,end=' ')
        c = c*(i-j)//j
    print()
```
Sample Output
<img width="909" height="533" alt="530062368-e49290a3-fadd-4711-95d8-ff14354c97f8" src="https://github.com/user-attachments/assets/55f89588-1a1b-4ec9-9302-ef4a95d71a69" />


Result
Thus , the program has been executed succesfully.

Loops in Python: Palindrome Number Checker
🎯 Aim
```
To write a Python program that checks whether a given number is a palindrome using loops.
```
🧠 Algorithm
```
1.Get input from the user and assign it to a variable num.
2.Assign the value of num to a temporary variable temp.
3.Initialize a variable rev to 0 (used to store the reversed number).
4.Use a while loop to reverse the digits:
5.While temp > 0:
rev = (10 * rev) + temp % 10
temp = temp // 10
6.After the loop, compare rev with num:
If equal, print that the number is a palindrome.
Else, print that it is not a palindrome.
```
🧾 Program
```
num=int(input())
rev=0
temp=num
while temp>0:
    rev=(10*rev)+temp%10
    temp//=10
if rev==num:
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))
```
Output
<img width="1049" height="194" alt="530062989-85510c64-8d12-4a06-aa02-8f9b8413145a" src="https://github.com/user-attachments/assets/9cec3e82-b7bb-4127-8ad0-b5fe57b7d951" />


Result
Thus , the program has been executed succesfully.
