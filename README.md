# 10.-Python-Uses-of-input-in-Python
The input() function in Python is used to take user input from the keyboard. The input is returned as a string, so it can be processed or converted to other data types as needed.  Below are various use cases for input() in Python:
# README: Python `input()` Function Examples

| **S.No** | **Use Case**                          | **Code Example**                                                                                 | **Explanation**                                                                                 |
|----------|---------------------------------------|-------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| 1        | Basic Input                          | `name = input("What is your name? ")` <br> `print(f"Hello, {name}!")`                           | Takes a user's name and displays a greeting message.                                           |
| 2        | Arithmetic Operations                | `num1 = input("Enter first number: ")` <br> `num2 = input("Enter second number: ")`             | Takes two numbers as input, converts to integers, and calculates their sum.                   |
| 3        | Type Conversion                      | `age = int(input("Enter your age: "))` <br> `print(f"You will be {age + 1} next year.")`        | Converts input to an integer for arithmetic operations.                                        |
| 4        | Input Validation                     | `while True:` <br> `if input("Enter 'yes' to proceed: ").lower() == 'yes': break`              | Repeats input prompt until the user enters "yes".                                              |
| 5        | Default Values                       | `value = input("Enter a value: ") or "default"`                                                 | Uses a default value if no input is provided.                                                  |
| 6        | Multiple Values                      | `values = input("Enter numbers: ").split()` <br> `numbers = [int(v) for v in values]`          | Accepts multiple values separated by space and converts them into a list of integers.          |
| 7        | Password Masking                     | `from getpass import getpass` <br> `password = getpass("Enter password: ")`                     | Hides input for sensitive data like passwords.                                                 |
| 8        | Multi-line Input                     | `lines = []` <br> `while True:` <br> `line = input(); if line == 'STOP': break`                | Reads multiple lines of input until the user types "STOP".                                     |
| 9        | Decision-Making Input                | `choice = input("Continue (yes/no)? ")`                                                        | Uses input for decision-making.                                                               |

Feel free to use these examples to explore the versatility of the `input()` function!
