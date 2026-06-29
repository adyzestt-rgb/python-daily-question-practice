#@1)Accept a number and print its reverse.
Input: 12345
54321

code:)
num = int(input("Enter a number: "))

reverse = 0

while num > 0:
    digit = num % 10
    reverse = reverse * 10 + digit
    num = num // 10

print(reverse)

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

#@2) Check if a number is palindromic (equal to its reverse). Input: 121 Palindrome ✅ Input: 123 Not Palindrome ❌

Code:)
num = int(input("Enter a number: "))

original = num
reverse = 0

while num > 0:
    digit = num % 10
    reverse = reverse * 10 + digit
    num = num // 10

if original == reverse:
    print("Palindrome ✅")
else:
    print("Not Palindrome ❌")


////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

#@3)Build a number guessing game — computer picks a random number, user keeps guessing until correct. Guess: 50 → Too low! Guess: 75 → Too high! Guess: 63 → 🎉 Correct!

code:)

import random

number = random.randint(1, 100)

while True:
    guess = int(input("Guess the number (1-100): "))

    if guess < number:
        print("Too low!")
    elif guess > number:
        print("Too high!")
    else:
        print("🎉 Correct!")
        break

#@4) 










        
