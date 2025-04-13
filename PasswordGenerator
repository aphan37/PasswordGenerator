import random
import string

# Base character set
chars = string.ascii_lowercase
if use_uppercase:
    chars += string.ascii_uppercase
if use_digits:
    chars += string.digits
if use_symbols:
    chars += string.punctuation

if not chars:
    raise ValueError("No character types selected!")

# Ask the user for inputs
  num_passwords = int(input("How many passwords do you want to generate? "))
  password_length = int(input("Enter the desired password length: "))

  use_uppercase = input("Include uppercase letters? (y/n): ").lower() == 'y'
  use_digits = input("Include numbers? (y/n): ").lower() == 'y'
  use_symbols = input("Include symbols? (y/n): ").lower() == 'y'

  print("\nHere are your generated password\n")
  for i in range(num_passwords):
      pwd = generate_password(password_length, use_uppercase, use_digits, use_symbols)
      print(f"{i+1}: {pwd}")

