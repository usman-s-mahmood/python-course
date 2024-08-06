# Chapter 1: Introduction To Programming

### What is programming:

Programming is a standard way of communication between Humans and Computers. Programming languages are used for the purpose of programming a computer for performing specific tasks.

### Programming Languages:

Set of commands, symbols, words and syntax (rules) used to write computer programs is called programming language. These languages are used to write well defined set of instructions called computer programms

### Types of programming languages:

There are 2 main categories of programming languages:
**1. High Level Programming Languages**

These languages are easy to understand for the developer and have syntax that resembles to english languages. Due to there ease, these languages are also called User Oriented Languages. Some examples include: python, c/c++, java, go, R, kotlin, dart, javascript, etc.

**2. Low Level Programming Languages**

These languages are complex to understand for the developer due to there strict set of instructions that is lengthy to implement but these languages are directly understandable by machines. These languages are faster then high level languages. Examples include Binary and Assembly Language

### How does high level programming work

Code written in high level languages is converted to low level languages with the standard compiler or interpreter of respective language and the low level code (Binary) is executed directly on the computer hardware

**Compiler converts all the code into binary instructions at a time. It also creates an executable file that can be executed any number of times without compiling the program again. Compiled languages are faster than interpreted languages**

**Interpreter converts each line of code one by one into binary instruction that makes the process slow. Interpreter does not provide any executable file so programs written in languages that use interpreter require to be converted into binary every time that slows down the process.**

python uses interpreter for converting it's code from high level syntax to machine code

### Introduction to python

Python is a high level interpreted programming language that was developed by Guido Van Rossum in the year 1991. Python was developed as a general purpose programming language. It has a very easy syntax and it is best for those learners who are new to programming. Due to the simplicity of python, it is now widely used in areas of machine learning, data science, deep learning, natural language processing, Artificial Intelligence, web development, cyber security, cross platform application development etc.


<hr>


```
Raw notes: Certainly! I'll expand your notes by adding sections on the print statement, escape sequences, variables, and operators in Python. Here’s the updated markdown code:

```markdown
# Chapter 1: Introduction To Programming

### What is programming:

Programming is a standard way of communication between humans and computers. Programming languages are used for the purpose of programming a computer to perform specific tasks.

### Programming Languages:

A programming language is a set of commands, symbols, words, and syntax (rules) used to write computer programs. These languages are used to write well-defined sets of instructions called computer programs.

### Types of programming languages:

There are 2 main categories of programming languages:

**1. High-Level Programming Languages**

These languages are easy to understand for the developer and have syntax that resembles English language. Due to their ease, these languages are also called User-Oriented Languages. Some examples include Python, C/C++, Java, Go, R, Kotlin, Dart, JavaScript, etc.

**2. Low-Level Programming Languages**

These languages are complex to understand for the developer due to their strict set of instructions that are lengthy to implement. However, these languages are directly understandable by machines and are faster than high-level languages. Examples include Binary and Assembly Language.

### How does high-level programming work

Code written in high-level languages is converted to low-level languages with the standard compiler or interpreter of the respective language. The low-level code (Binary) is executed directly on the computer hardware.

**Compiler**: Converts all the code into binary instructions at once. It also creates an executable file that can be executed any number of times without compiling the program again. Compiled languages are generally faster than interpreted languages.

**Interpreter**: Converts each line of code one by one into binary instructions, which makes the process slower. An interpreter does not provide any executable file, so programs written in languages that use an interpreter require conversion into binary every time, which slows down the process.

Python uses an interpreter for converting its code from high-level syntax to machine code.

### Introduction to Python

Python is a high-level interpreted programming language that was developed by Guido van Rossum in 1991. Python was developed as a general-purpose programming language. It has a very easy syntax, making it ideal for beginners. Due to the simplicity of Python, it is now widely used in areas such as machine learning, data science, deep learning, natural language processing, artificial intelligence, web development, cybersecurity, and cross-platform application development.

### Print Statement

In Python, the `print()` function is used to display output to the user. It can print strings, numbers, and variables. Here’s a basic example:

```python
print("Hello, World!")
```

