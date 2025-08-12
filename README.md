# basicCalculator
#basic calculator program using python
print("This is calculator")

num1 = int(input("Enter num1: "))
num2 = int(input("Enter num2: "))
op = input("Enter the operator(+,-,*,/): ")
add = num1 + num2
minus = num1 - num2
multiple = num1 * num2
divide = num1 / num2

if op == "+":
 print(num1, " + ", num2, " = ", add)
elif op == "-":
 print(num1, " - ", num2, " = ", minus)
elif op == "*":
 print(num1, " * ", num2, " = ", multiple)
elif op == "/":
 print(num1, " / ", num2, " = ", divide)
else:
 print("Wrong operation!")

