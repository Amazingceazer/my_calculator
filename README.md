#A simple calculation app

#1. ADDITION 
#2. SUBSTRACTION
#3. MULTIPLICATION
#4. DIVISION

print("enter two numbers to add")
first_number = input("first number:")
second_number= input("second number:")
sum = float(first_number) + float(second_number)
print(f"{first_number} + {second_number} = {sum:.2f}")


print("Enter two numbers to sub")
firstnumber = input("first number:")
secondnumber = input("second number:")
sub = float(firstnumber) - float(secondnumber)
print(f"{firstnumber} - {secondnumber} = {sub:.2f}")

print("Enter two numbers to mul")
firstnumber = input("first number:")
secondnumber = input("second number:")
mul = float(firstnumber) * float(secondnumber)
print(f"{firstnumber} * {secondnumber} = {mul:.2f}") 

print("Enter two numbers to div")
firstnumber = input("first number:")
secondnumber = input("second number:")
div = float(firstnumber) / float(secondnumber)
print(f"{firstnumber} / {secondnumber} = {div:.2f}")
 
print("Enter two numbers to exp")
firstnumber = input("first number:")
secondnumber = input("second number:")
exp = float(firstnumber) ** float(secondnumber)
print(f"{firstnumber} ** {secondnumber} = {exp:.2f}")
 
 
print("Enter two numbers to flo")
firstnumber = input("firstnumber:")
secondnumber = input("secondnumber:")
flo = float(firstnumber) // float(secondnumber)
print(f"{firstnumber} // {secondnumber} = {flo:.2f}") 

