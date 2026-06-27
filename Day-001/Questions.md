#Q1) Accept two numbers and print the greatest between them.
Input: 14, 7
Output: 14 is greater


code:)
num1 = input("Enter a number1: ")
num2 = input("Enter a number2: ")
if num1 > num2:
    print("Number1 is greater")
elif num2>num1:
    print("Number2 is greater")
else:
    print("Both numbers are equal")

/////////////////////////////////////////////////////////////////////////




#Q2) Accept gender from user and print a greeting message.
Input: M
Output: Good Morning Sir


code:)
gender = (input("Enter your gender:- ")).lower()
if gender == "Male" or gender == "m":
    print("hey sir")
elif gender == "Female" or gender == "f":
    print("Hey madam")
else:
    print("Hey There")
    
/////////////////////////////////////////////////////////////////////////////////////////////////





#Q3) Accept an integer and check if it is even or odd.


code:)
num = int(input("Enter a number: "))
if num%2 == 0:
    print(f"{num} is even") 
else:
    print(f"{num} is odd") 
    
///////////////////////////////////////////////////////////////////////////////////////////////////





#Q4) Accept name and age — check if the user is a valid voter (18+).


code:)
name = input("Enter your name: ")
age = int(input("Enter your age: "))

if age >= 18:
    print(f"{name}, you are eligible to vote.")
else:
    print(f"{name}, you are not eligible to vote.")
    
///////////////////////////////////////////////////////////////////////////////////////////////////////////////




#Q5)Accept a year and check if it is a leap year.
Input: 2024
Output: 2024 is a leap year ✅

code:)
year = int(input("Enter a year: "))
if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
    print(f"{year} is a Leap Year.")
else:
    print(f"{year} is not a Leap Year.")
    
/////////////////////////////////////////////////////////////////////////////////////////////////////////////////





#Q6)Accept temperature in °C and print a description.
Input: -5
Freezing Cold 🥶
Input: 25
Pleasant 😊
Input: 45
Very Hot 🔥



code:)
temp = float(input("Enter the temperature in celsius: "))
if temp == 0:
    print("The temperature is at the freezing point.")
elif temp <= 15:
    print("The temperature is cold.")
elif temp <= 25:
    print("The temperature is moderate.")
elif temp <= 35:
    print("The temperature is warm.")
elif temp <= 45:
    print("The temperature is hot.")
elif temp > 50:
    print("The temperature is very hot.")

///////////////////////////////////////////////////////////////////////////////////////////////////////////////////




#Q7) Print "Hello World" n times.
Input: 3
Hello World × 3 lines


code:)
n = int(input("Enter a number: "))

for i in range(n):
    print("Hello World")

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////


#Q8)Print natural numbers from 1 to n.
Input: 5
1 2 3 4 5


code:)
n = int(input("Enter natural number: "))

for i in range(0,n+1,1):
    print(i)

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////


#Q9)Print natural numbers from 1 to n.
Input: 5
1 2 3 4 5

code:)
n = int(input("Enter a number: "))

for i in range(n,0,-1):
    print(i, end=" ")

////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

#010)Print the multiplication table of a number.
Input: 5
5×1=5, 5×2=10 … 5×10=50

code:)
num = int(input("Enter a number: "))

for i in range(1, 11):
    print(num, "x", i, "=", num * i)
    


























