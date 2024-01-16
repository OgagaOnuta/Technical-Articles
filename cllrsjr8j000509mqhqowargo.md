---
title: "The Python Programming Language Need-to-Know for Beginners"
seoTitle: "Python Need-to-Know for Beginners"
datePublished: Sat Aug 26 2023 09:00:12 GMT+0000 (Coordinated Universal Time)
cuid: cllrsjr8j000509mqhqowargo
slug: python-need-to-know-for-beginners
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1692812953375/1e24b8c6-edfa-432e-8818-29e384dd31f4.png
tags: python, python3, python-beginner, beginnersguide

---

## Introduction

Hello World!, trying to get familiar with **Python**? In this article, we will take a look at the fundamentals to begin writing in **Python Programming Language**. It's going to be a fun ride, so fasten your seatbelts, grab those goggles, and let's ride on!

> Ensure you have [Python](https://www.python.org/downloads/) installed on your machine.
> 
> To practice with the example code included in different sections of the article, ***launch the Python interpreter*** from your *terminal* or *command prompt (or PowerShell)*, or use Python's *Integrated Development and Learning Environment (IDLE)* which comes along with your Python installation.
> 
> Lines beginning with `>>>` represent the *command line* where the Python command(s) and statement(s) are written.

***On Linux or MacOS*** *(run* `python3`*)*

![Python Interpreter on Linux or MacOS](https://cdn.hashnode.com/res/hashnode/image/upload/v1692843466479/152bc992-bf95-4243-a0f6-fa45907c3121.png align="center")

***On Windows*** *(run* `py` *or* `python`*)*

![Python Interpreter on Windows](https://cdn.hashnode.com/res/hashnode/image/upload/v1692843485980/470d522a-eac0-46d4-ba93-63600c70cf41.png align="center")

![Python Interpreter on Windows](https://cdn.hashnode.com/res/hashnode/image/upload/v1692843507867/d99864b1-8615-459e-b12a-c7a79d8c3583.png align="center")

***Python's IDLE***

![Python IDLE](https://cdn.hashnode.com/res/hashnode/image/upload/v1692844389557/add9a546-5a34-48e0-b8ad-aa462e9c4a92.png align="center")

---

## Prerequisite

To have an in-depth feel of this article, you should be familiar with the concept of programming and programming languages. Terms like *syntax*, *statements*, *data*, *data types*, *variables*, and *operators* should not be new to you. Here is a 20-minute [introduction to programming](https://learn.microsoft.com/en-us/training/modules/web-development-101-introduction-programming/) to get started.

---

## What is Python?

Python is a high-level [interpreted](https://thepythonguru.com/python-tutorial/introduction-to-python/#python-is-an-interpreted-language) programming language. Its syntax and commands are similar to the English language. It is as though you are speaking to a friend. This article explains some of the basic concepts needed to begin writing in Python Programming Language.

### Python Syntax

Python syntax refers to the way Python is written, and how it differs from other programming languages. Python is [dynamically](https://thepythonguru.com/python-tutorial/introduction-to-python/#python-is-dynamically-typed) and [strongly](https://thepythonguru.com/python-tutorial/introduction-to-python/#python-is-strongly-typed) typed.

#### Python Comments

Comments in Programming are used to add descriptions to code. The comments are not interpreted but are important to explain what a statement(s) is doing in a program. Adding comments can help non-technical and technical people, including yourself *(or your future self)* understand the process behind the program.

There are two types of comments in Python; single-line comments and multi-line comments.

To add a single-line comment, begin with a hash symbol (`#`), followed by a [whitespace](https://en.m.wikipedia.org/wiki/Whitespace_character) *(optional)*. Single-line comments can be added at the beginning of a line, or after a Python statement. When adding a single-line comment after a statement, it is best practice to leave at least two whitespaces after the statement before adding the comment.

```py
# This is a single-line Python comment
var = "value"  # This is another single-line Python comment
```

To add a multi-line comment, begin and end the comment with **three (3)** single/double quotes (`'''` OR `"""`). Always end with a single quote if you begin with a single quote, and end with a double quote if you begin with a double quote, but never mix the quotations.

```py
'''
This
is
a
multi
line
comment
'''
```

#### Python Statements

Python statements are instructions to be run/interpreted to produce a desired result. Each statement gives a specific instruction. Python statements are written on independent lines and do not require any closing *(like periods, semi-colons, etc.)*. Although multiple statements can be written on one line, separated by semi-colons (;), it is not recommended.

```py
# NOT RECOMMENDED!!!
var = "value"; print(var)
```

```py
# This is BETTER
var = "value"
print(var )
```

#### Indentation in Python

Indentation is used to group code blocks. It identifies code blocks as belonging to an [object](https://ogagaonuta.hashnode.dev/python-need-to-know-for-beginners#heading-concept-of-object-oriented-programming-in-python), like a parent-child relationship. Statement(s) in code blocks in Python are indented by **4 spaces or 1 tab**.

```py
val1 = 5
val2 = 4

'''
The brackets used in the "if" statements are not
necessary, they are just a way to group my code.
'''
if (val1 > val2):
    print("{} is greater".format(val1))
else:
    print("{} is greater".format(val2))
```

![Python Indentation](https://cdn.hashnode.com/res/hashnode/image/upload/v1692844753118/8e0199e2-2c0e-444a-9e87-425568f1ae9c.png align="center")

> If you are curious about what you are looking at, check out [**if\_else statements**](https://www.w3schools.com/python/python_conditions.asp) and [**Formatting strings in Python**](https://www.w3schools.com/python/ref_string_format.asp).

### Handling Variables in Python

A variable is similar to a container that stores a particular value. To create a variable in Python, you begin with the variable name, followed by the [assignment operator](https://www.w3schools.com/python/gloss_python_assignment_operators.asp), and then the value to be stored in the variable.

```py
size = 42
```

From the example above, the variable name *(the container)* is `size`, and the value it contains is `42`.

#### Rules for Naming Python Variables

There are certain rules to be followed when creating a variable in Python. Highlighted below are the rules:

* Variable names *begin* with an **alphabet** or an **underscore**.
    
* Variable names consist of any *combinations* of **alphabets**, **underscores**, and **numbers**.
    
* Variable names are **case-sensitive**.
    
* Variable names *cannot* be [**Python Keywords**](https://www.digitalocean.com/community/tutorials/python-keywords-identifiers).
    

Python variables can be of any length, but it is good practice for variable names to be as descriptive as possible. Variable names containing more than one word can either be written in [*camelCase*](https://en.m.wikipedia.org/wiki/Camel_case) or separated by underscores.

```py
streetName = "Baker"
street_number = 21
GradePoint = 4.5
shopping_list = ["Baking Pan", "Spatula", "Sugar", "Eggs", "Flour"]
blonde = False
```

#### Defining Variables

Python variables can be declared and defined whenever needed. They do not need to be declared initially and then defined later on in the document.

> In some situations, using the same variable name later on in the document will replace the previous value stored in the variable.

### Data Types in Python

Data type refers to the type of information a variable can contain. There are several data types in Python, but for the sake of this article, we will look at a few needed to understand the basics.

> To find out the data type of a variable, use the `type()` function in Python.
> 
> To get help with the functions (methods) available for any data type, use the `help()` function in Python.
> 
> Check out [*Python Data Types*](https://www.w3schools.com/python/python_datatypes.asp) for more information.
> 
> Python functions are not covered in this article, but check out [*Python Functions*](https://www.w3schools.com/python/python_functions.asp) if you're curious.

```py
help(str)
help(bool)
```

#### Strings

A string (`str`) in Python is a sequence of characters, arranged consecutively. Strings are created by enclosing the character(s) in single or double quotes and assigning it to a variable. Just like comments, a string can also span multiple lines by enclosing the character(s) in three (3) single or double quotes. Other data types can be converted to a string by using the `str()` function.

```py
myStr1 = 'This is a string'
print(myStr1)
print(type(myStr1))  # Confirming the data type of the variable
```

![Python string output](https://cdn.hashnode.com/res/hashnode/image/upload/v1692844811428/5a82180a-d581-4d23-b6d8-143ccbfbebcf.png align="center")

```py
myStr2 = "This is also a string"
print(myStr2)
```

![Python string output](https://cdn.hashnode.com/res/hashnode/image/upload/v1692844849839/9d4aef75-6dfd-4832-818e-4f53fed6be06.png align="center")

```py
myStr3 = '''This is
a multi-line
string. It
occupies more
than one line'''
print(myStr3)
```

![Python string output](https://cdn.hashnode.com/res/hashnode/image/upload/v1692844882358/fc91930c-c6fb-4c4f-8c3a-91304e6a8797.png align="center")

```py
myStr4 = """This is yet
another multi-line
string. It also
occupies more
than one line"""
print(myStr4)
```

![Python string output](https://cdn.hashnode.com/res/hashnode/image/upload/v1692844908917/224ad204-9bf5-4157-aff5-fdd85d2ec0b7.png align="center")

#### Integer

An integer (`int`) in Python is a whole number, positive or negative, without a decimal point, with unlimited length. Integers are created by assigning a whole number to a variable. Operations carried out on integers will result in another integer. Other data types can be converted to an integer by using the `int()` function.

```py
myInt1 = 4
myInt2 = 10
myInt3 = myInt1 * myInt2

print(myInt1)
print(myInt2)
print("{} multiplied by {} will result to {}".format(myInt1, myInt2, myInt3))
print(type(myInt3))
```

![Python integer output](https://cdn.hashnode.com/res/hashnode/image/upload/v1692844939908/f9d073e3-dea9-4c76-8c0c-e0710873461c.png align="center")

#### Float

A float in Python is a decimal point number, positive or negative. Floats are created by assigning a decimal point number to a variable. Operations carried out on floats will result in another float, and operations carried out on integers and floats will result in a float too. Other data types can be converted to a float by using the `float()` function.

```py
myFloat1 = 3.5
myFloat2 = 4.7
myInt2 = 10

myVar1 = myFloat1 + myFloat2
myVar2 = myFloat2 * myInt2  # Operation on float and int

print(myVar1)
print(type(myVar2))
```

![Python float output](https://cdn.hashnode.com/res/hashnode/image/upload/v1692844986980/96e9e477-16e0-44f8-8019-6cd0ad1851a4.png align="center")

#### List

A list in Python is a group of variables stored together as one variable. Lists are created by assigning one or more values separated by commas within square brackets to a variable. A list can contain different types of data, including other lists. The values within the square brackets are called **"items"**. Items in a list are ordered by **index** beginning with the index `0` and can include duplicate values.

```py
# list containing items of the same data type
myList1 = [9, 8, 5, 3, 2, 9, 0]

# list containing items of different data types
myList2 = ["October", 7, 2029, 20.5, False]

var1 = 1
var2 = 3.7
var3 = "This is interesting"
var4 = True
myList3 = [var1, var2, var3, var4]

print(myList1)
print(myList2)
print(myList3)
print(type(myList3))
```

![Python list output](https://cdn.hashnode.com/res/hashnode/image/upload/v1692845085491/61165fb2-4807-4224-81db-c9a38fe252db.png align="center")

#### Boolean

Booleans in Python are one of two possible values; `True` or `False` *(not* `true` or `false`, **NOTE** the Capital letters). They can be used to decide the outcome of several operations. The function `bool()` can be used to evaluate any value. Most values are evaluated as `True` except for empty values.

```py
myBool1 = True
myInt1 = 4
myFloat2 = 4.7

if (myInt1 < myFloat2):
    print(myBool1)
else:  # Expression is False
    print(False)
```

![Python boolean output](https://cdn.hashnode.com/res/hashnode/image/upload/v1692845118773/ae374ea6-20dd-40e6-98fa-eda8ab002f6d.png align="center")

### Understanding Python Errors

There are at least two kinds of errors in Python, **Syntax errors** and **Exceptions**.

#### Errors

**Syntax errors** are raised when there's a mistake in the written program. Mistakes such as a wrong indentation, using a wrong variable name, and the like can result in a syntax error.

![Python syntax error](https://cdn.hashnode.com/res/hashnode/image/upload/v1692845159727/8dfaff3b-0fa0-4f9f-b8f7-526a2bbfbfd9.png align="center")

#### Exceptions

**Exceptions** on the other hand are detected during execution of the program. The program must have already passed the syntax checking before exceptions are raised.

![Python exception](https://cdn.hashnode.com/res/hashnode/image/upload/v1692845183003/efdcfe07-703d-48bf-a4ba-dc9355bf972a.png align="center")

As seen from the images above, the error message tells you what kind of error has been made, and sometimes even suggests possible corrections. It also tells you what file and line number the error was raised from.

### Concept of Object-Oriented Programming in Python

**Object-Oriented Programming** (OOP) refers to the logic of each element operating as a first-level element. This means that each element is on the first rank in the hierarchy of things. Two terms you would notice in OOP are **Classes** and **Objects**. A common example is *"An Architect drawing a building plan"*, after drawing the plan, different structures can be built from it. The plan is referred to as the ***Class***, while the structures built from the plan are referred to as ***Objects***.

Elements include *variables*, *loops*, *control structures*, *functions*, *modules*, and even *classes* and *objects*.

> Check out [***Python OOP***](https://pynative.com/python/object-oriented-programming/) to know more.

---

## Conclusion

Whew! Was that a lot to take in? It was an interesting ride, yeah?

I expect us to be warmed up and excited about **Python** by now, I certainly am. After completing this article, we should feel confident about Python *syntax, variables, data types, errors, and OOP*. To improve on what you already know, go through the resources provided below.

Now go type some **Python** code.

* [https://thepythonguru.com/](https://thepythonguru.com/)
    
* [https://www.learnpython.org/](https://www.learnpython.org/)
    
* [https://www.w3schools.com/python/](https://www.w3schools.com/python/)
    
* [https://www.tutorialspoint.com/python/index.htm](https://www.tutorialspoint.com/python/index.htm)
    
* [https://realpython.com/python-first-steps/](https://realpython.com/python-first-steps/)
    
* [https://www.freecodecamp.org/news/the-python-handbook](https://www.freecodecamp.org/news/the-python-handbook)