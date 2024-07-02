
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

Python is a popular programming language known for its ease of use, readability, and efficiency. It's interpreted, object-oriented, high-level, and ideal for beginners due to its simple syntax. Key features include:

Easy to read and understand
Interpreted language
Object-oriented
Free and open-source
Versatile and extensible
Multi-platform compatibility
Extensive libraries and frameworks
GUI support
Dynamically typed
Large, active community
Applications of Python
Web Development: Python is favored for web development due to its robust frameworks like Django (backend) and Flask (frontend), which enable developers to create dynamic, scalable, and efficient websites.

Data Science: Python allows data scientists to build powerful AI models and algorithms, extracting patterns from data to aid organizational decision-making and investment strategies.

Web Scraping and Automation: Python's libraries like BeautifulSoup, pandas, and matplotlib facilitate web scraping and automation, helping businesses analyze data, improve customer support with AI bots, and enhance market strategies through data organization and pattern recognition.

GeeksforGeeks. (2023). What is Python? [online] Available at: https://www.geeksforgeeks.org/what-is-python/.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

How to install Python on Windows
Follow these steps to get Python up and running on your Windows machine:

Download the Python installer
Run the installer
Customize the installation (optional)
Install Python
Verify the installation
Alternate installation via Microsoft Store
Step 1: Download the Python installer
Visit the official Python website and download the latest version of Python 3.x for Windows. The website will automatically detect your operating system and offer the appropriate installer for your system (32-bit or 64-bit).

Downloading Python from the official website.
Downloading Python from the official website.
Step 2: Run the installer
Locate the downloaded installer file (usually in your Downloads folder) and double-click on it to run the installation process. You may be prompted by the User Account Control (UAC) to allow the installation. Click Yes to proceed.

Step 3: Customize the installation (optional)
On the installer’s welcome screen, you’ll see two options: Install Now and Customize installation.

If you want to install Python with the default settings, simply click Install Now.

Python installer for Windows
Python installer for Windows
Important
We highly recommend checking the box next to “Add Python 3.x to PATH” before proceeding with the installation. This will ensure that Python is added to your system’s PATH variable, making it easier to run Python from the command prompt.

If you want to customize the installation (changing the installation directory or selecting specific components, for instance), click Customize installation. You should see the following:

Optional features in the Python for Windows installer.
Optional features in the Python for Windows installer.
Pick and choose what you’d like to be installed alongside the base installation. Your options include:

Documentation — This includes the Python documentation file with the installation.
pip — This option installs pip, which allows you to install other Python packages as you’d like.
tcl/tk and IDLE — This option installs tkinter and IDLE.
Python test suite – Selecting this option installs the standard library test suite, which is useful for testing your output.
py launcher; for all users — These two options make it so you can launch Python from the command line
When you’re done making your selections, click Next.

You’ll be then taken to a new dialog box that offers advanced options:

Advanced options in the Windows Python installer.
Advanced options in the Windows Python installer.
Again, you’re presented with a number of options to choose from, including:

Install Python 3.11 for all users
Associate files with Python (requires the ‘py’ launcher)
Create shortcuts for installed applications
Add Python to environment variables
Precompile standard library
Download debugging symbols
Download debug binaries (requires VS 2017 or later)
Verify that the installation directory chosen is correct and then you’re reading to install.

Step 4: Install Python
After selecting your desired installation settings, click Install to begin the installation process. The installer will copy the necessary files to your computer and set up Python. This process may take a few minutes.

Step 5: Verify the installation
Once the installation is complete, you can verify that Python has been installed correctly by opening the Command Prompt (search for “cmd” in the Start menu) and typing the following command:

python --version
Press Enter, and you should see the version of Python you installed displayed in the output. This confirms that Python has been successfully installed on your computer.

Alternate installation via Microsoft store
As an alternative to downloading the Python installer from the official website, you can also install Python on Windows using the Microsoft Store. This method ensures you get the latest version of Python and allows for easy updates.

To install Python in this fashion, you’ll need to:

