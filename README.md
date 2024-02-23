# Python for begginers
Welcome to the exciting world of Python programming! This guide serves as your roadmap to mastering the fundamentals of Python, equipping you with the knowledge to build your own projects and explore new horizons.

## 1. Python Basics: Laying the Foundation
### 1.1 What is Python?

Python is a powerful yet versatile programming language known for its readability, simplicity, and extensive libraries. It's perfect for beginners due to its clear syntax and emphasis on code clarity.

### 1.2 Setting Up:

Before diving in, ensure you have Python installed on your system. Download and install it from the official website: https://www.python.org/downloads/

### 1.3 Pip: Your Package Manager:

Python uses pip to install and manage external libraries. Open your terminal and run pip --version to check if it's installed. If not, install it using the instructions provided on the official website: https://pip.pypa.io/en/stable/installation/

### 1.4 Variables:

Variables store data like numbers, text, or booleans. You can create them using their names and assigning values:

```
name = "John"
age = 30
is_happy = True
```
### 1.5 Data Types:

Python supports various data types:

Numbers: Integers (whole numbers) and Floats (decimal numbers)  
Strings: Text enclosed in single or double quotes  
Booleans: True or False values  
Lists: Ordered collections of items enclosed in square brackets []  
Tuples: Ordered collections of items like lists, but immutable (unchangeable)  
Dictionaries: Unordered collections of key-value pairs enclosed in curly braces {}  
### 1.6 Basic Operators:

Python uses operators for calculations and comparisons:

Arithmetic operators: +, -, *, /, % (modulo)  
```
# Addition (+): Adds two numbers.
x = 10
y = 5
sum = x + y
print(sum)  # Output: 15

# Subtraction (-): Subtracts one number from another.
difference = y - x
print(difference)  # Output: -5

# Multiplication (*): Multiplies two numbers.
product = x * y
print(product)  # Output: 50

# Division (/): Divides one number by another. In Python 2, this might result in a float even for integer division.
quotient = x / y
print(quotient)  # Output: 2.0 (in Python 3)

# Floor division (//): Divides one number by another and returns the integer quotient, discarding any remainder.
floor_quotient = x // y
print(floor_quotient)  # Output: 2

# Modulus (%): Returns the remainder after dividing one number by another.
remainder = x % y
print(remainder)  # Output: 0

# Exponentiation ():** Raises one number to the power of another.
power = x ** y
print(power)  # Output: 1024
```
Comparison operators: ==, !=, <, >, <=, >=  
```
# Equal to (==): Checks if two values are equal.
x = 5
y = 10
is_equal = x == y  # False
print(is_equal)

# Not equal to (!=): Checks if two values are not equal.
is_not_equal = x != y  # True
print(is_not_equal)

# Greater than (>): Checks if the left operand is greater than the right.
is_greater = x > y  # False
print(is_greater)

# Less than (<): Checks if the left operand is less than the right.
is_less = x < y  # True
print(is_less)

# Greater than or equal to (>=): Checks if the left operand is greater than or equal to the right.
is_greater_equal = x >= 5  # True
print(is_greater_equal)

# Less than or equal to (<=): Checks if the left operand is less than or equal to the right.
is_less_equal = y <= 10  # True
print(is_less_equal)
```
Logical operators: and, or, not  
```
# and:

# Returns True if both operands are True, otherwise False.
# Example: Checking if a number is even and greater than 5:
number = 8
is_even_and_greater_than_5 = number % 2 == 0 and number > 5
print(is_even_and_greater_than_5)  # Output: True

# or:

# Returns True if at least one operand is True, otherwise False.
# Example: Checking if a grade is either an A or a B:
grade = "B+"
is_a_or_b = grade == "A" or grade == "B"
print(is_a_or_b)  # Output: True

# not:

# Reverses the logical value of the operand.
# Example: Checking if a name is not empty:

name = "John Doe"
is_not_empty = not name == ""
print(is_not_empty)  # Output: True

# Here are some additional examples with multiple operators:

# Checking if a user is eligible for a discount:

age = 25
is_student = True
is_eligible = (age >= 18 and not is_student) or age >= 65
print(is_eligible)  # Output: True if age >= 18 and not student or age >= 65

# Checking if a number is within a specific range:

min_value = 10
max_value = 20
number = 15
is_within_range = min_value <= number <= max_value
print(is_within_range)  # Output: True
```
### 1.7 Input and Output:

Use the input() function to get user input and the print() function to display output on the screen.

```
name = input("What is your name? ")
print("Hello, " + name + "!")
```
### 1.8 Built-in Functions:

len(): Get the length of an object  
type(): Get the type of an object  
min(), max(): Find the minimum or maximum value  
str(), int(), float(): Convert between data types  
## 2. Data Type Operations: Mastering Manipulation
### 2.1 String Operations:  