You can also print multiple items by separating them with commas:

```python
name = "Alice"
age = 30
print("Name:", name, "Age:", age)
```

For more formatted output, you can use formatted strings (f-strings):

```python
name = "Bob"
age = 25
print(f"Name: {name}, Age: {age}")
```

### Escape Sequences

Escape sequences in Python are used to include special characters in strings. They start with a backslash (`\`). Here are some common escape sequences:

- `\n` - Newline: Moves the cursor to the next line.
- `\t` - Tab: Inserts a horizontal tab space.
- `\\` - Backslash: Inserts a backslash character.
- `\"` - Double Quote: Inserts a double quote character inside a string delimited by double quotes.
- `\'` - Single Quote: Inserts a single quote character inside a string delimited by single quotes.

Example usage:

```python
print("Hello\tWorld")    # Output: Hello    World
print("Line 1\nLine 2")  # Output: Line 1
                         #         Line 2
print("A backslash: \\") # Output: A backslash: \
print("He said, \"Hello!\"") # Output: He said, "Hello!"
```

### Variables

Variables are used to store data values. In Python, you don't need to declare the type of a variable explicitly; Python infers it automatically. Variables are created by assigning a value using the `=` operator.

Examples:

```python
x = 10          # Integer
y = 3.14        # Float
name = "Alice"  # String
is_active = True # Boolean
```

You can also reassign variables to new values:

```python
x = 10
x = x + 5  # x is now 15
```

### Operators

Operators are symbols that perform operations on variables and values. Python includes several types of operators:

#### Arithmetic Operators

- `+` : Addition
- `-` : Subtraction
- `*` : Multiplication
- `/` : Division
- `//` : Floor Division
- `%` : Modulus (Remainder)
- `**` : Exponentiation

Examples:

```python
a = 5
b = 2
print(a + b)  # Output: 7
print(a - b)  # Output: 3
print(a * b)  # Output: 10
print(a / b)  # Output: 2.5
print(a // b) # Output: 2
print(a % b)  # Output: 1
print(a ** b) # Output: 25
```

#### Comparison Operators

- `==` : Equal to
- `!=` : Not equal to
- `>`  : Greater than
- `<`  : Less than
- `>=` : Greater than or equal to
- `<=` : Less than or equal to

Examples:

```python
a = 5
b = 3
print(a == b)  # Output: False
print(a != b)  # Output: True
print(a > b)   # Output: True
print(a < b)   # Output: False
print(a >= b)  # Output: True
print(a <= b)  # Output: False
```

#### Logical Operators

- `and` : Logical AND
- `or`  : Logical OR
- `not` : Logical NOT

Examples:

```python
x = True
y = False
print(x and y) # Output: False
print(x or y)  # Output: True
print(not x)   # Output: False
```

#### Assignment Operators

- `=`  : Assigns a value
- `+=` : Add and assign
- `-=` : Subtract and assign
- `*=` : Multiply and assign
- `/=` : Divide and assign
- `//=`: Floor divide and assign
- `%=` : Modulus and assign
- `**=`: Exponentiate and assign

Examples:

```python
x = 5
x += 3  # x is now 8
x -= 2  # x is now 6
x *= 4  # x is now 24
x /= 6  # x is now 4.0
```

#### Bitwise Operators

- `&`  : Bitwise AND
- `|`  : Bitwise OR
- `^`  : Bitwise XOR
- `~`  : Bitwise NOT
- `<<` : Bitwise left shift
- `>>` : Bitwise right shift

Examples:

```python
a = 5  # 0b0101 in binary
b = 3  # 0b0011 in binary
print(a & b)  # Output: 1 (0b0001 in binary)
print(a | b)  # Output: 7 (0b0111 in binary)
print(a ^ b)  # Output: 6 (0b0110 in binary)
print(~a)     # Output: -6 (bitwise NOT of 5)
print(a << 1) # Output: 10 (0b1010 in binary)
print(a >> 1) # Output: 2 (0b0010 in binary)
```

These topics cover foundational elements of Python programming, providing a solid base for further learning and exploration.

```

Feel free to adjust or add any details to fit your specific needs!
```