Open the Microsoft Store — Search for “Microsoft Store” in the Start menu and click on the app to open it.
Search for Python — In the Microsoft Store, use the search bar in the upper-right corner to search for “Python.” You should see the latest version of Python 3.11 listed in the search results.
Install Python — Click on the Python 3.11 listing, and then click the Install button on the Python app page. The Microsoft Store will download and install Python on your Windows computer

Kinsta®. (2023). How To Install Python on Windows, macOS, and Linux. [online] Available at: https://kinsta.com/knowledgebase/install-python/.

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

Python program that prints "Hello, World!" to the console:

python
Copy code
print("Hello, World!")
Explanation of Basic Syntax Elements
print function:

The print function is a built-in function in Python used to output text or other data to the console.
In this case, it outputs the string "Hello, World!".
Parentheses ():

In Python, functions are called using parentheses. The parentheses are used to enclose the arguments that you want to pass to the function.
Here, "Hello, World!" is the argument passed to the print function.
String "Hello, World!":

Strings in Python are sequences of characters enclosed in either single quotes (') or double quotes (").
The text "Hello, World!" is a string literal that will be printed to the console.
Additional Notes
Python programs are typically written in text files with a .py extension, and you can run them using a Python interpreter by typing python filename.py in the command line.
Python uses indentation to define blocks of code. For this simple example, indentation is not necessary, but it becomes crucial when writing more complex programs with multiple lines of code and control structures like loops and conditionals.
This basic program demonstrates the simplicity and readability of Python syntax, making it a great language for beginners.

OpenAI. (2024). ChatGPT [Large language model]. https://chatgpt.com

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

Basic Data Types in Python
Integers (int):

Whole numbers without a decimal point.
Example: 5, -3, 100
Floating-Point Numbers (float):

Numbers with a decimal point.
Example: 3.14, -0.001, 2.0
Strings (str):

Sequences of characters enclosed in single (') or double (") quotes.
Example: "Hello, World!", 'Python'
Booleans (bool):

Represents True or False values.
Example: True, False
Lists (list):

Ordered collections of items, which can be of different types, enclosed in square brackets ([]).
Example: [1, 2, 3], ['apple', 'banana', 'cherry']
Tuples (tuple):

Ordered collections of items, which can be of different types, enclosed in parentheses (()), and are immutable.
Example: (1, 2, 3), ('apple', 'banana', 'cherry')
Dictionaries (dict):

Unordered collections of key-value pairs, enclosed in curly braces ({}).
Example: {'name': 'Alice', 'age': 25}
Sets (set):

Unordered collections of unique items, enclosed in curly braces ({}).
Example: {1, 2, 3}, {'apple', 'banana', 'cherry'}
Short Script Demonstrating Variables of Different Data Types
python
Copy code
# Integer
my_int = 10
print("Integer:", my_int)

# Float
my_float = 3.14
print("Float:", my_float)

# String
my_str = "Hello, World!"
print("String:", my_str)

# Boolean
my_bool = True
print("Boolean:", my_bool)

# List
my_list = [1, 2, 3, 'apple', 'banana']
print("List:", my_list)

# Tuple
my_tuple = (1, 2, 3, 'apple', 'banana')
print("Tuple:", my_tuple)

# Dictionary
my_dict = {'name': 'Alice', 'age': 25}
print("Dictionary:", my_dict)

# Set
my_set = {1, 2, 3, 'apple', 'banana'}
print("Set:", my_set)
Explanation of the Script
Variables: Variables are used to store data. In Python, you do not need to declare the type of a variable; it is determined automatically based on the value assigned.
Printing: The print function is used to output the value of variables to the console.
Creating Variables: Each variable is assigned a value of a different data type, demonstrating the basic data types in Python.

OpenAI. (2024). ChatGPT [Large language model]. https://chatgpt.com

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

Using else conditional statement with for loop in python

In most of the programming languages (C/C++, Java, etc), the use of else statement has been restricted with the if conditional statements. But Python also allows us to use the else condition with for loops.
 

The else block just after for/while is executed only when the loop is NOT terminated by a break statement.

Else block is executed in below Python 3.x program: 

Python
for i in range(1, 4): 
    print(i) 
else:  # Executed because no break in for 
    print("No Break") 
Output : 

1
2
3
No Break
Else block is NOT executed in Python 3.x or below: 

Python
for i in range(1, 4): 
    print(i) 
    break
else: # Not executed as there is a break 
    print("No Break") 
Output : 

1
Such type of else is useful only if there is an if condition present inside the loop which somehow depends on the loop variable.
In the following example, the else statement will only be executed if no element of the array is even, i.e. if statement has not been executed for any iteration. Therefore for the array [1, 9, 8] the if is executed in the third iteration of the loop and hence the else present after the for loop is ignored. In the case of array [1, 3, 5] the if is not executed for any iteration and hence the else after the loop is executed.

Python
# Python 3.x program to check if an array consists  
# of even number 
def contains_even_number(l): 
    for ele in l: 
        if ele % 2 == 0: 
            print ("list contains an even number") 
            break
  
    # This else executes only if break is NEVER 
    # reached and loop terminated after all iterations. 
    else:      
        print ("list does not contain an even number") 
  
# Driver code 
print ("For List 1:") 
contains_even_number([1, 9, 8]) 
print (" \nFor List 2:") 
contains_even_number([1, 3, 5]) 
Output: 

For List 1:
list contains an even number

For List 2:
list does not contain an even number
As an exercise, predict the output of the following program. 

Python
count = 0
while (count < 1):     
    count = count+1
    print(count) 
    break
else: 
    print("No Break") 

    GeeksforGeeks. (2017). Using Else Conditional Statement With For loop in Python. [online] Available at: https://www.geeksforgeeks.org/using-else-conditional-statement-with-for-loop-in-python/.

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.


Functions in Python
Functions are reusable blocks of code designed to perform a specific task. They help in organizing code, making it more readable, and reducing redundancy by allowing code reuse. Functions can take inputs (arguments), process them, and return an output.

Benefits of Using Functions:
Code Reusability: Functions allow you to write code once and use it multiple times.
Modularity: Functions enable you to break down complex problems into smaller, manageable chunks.
Readability: Well-named functions make your code easier to understand.
Maintainability: Functions make your code easier to update and maintain.
Defining and Using a Function
Here’s a Python function that takes two arguments and returns their sum:

python
Copy code
def add_numbers(a, b):
    """
    This function takes two arguments and returns their sum.
    """
    return a + b
Example of How to Call This Function:
python
Copy code
# Call the function with two arguments
result = add_numbers(3, 5)

# Print the result
print("The sum is:", result)
Explanation:
Function Definition:

def: This keyword is used to define a function.
add_numbers: The name of the function. Function names should be descriptive.
(a, b): These are the parameters. The function accepts two arguments, a and b.
:: This colon indicates the start of the function body.
Docstring:

The triple quotes (""") define a docstring, which is a string literal used to document the function. It describes what the function does.
Return Statement:

return a + b: This statement returns the sum of the two arguments. The return keyword exits the function and provides the result to the caller.
Function Call:

result = add_numbers(3, 5): This calls the add_numbers function with arguments 3 and 5. The result is stored in the variable result.
Printing the Result:

print("The sum is:", result): This prints the result to the console.

OpenAI. (2024). ChatGPT [Large language model]. https://chatgpt.com
"Python Functions". W3Schools. https://www.w3schools.com/python/python_functions.asp

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

Differences between Lists and Dictionaries in Python
Order and Indexing:

List: An ordered collection of elements that can be accessed using an index. Lists maintain the order of elements as they were inserted.
Dictionary: A collection of key-value pairs where each key is unique. The order of elements is based on insertion order (since Python 3.7).
Mutability:

List: Mutable, meaning elements can be changed, added, or removed.
Dictionary: Also mutable, allowing changes to values, addition, or removal of key-value pairs.
Access Time:

List: Accessing elements by index is fast (O(1) time complexity).
Dictionary: Accessing elements by key is very fast, generally O(1) due to the underlying hash table implementation.
Usage:

List: Suitable for collections of items that are ordered and accessed by position.
Dictionary: Suitable for collections of items that are accessed by a unique key, allowing for fast lookups.
Now, let's create a script that demonstrates these differences by performing basic operations on a list and a dictionary.

Python Script
python
Copy code
# Creating a list of numbers
numbers_list = [1, 2, 3, 4, 5]

# Creating a dictionary with key-value pairs
person_dict = {
    'name': 'Alice',
    'age': 30,
    'city': 'New York'
}

# Demonstrating basic operations on the list
print("Original list:", numbers_list)

# Adding an element to the list
numbers_list.append(6)
print("List after appending 6:", numbers_list)

# Removing an element from the list
numbers_list.remove(3)
print("List after removing 3:", numbers_list)

# Accessing an element by index
second_element = numbers_list[1]
print("Second element in the list:", second_element)

# Demonstrating basic operations on the dictionary
print("Original dictionary:", person_dict)

# Adding a new key-value pair to the dictionary
person_dict['occupation'] = 'Engineer'
print("Dictionary after adding occupation:", person_dict)

# Removing a key-value pair from the dictionary
del person_dict['city']
print("Dictionary after removing city:", person_dict)

# Accessing a value by key
name = person_dict['name']
print("Name from dictionary:", name)
Explanation of the Script
List Operations:

append(6): Adds the number 6 to the end of the list.
remove(3): Removes the first occurrence of the number 3 from the list.
Accessing an element by index: Retrieves the second element (index 1) from the list.
Dictionary Operations:

Adding a new key-value pair: Adds the key occupation with the value 'Engineer'.
Removing a key-value pair: Deletes the key city and its associated value.
Accessing a value by key: Retrieves the value associated with the key name.
By running this script, you can observe the differences in how lists and dictionaries are manipulated and accessed in Python

OpenAI. (2024). ChatGPT [Large language model]. https://chatgpt.com 
W3Schools: Python Lists

W3Schools, 2023. Python Lists. Available at: https://www.w3schools.com/python/python_lists.asp [Accessed 2 July 2024].
W3Schools: Python Dictionaries

W3Schools, 2023. Python Dictionaries. Available at: https://www.w3schools.com/python/python_dictionaries.asp [Accessed 2 July 2024].

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

Exception handling in Python is a mechanism to handle runtime errors, ensuring the flow of the program doesn't break abruptly due to unexpected issues. It allows you to catch and manage errors using try, except, and finally blocks.

Here's a basic explanation of each:

try block: This block contains the code that might raise an exception.
except block: This block contains the code that executes if an exception occurs in the try block. You can specify different types of exceptions to handle specific errors.
finally block: This block contains code that executes no matter what, whether an exception occurred or not. It's typically used for cleanup actions.
Example
Let's look at a simple example that demonstrates the usage of try, except, and finally blocks:

python
Copy code
def divide_numbers(a, b):
    try:
        # Try to perform the division
        result = a / b
    except ZeroDivisionError as e:
        # Handle the case where division by zero is attempted
        print(f"Error: {e}. Division by zero is not allowed.")
    except TypeError as e:
        # Handle the case where the inputs are not numbers
        print(f"Error: {e}. Please provide numbers for division.")
    else:
        # If no exception occurs, print the result
        print(f"The result of division is: {result}")
    finally:
        # This block will always execute
        print("Execution of the try-except block is complete.")

# Example usage
divide_numbers(10, 2)  # Normal case
divide_numbers(10, 0)  # Division by zero
divide_numbers(10, 'a')  # Invalid type
Explanation
First call divide_numbers(10, 2):

The try block successfully executes result = a / b.
No exception is raised, so the except blocks are skipped.
The else block prints the result.
The finally block prints the completion message.
Second call divide_numbers(10, 0):

The try block raises a ZeroDivisionError.
The corresponding except block catches the error and prints a message.
The finally block prints the completion message.
Third call divide_numbers(10, 'a'):

The try block raises a TypeError because 'a' is not a number.
The corresponding except block catches the error and prints a message.
The finally block prints the completion message.
This example demonstrates how exception handling in Python can gracefully manage errors and ensure the program continues to run without crashing.

OpenAI. (2024). ChatGPT [Large language model]. https://chatgpt.com


9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

Modules in Python are files containing Python code, which can define functions, classes, and variables. A package is a collection of modules. This allows for better organization and reusability of code.

Importing and Using a Module
To import a module in Python, you can use the import keyword followed by the module name. Once imported, you can use the functions, classes, and variables defined in the module using dot notation.

Example using the math module:

import math
print(math.sqrt(16))  # Output: 4.0
In this example, the math module is imported, and the sqrt function from the math module is used to calculate the square root of 16.

Studocu. (2023). [Solved] Explain the concepts of modules and packages in Python How can - Information Systems (INFO1000) - Studocu. [online] Available at: https://www.studocu.com/en-za/messages/question/7983112/explain-the-concepts-of-modules-and-packages-in-python-how-can-you-import-and-use-a-module-in-your [Accessed 2 Jul. 2024].

‌
10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

Writing to a file in Python
There are two ways to write in a file:

Using write()
Using writelines()
Writing to a Python Text File Using write()

write() : Inserts the string str1 in a single line in the text file.

File_object.write(str1)
Writing to a Text File Using writelines()

writelines() : For a list of string elements, each string is inserted in the text file.Used to insert multiple strings at a single time.

File_object.writelines(L) for L = [str1, str2, str3]
Reference: write() VS writelines()

Reading from a file in Python
There are three ways to read data from a text file:

Using read()
Using readline()
Using readlines()
Reading From a File Using read()

read() : Returns the read bytes in form of a string. Reads n bytes, if no n specified, reads the entire file.

File_object.read([n])
Reading a Text File Using readline()

readline() : Reads a line of the file and returns in form of a string.For specified n, reads at most n bytes. However, does not reads more than one line, even if n exceeds the length of the line.

File_object.readline([n])
Reading a File Using readlines()

readlines() : Reads all the lines and return them as each line a string element in a list.

  File_object.readlines()
Note: ‘\n’ is treated as a special character of two bytes.

In this example, a file named “myfile.txt” is created and opened in write mode ( "w" ). Data is written to the file using write and writelines methods. The file is then reopened in read and append mode ( "r+" ). Various read operations, including read , readline , readlines , and the use of seek , demonstrate different ways to retrieve data from the file. Finally, the file is closed.


# Program to show various ways to read and
# write data in a file.
file1 = open("myfile.txt", "w")
L = ["This is Delhi \n", "This is Paris \n", "This is London \n"]

# \n is placed to indicate EOL (End of Line)
file1.write("Hello \n")
file1.writelines(L)
file1.close()  # to change file access modes

file1 = open("myfile.txt", "r+")

print("Output of Read function is ")
print(file1.read())
print()

# seek(n) takes the file handle to the nth
# byte from the beginning.
file1.seek(0)

print("Output of Readline function is ")
print(file1.readline())
print()

file1.seek(0)

# To show difference between read and readline
print("Output of Read(9) function is ")
print(file1.read(9))
print()

file1.seek(0)

print("Output of Readline(9) function is ")
print(file1.readline(9))

file1.seek(0)
# readlines function
print("Output of Readlines function is ")
print(file1.readlines())
print()
file1.close()
Output:

Output of Read function is 
Hello 
This is Delhi 
This is Paris 
This is London 
Output of Readline function is 
Hello 
Output of Read(9) function is 
Hello 
Th
Output of Readline(9) function is 
Hello 
Output of Readlines function is 
['Hello \n', 'This is Delhi \n', 'This is Paris \n', 'This is London \n']

GeeksforGeeks. (2017). Reading and Writing to text files in Python - GeeksforGeeks. [online] Available at: https://www.geeksforgeeks.org/reading-writing-text-files-python/.

‌
# Submission Guidelines:
-

