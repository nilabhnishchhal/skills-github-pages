---
title: Beginners Python Blog
---

## Basic Python Syntax

Welcome to the world of Python programming! In this chapter, we'll embark on a journey to explore the basics of Python syntax. Python, known for its simplicity and readability, is a great language to start your programming adventure. Let's dive in and learn through a story - the tale of Alice in DataLand.

### Basics of a Python Script

In DataLand, everything starts with a script. A Python script is like a recipe that tells your computer what to do. Each line of the script is an instruction, a step in the recipe, that the Python interpreter reads and executes.

```python
# This is a simple Python script
print("Hello, DataLand!")

# Now let us is another simple script, which Calculates the area of a Triangle
# If you run this script as it is, python may hiss at you (in form of some errors)
# This will be more clear in the end of the section about variables

area = 0.5 * base * height
```
The script (also called codes sometimes) in Python are read and executed from top to bottom, in an orderly fashion. The output of earlier script can be used in the upcoming lines. In the example above, we saw a simple script used to print text of our choice on the screen. We will write many more going forward.

Before we move forward, two very important points about Pyhton-
1. Python is case sensitive. Therefore, `print()` and `PRINT()` are different, so is `Print()`.
1. Python is cute 😊. You are going to love it. 

### Variables: Holding Data

Alice starts her day in DataLand by collecting data. In Python, we store data in containers called variables.

```python
name = "Alice"
age = 10
height = 4.5
```

Here, `name` holds a string "Alice", `age` holds an integer 10, and `height` holds a float 4.5.
You can call a variable by its name, and the value it holds will come as the output. We will use variables to do operations on them, and they will behave exactly as the value they hold. 
example: 
```python
# Guess the output for_fun
for_fun = age + height
```
Now call the variable, for_fun, and see what value it returns. Ohh, I forgot to tell you how to call a variable. Just write its name and run the code. 

The variables are sensitive creatures. Particularly they are very touchy about their names. Therefore, there are few very important points you must be careful about, when you name a variable. Here's a summary of these rules:

#### Rules for Naming Variables in Python

1. **Alphanumeric and Underscore**: Variable names must consist of letters (a-z, A-Z), digits (0-9), or underscores (_). However, they cannot start with a digit.

2. **Case Sensitivity**: Variable names are case-sensitive. This means that `myVariable`, `myvariable`, and `MyVariable` are all considered different variables in Python.

3. **No Reserved Words**: Variable names cannot be the same as reserved words (also known as keywords) in Python. Reserved words are those that have a special meaning in Python syntax (e.g., `if`, `for`, `while`, `class`, `import`, `return`, `def`, `try`, etc.).

4. **No Special Characters**: Apart from the underscore, any other special characters (like @, #, %, &, etc.) are not allowed in variable names.

5. **Not Starting with an Underscore (Convention)**: While it's allowed, it's a convention not to start a variable name with an underscore, as these are often used for specific purposes (like indicating a variable is for internal use, or for naming methods in classes).

#### Best Practices and Conventions

Beyond these rules, there are also some best practices and naming conventions in Python:

- **Descriptive Names**: Choose meaningful and descriptive names for variables. For example, `price` is better than `p`, and `user_age` is better than `ua`.

- **Snake Case for Variables**: Python community prefers snake_case for variable names where words are lowercase and separated by underscores, e.g., `my_variable`.

- **Avoid Using Single Character**: Except for certain cases like loop indices or lambda functions, avoid using single characters like `x`, `y`, `i`.

- **Constants**: By convention, constants are defined using uppercase letters with underscores separating words, e.g., `MAX_SIZE`.

Following these rules and conventions ensures that your Python code is more readable, maintainable, and less prone to errors.
Now when we have learnt all about the variables in Python, let us go back to calculating the Area of Triangle. 

To write a simple script to calculate the area of a triangle, you can use the formula:

$ \text{Area} = \frac{1}{2} \times \text{base} \times \text{height} $

Here is a Python script that prompts the user to enter the base and height of the triangle and then calculates and prints the area:

```python
# Python script to calculate the area of a triangle

# Input base and height of the triangle
base = float(input("Enter the base of the triangle: "))
height = float(input("Enter the height of the triangle: "))

# Calculate the area
area = 0.5 * base * height

# Display the area
print(f"The area of the triangle is {area}")
```

This script works as follows:
1. It asks the user to input the base and height of the triangle.
2. The inputs are converted to `float` to handle decimal values.
3. The area is calculated using the formula.
4. Finally, it prints out the area of the triangle.

In the scripts or rather along with the scripts, we used some instructions and clarifications which started very conspicuously with a `#`. These are called `comments` in Python. Let us understand what is that now. 

### Comments: Notes to Self

As Alice collects data, she takes notes. In Python, we write notes using comments. Comments start with a `#` and are ignored by Python. They're for humans, not machines.

```python
# This is a comment
# Python will ignore this
```
Therefore, whenever you want to write something which you want only humans to read (and therefore not being executed by the python interpreter), write them as comments. Going forward, you will notice many statements will be written which start with `#`. These are to make the code more readable and easy to understand. These lines will be ignored by the python interpreter. 

