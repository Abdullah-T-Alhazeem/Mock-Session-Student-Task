# Beginner Task: Competition Eligibility Checker

# Ask for user's name and age
name = input("What is your name? ")
age = int(input("How old are you? "))

# Greet the user
print(f"Hello {name}!")

# Check eligibility
if age >= 18:
    print("Hooooraaaay!! You're eligible to enter the competition!")
else:
    print("you must be at least 18 to enter. Try Again Later")
