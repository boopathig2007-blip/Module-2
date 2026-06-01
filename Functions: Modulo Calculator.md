# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
def modulo(a, b):
    return a % b

num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))

result = modulo(num1, num2)

print("Modulo =", result)


## Output
Enter first number: 17
Enter second number: 5
Modulo = 2

## Result
Thus, the Python program that defines a function to accept two values and return their modulo using the % operator was successfully executed and verified.
