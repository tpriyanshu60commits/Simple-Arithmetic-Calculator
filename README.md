# Simple-Arithmetic-Calculator

operator = input("enter the operator(+,-,*,/)")
num1= int(input("enter the first number - "))
num2 = int(input("enter the second number - "))

if operator == "+":
    print(num1+num2)
elif operator == "-":
    print(num1-num2)
elif operator == "*":
    print(num1*num)
elif operator == "/":
    print(num1/num2)
else:
    print(f"{operator} is not a valid input")
