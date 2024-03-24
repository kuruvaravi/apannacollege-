# AIM : PYTHON CODE TO FIND FACTORIAL

"""
STEP 1: START
STEP 2: define a function factorial 
STEP 3:let factorial be 1 
STEP 4:if the given number is greater than  1 then
STEP 5:fact will be fact into given number
STEP 6:number will be decremented by 1 and return fact
STEP 7:ENTER A NUMBER
STEP 8: DISPLAY OUTPUT by calling the function
STEP 9: STOP
"""


def factorial(n):
    fact = 1
    while n > 1:
        fact *= n
        n -= 1
    return fact

number=int(input("Enter the given number : "))
result = factorial(number)
print(f"The factorial of {number} is {result}")


# RESULT :  Understood the aim and executed the program.