Concatenation: string1 + string2  
Slicing: string[start:end:step]  
Searching: string.find("substring")  


### 2.2 List Operations:

Access elements: list[index]  
Modify elements: list[index] = value  
Add elements: list.append(value)  
Remove elements: list.remove(value)  
Iterate over elements: for item in list:  
### 2.3 Tuple and Dictionary Operations:

Accessing elements: tuple[index], dictionary[key]  
Modifying dictionary elements: dictionary[key] = value  
Adding dictionary elements: dictionary["new_key"] = value  
## 3. Loops and Functions: Automation and Reusability  
### 3.1 Loops:

for loop: Iterates over a sequence 
```
for i in range(1, 6):  # Starts at 1, excludes 6
    print("Number:", i)

name = "John Doe"

for char in name:
    print(char)
``` 
while loop: Repeats a block of code until a condition is met 
```
i = 1
while i <= 10:
  print(i)
  i += 1

name = "John Doe"
lenght = len(name)
while lenght >= 0:
    print(name[:lenght:])
    lenght -= 1
``` 
### 3.2 Functions:

Define functions using the def keyword  
Functions accept arguments and return values  
Use functions to reuse code and make it modular  
```
def func_name():
    pass
```
## 4. OOP in Python: Object-Oriented Programming  
### 4.1 Classes and Objects:  

Define classes as blueprints for objects  
Objects are instances of classes  
Objects have attributes and methods  

class ClassName:
   Statement-1
   .
   .
   .
   Statement-N  
```
class Person:  
    pass
```

```
class Person:

  def __init__(self, name, age, city):
    self.name = name
    self.age = age
    self.city = city

  def greet(self):
    """
    Greets the person with a personalized message.
    """
    print(f"Hello, my name is {self.name} and I am from {self.city}!")

# Create an instance of the Person class
person1 = Person("Mayank", 30, "Indore")

# Access and modify attributes
person1.age += 1
print(f"Person's name: {person1.name}, age: {person1.age}, city: {person1.city}")

# Call the greet method
person1.greet()
```
### 4.2 Inheritance:

Create new classes (subclasses) that inherit properties from existing classes (superclasses)  

class Parent:
    pass

class Child(Parent):
    pass

```
class Parent:  # Creating the parent class
    def greet(self):
        print('Hello from the Parent class!')

class Child(Parent):  # Creating the child class
    pass

# Creating an instance of the Child class
child = Child()
child.greet()

# Output:
# 'Hello from the Parent class!'
```
### 4.3 Encapsulation and Polymorphism:

Encapsulation: Protect data and methods within objects
```
class BankAccount:
    """
    Represents a bank account with encapsulated balance and account number.
    """

    def __init__(self, _account_number, initial_balance):
        self._account_number = _account_number  # Private attribute
        self._balance = initial_balance  # Private attribute

    def get_balance(self):
        """
        Returns the account balance.
        """
        return self._balance

    def deposit(self, amount):
        """
        Deposits money into the account.
        """
        if amount > 0:
            self._balance += amount
            print(f"Deposited {amount}. New balance: {self._balance}")
        else:
            print("Invalid deposit amount. Please enter a positive value.")

    def withdraw(self, amount):
        """
        Withdraws money from the account if sufficient funds are available.
        """
        if amount > 0 and self._balance >= amount:
            self._balance -= amount
            print(f"Withdrew {amount}. New balance: {self._balance}")
        else:
            print("Insufficient funds. Current balance:", self._balance)

# Create a bank account object
account1 = BankAccount("12345678", 1000)

# Access balance directly (not recommended)
# print(account1._balance)  # This would violate encapsulation

# Access balance using the get_balance method
print(account1.get_balance())  # Output: 1000

# Deposit money
account1.deposit(500)

# Withdraw money
account1.withdraw(200)

# Try to withdraw more than available balance
account1.withdraw(1500)

```

Polymorphism: Objects of different classes can respond to the same method in different ways  
polymorphism means the same function name (but different signatures) being used for different types. The key difference is the data types and number of arguments used in function.
```
class India():
    def capital(self):
        print("New Delhi is the capital of India.")
 
    def language(self):
        print("Hindi is the most widely spoken language of India.")
 
    def type(self):
        print("India is a developing country.")
 
class USA():
    def capital(self):
        print("Washington, D.C. is the capital of USA.")
 
    def language(self):
        print("English is the primary language of USA.")
 
    def type(self):
        print("USA is a developed country.")
 
obj_ind = India()
obj_usa = USA()
for country in (obj_ind, obj_usa):
    country.capital()
    country.language()
    country.type()
```


