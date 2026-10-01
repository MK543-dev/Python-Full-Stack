[Python (1).md](https://github.com/user-attachments/files/32923621/Python.1.md)
# Python Full Stack with AI/ML Notes

## Table of Contents

1. [Python Full Stack Overview](#python-full-stack-overview)
2. [Types of Applications](#types-of-applications)
3. [Introduction to Python](#introduction-to-python)
4. [Setting Up Python](#setting-up-python)
5. [Python Character Set](#python-character-set)
6. [Python Keywords](#python-keywords)
7. [Python Comments](#python-comments)
8. [Python Identifiers](#python-identifiers)
9. [Python Data Types](#python-data-types)
10. [Input and Output Statements](#input-and-output-statements)
11. [Python Variables](#python-variables)
12. [Python Operators](#python-operators)
13. [Practice Programs on Operators --> codes](#practice-programs-on-operators)
14. [Overloaded Operators](#overloaded-operators)
15. [Conditional Statements](#conditional-statements)
16. [Looping Statements](#looping-statements)
17. [Programs on Strings and Lists (Without Built-in Functions) --> codes](#programs-on-strings-and-lists-without-built-in-functions)
18. [Programs on Numbers --> codes](#programs-on-numbers)
19. [Programs on Patterns --> codes](#programs-on-patterns)
20. [Un-conditional Statements](#un-conditional-statements)
21. [String Formatting](#string-formatting)
22. [Data Structures](#data-structures)
23. [Indexing and Slicing](#indexing-and-slicing)
24. [Programs on Lists and Strings --> codes](#programs-on-lists-and-strings)
25. [Searching and Sorting](#searching-and-sorting)
26. [Comprehensions](#comprehensions)
27. [Working with Lists](#working-with-lists)
28. [Working with Tuples](#working-with-tuples)
29. [Working with Strings](#working-with-strings)
30. [Working with Sets](#working-with-sets)
31. [Working with Dictionaries](#working-with-dictionaries)
32. [Python Functions](#python-functions)
33. [Recursion](#recursion)
34. [Monkey Patching](#monkey-patching)
35. [Decorators](#decorators)
36. [Iterators and Generators](#iterators-and-generators)
37. [Annotations and Doc Strings](#annotations-and-doc-strings)
38. [Packing and Unpacking](#packing-and-unpacking)
39. [Python Built-in Functions](#python-built-in-functions)
40. [Scope](#scope)
41. [Modules and Packages](#modules-and-packages)
42. [OOPS: Classes and Objects](#oops-classes-and-objects)
43. [Constructors](#constructors)
44. [Built-in Classes](#built-in-classes)
45. [Inheritance](#inheritance)
46. [Data Abstraction](#data-abstraction)
47. [Data Encapsulation](#data-encapsulation)
48. [Abstract Classes](#abstract-classes)
49. [Polymorphism](#polymorphism)
50. [Singleton Class](#singleton-class)
51. [Meta Classes](#meta-classes)
52. [Data Classes](#data-classes)
53. [OOPS Relationships](#oops-relationships)
54. [Exception Handling](#exception-handling)
55. [Asynchronous Functions](#asynchronous-functions)
56. [Multi-threading](#multi-threading)
57. [Relational Databases](#relational-databases)
58. [Working with MySQL](#working-with-mysql)
59. [Tables and Constraints](#tables-and-constraints)
60. [SQL Clauses](#sql-clauses)
61. [Aggregate Functions, Group By and Having](#aggregate-functions-group-by-and-having)
62. [MySQL Operators (Logical, IN, BETWEEN, LIKE)](#mysql-operators-logical-in-between-like)
63. [Alter Command](#alter-command)
64. [MySQL with Python](#mysql-with-python)
65. [Null Values and Case Statement](#null-values-and-case-statement)
66. [MySQL Built-in Functions](#mysql-built-in-functions)
67. [Window Functions](#window-functions)
68. [CTEs and Joins](#ctes-and-joins)
69. [Programming with SQL](#programming-with-sql)
70. [Stored Procedures, Functions and Triggers](#stored-procedures-functions-and-triggers)
71. [Indexes](#indexes)
72. [Transactions](#transactions)
73. [AI/ML](#aiml)

---

## Python Full Stack Overview

full stack is a "combination of front-end and back-end"

full stack refers " front-end+ back-end+ databases+ deployment"

**what is mean by Front-end:**

front-end means "application user interface"

application user interface makes the  "user can able to interact with

application"

with help of python full stack, we are developing the following types

of applications:

1)  stand-alone or desktop application

2)  web application or internet application

3)  enterprise application or business specific application

4)  distributed application

when want to develop the application UI for the above applications,

**we will use the following Tech.:**

1)  HTML:

html is a "markup language", which is uses "tags" to describe the

data

using "HTML", we can able to "Design or create the structure of the

UI or application User Interface"

**2) CSS:**

css is a style sheet using this we can able to give the "Look and feel

for any application UI, which is made with HTML"

**3)  JS:**

java script is a "client-side scripting language"

java script is often called as "programming language for UI"

with  help JS, we can able to perform the following actions:

1)  event management

2)  form management

3) any DOM activities,............................

**4) Bootstrap:**

bootstrap is also called as "CSS framework"

using bootstrap, we can able to make the "Application UI" as

Responsive (with this, we can able to open the application UI in

any device)

HTML  ===\> to design or create the structure the UI

CSS  ===\> to style the "application UI"

JS  ===\> to write any coding at  "Application UI"

Bootstrap  ===\> to make the application UI as responsive

**UI framework( to develop the end-to-end Realtime UI):**

React

**what is mean by back-end:**

back-end means "application server", which is used to process the

any user request or action

when server wants to process the "any user request or action",

server will uses a program or a logic, which is developed using

following technologies:

1)  Python

2)  java

3)  PHP

4)  Node JS .................

in our course,  we are learning " Python" as back-end technology.

**what is mean by database:**

database in used in the application, to store the all application users

data

**what is data?**

data refers "what we can able to store in the computer memory"

example:  image, audio, video, text, document,............

what is information:

information refers "processed data" " data which come from a

process"

based how we store the data in the database or based on what

structure  we use to store the data, the databases are classified into

two types:

1)  Relational Database

in this database, we will store the data in the form  of "Table"

any database store the data in the form of table, then the database is

called as "Relational Database"

Relation means " Table"

when we want to work with relational database, we will use a language

called "SQL"

when want to work with relational database using SQL, we will use

a software called "DBMS" , the DBMS which uses relational database

is called "RDBMS"

the following are the popular RDBMS :

1)  MySQL

2) oracle

3) sql server

4) IBM DB2

5)  Sybase......................

in our course we are learning "MySQL with SQL" as relational database

**2)  Non-relational Database:**

any database store the data other than table to store the data, then

the database is called  "Non-relational database"

in this database, we are never going to use any language called "SQL",

this is also often called  "No-SQL database"

in our course , we are learning a database called "MongoDB", which

uses "document" structure to store the data, where the document will

have the data in the form of key and value pairs

full stack=  application UI + application Server + Database

for UI:  html, css, javascript, Bootstrap

UI framework:  React

back-end:  Python

Databases:  MySQL with SQL, MongoDB

web frameworks:

Flask   ===\> for small scale or any AI/ML applications

Django ====\> to make any larger application

**API Frameworks:**

Rest API with Django

Fast API

DSA

using python full stack, we can able to develop the following

---

## Types of Applications

**1. stand-alone application or desktop application :**

when we say any application is "stand-alone application" or "desktop"

application, the application never uses "internet" to access the

application  and  the application never uses "server" to run the

application

example:  calendar , camera, gallery, notepad.......................

these applications we can develop in the very limited space in real time,

because these application will never allow the  "sharing of data"

**2. web application or internet application:**

if we say any application is "Web or enterprise application" , then the

application uses "internet" to access the application and server to

run the application

example:  gmail, dropbox, drive, youtube,.......................

in this application, we can able to have the "data sharing", it means

we can able to share the data from the one device to another device

in real-time, almost all applications by default "web applications" ,

in this applications, we can not able to have "Server to server"

communication

**3. Enterprise application:**

every enterprise application by default "Web application", but not

vice versa, this application also uses internet to access the application

and server to run the application

in this application, we can also have "server to server communication"

example:   Amazon, book my show, blinkit,.................

in real-time, in the enterprise application, the server can able to

communicate with another server using "API"

this server -to- server communication will done in the enterprise

in the following ways:

1)  native server communication

2)  Third-party server communication

**the major common issues with enterprise application:**

1)   when the load is high, it un able to process

2)  it can not scale the user limit

3)  it can not reverse the operations back

4) it maintain different databases for each server

**4. Distributed application:**

distributed application is can be  "Web or enterprise" application  it

maintain the following:

1)  Load balancing

2)  auto scaling

3)  Fault tolerance

4)  De-centralized database

5)  high performance

---

## Introduction to Python

python is a "high-level, strongly typed, dynamic typed, object-oriented

programming language"

**why python high-level?**

**in computers, we  will have following types of languages:**

**1) high-level language:**

if language which is used by  "programmers or developers" to write

any code or program, then the language is called as "high-level"

language

example:  python, c, c++, java, php,.................

**2) binary language or machine or low-level:**

if any language is understand by  "computer or machine", then the

language is "binary" , it is in 0's and 1's

in order to execute the machine  for given program , we are using

a software called " language translator"

language translator converts the given program or code into

binary

the following are popular language translators:

1)  compiler

2) interpreter

python uses "both compiler and interpreter" as a language translator

to convert the code into binary

**why python is strongly typed:**

python is a strongly typed language, because, when we are performing

the operation on the operands(Data), the operands always need to

same type, otherwise python will not allow the operation

if any high-level language allow the operation on any type, then the

language is called as "loosely typed language"

example: javascript

**why python is dynamic typed?**

python is a dynamic typed, because any data we are storing into the

variable, we no need to specify the "data type of the variable" , it

automatically become specific type, based on what data we store into

variable

if any high-level language, always allow the programmer or developer

has to specify the data type, before storing the value into it  , then the

language is called as "static typed language"

example:   C, C++, Java,............

**why python is object-oriented?**

object-oriented is a programming paradigm

programming paradigm refers "what way we write the program  or

code on that language", it will give the style, rules what way to  write

code "

programming paradigm we will refers "what the way the programmer

or developer can able to write the code"

if we say any language is object-oriented, then the language must

**follow the following  concepts:**

1)  classes and objects

2)  inheritance

3)  Data abstraction

4)  Data Encapsulation

5)  Polymorphism

python supports above all concepts, that is reason  "python is called as

object-oriented"

**why python?:**

1)  Python is very easy to learn , when compare with other languages,

because very simple syntax

**2) Python is used in the following domains:**

1)  application development

2)  Artificial Intelligence

3)  Data Science

4)  Data Analytics

5)  Data Eng.

6)  Automation and Testing

7)  IoT

8)  Cyber Security

9) Cloud and DevOps

10)  Networking

11)  Gaming Development..............................

because this many use cases, python often called as "Multi-domain

dominance "  language

3)  Python is a platform independent

platform  means "computer hard ware and software"

when we want to runs the python program we need the following

hard ware and software:

**hard ware:**

RAM, Processor

**software:**

OS, Compiler, PVM(which contains Interpreter)

when we write the python program, the python program will be

**executed in the following steps:**

1)  first we need to write the python program and save it with some

name.py , for  example, we save the program with name "sample.py"

2) after saving the program, first the program will taken by "compiler" ,

compiler takes the python program (Sample.py) and converts into

an intermediate code, this intermediate code is also called as "byte

code"

intermediate code is not a "python code or binary code"

the intermediate code file extension is ".pyc"

3) once we got the "byte code", the byte code will taken by "PVM" and

this will generate the "Executable code"  (sample.exe)

PVM is able to execute the byte code into executable code, using

interpreter

sample.py ===\> python compiler ===\> byte code ==\> PVM ==\>exe. code

the byte code can able to execute on any platform , where the platform

must have "PVM", where the byte code makes the "python as

platform  independent" , but the PVM is always "platform dependent"

**python is a open source:**

when we say any software or system is open source, then the it's

entire source code is available to everyone

the entire python source code is available to all users, because of this

we will have the following python flavours:

1)  Cpython

the most commonly used  python flavour, and it is implemented in

C and Python

2)  Jython

to run the Python on "JVM"

3)  IronPython

to run python on ".NET" framework

4)  pypy

python with JIT compiler

5)  stackless python

python for threading and concurrency

6)  Micro Python...............

Python for Micro Controllers......................

---

## Setting Up Python

when we want to work with python programming , we will use "IDLE"

IDLE is a software and which is used to "Write, Run, Test and Debug

any program"

**the following popular IDLE's:**

1)  Python IDLE  (this will come automatically, when install python)

2) Spyder

3)  Jupyter Note Book

4)  Google Colab

5)  Vs code editor

6)  PyCharm

first we need to download and  install the python

**use the following url for download python:**

https://www.python.org/downloads/

after installing the python , we need to install the a frame work

called " Anaconda Navigator"

**use the following URL to download Anaconda Navigator:**

https://www.anaconda.com/download

**Python language fundamentals :**

---

## Python Character Set

**in python, we will have three types of characters:**

1)  letters

there are two types of letters:

1)  upper case letters

example:  A, B, C, D,  E, .........Z

2)  lower case letters

example:  a, b, c, d, e, f, g, h, i.......z

2)  digits

0, 1, 2 ,3 ,4 ,5, 6 ,7 ,8,9

**3)  special characters or symbols:**

\+, \*, -, ~, !,@, #,$,%, ^, &, (, ),\[, \],{,}, \|, \\,/,',",:,;,,,.,=,\_,\<,\>,...................

---

## Python Keywords

keywords are also called "reserved words", these words are given

by python and these words are used in python for specific purpose in

the python program

**the following are important keywords of the python language:**

```python
for operators:
```

for logical operators:   or, and , not

for membership operators:  in

for identity operators:   is

for Boolean data type:   True , False

for conditional statements:   if,  else, elif, match, case

for looping statements:   for , while

for un-conditional statements:   continue, break, pass

for functions: def, lambda, return, yield

for scope:   global, nonlocal

for modules and packages:   import, from, as

for oops:   class

for exception handling : try, except, finally, assert, raise

for asynchronous functions:  async , await

for None type:   None

for context managers:  with

when we want to get the all python keywords of the current version

**, we will use the following python code:**

```python
import keyword
print(keyword.kwlist)
```

---

## Python Comments

comments will "Describe the code"

with help of comments any programmer or developer can able to

read the code and understand the code easily , every programmer or

developer, while implementing  code, they always need to write the

comments

**in python, we can have two types of comments:**

1)  single line comments

when we want to write the comments in the single line, we will

use a symbol called "#"

syntax:

```python
                          #write the comments
```

**2) multi-line comments :**

when we want to write the comments in the multiple lines, in

python, we will use "triple quotes"  (''' ''' or """ """)

any string we write in the triple quotes, then the string is called as "doc

string"

when we store the doc-string inside the variable, then the string act as

"multi-line string"

when we write the doc-string directly inside the program, then the

string is act as "multi-line comment"

writing the comments, will not zero effect the code execution  and

comments will be ignored by compiler while translation

---

## Python Identifiers

any name in the python program is called  as "identifier"

the name may be "variable name, list name, string name, tuple name,

class name, function name,..................."

when we want to create the identifier in python, we will use the

**following rules:**

1)  identifier always must starts with "letter or underscore"

2) identifier always will have only the following characters:

1)  all letters (a-z or A-Z)

2)  all digits (0-9)

3) only one special symbol called "\_"

3)  identifier name can not or never be keyword name or reserved

name

4)  identifier name never contain white spaces

5) identifier name length can be any size

6) identifier name can be alphanumeric (name can contain both letters

as well as digits)

**example:**

abc123  (valid)

```python
_abc(valid)
```

abc\_123 (valid)

abc# (invalid)

```python
#abc(it is valid, it is considered as a comment)
```

---

## Python Data Types

data type refers "what type of data the variable has"

when we want to know the "what type of data the variable has",

in python, we will use a function  called "type()"

**in python, we will have the following datatypes:**

1)  numeric type

2) Boolean type

3)  text type or character type

4)  sequence type

5)  set type

6) map type

7)  binary type

8)  None type

the above all are also called as "python built-in data types", built-in data

types refers "the data types which are given by python"

**1. numeric type:**

numeric type refers "numbers"

in python, we will have the following types of numbers:

1)  integer number (number without decimal or fractional part)

example:  10, 234, 5678, -9012,............

2)  floating-point numbers or real numbers (number with decimal

point or fractional part)

example:   1.234,-4.567,8.9012,.............

**3) complex numbers**

python will support the complex numbers

in python, the complex number is in the form of "a+bj" or "a+bJ"

in the complex number , where a refers "Real number"  and "b"

refers "imaginary  number"

in the complex number, where "imaginary always we need to

represents either "j or J", no other character is  allowed

**4) special numbers:**

**1) binary number:**

in python , we can able to represent the binary number with the prefix

called "ob or 0B"

example:  0b10101, oB110011

**2) octal number :**

in python , we can able to represent the octal number with the prefix

called "oo or 0O"

example:  0o157, 0O1777

**3) decimal number:**

in python, no any special representation for "Decimal number", because

every integer number, in python by default "Decimal" number

**4) hexa-decimal number :**

in python , we can able to represent the hexe-decimal number with the

prefix called "ox or 0X"

example: oxab123, 0Xabc1234

the above all numbers are also called as "computer numbers"

for machine, we will use "binary"

for humans, we will use "decimal"

for memory addressing and system purpose, we will use "octal and

hexa-decimal" number

**2.Boolean type:**

**in python, we will have two Boolean values:**

1)  True  (We can not write this as true)

2)  False  (We can not write this as false)

when we are working with  arithmetic operations using Boolean data,

python will convert the Boolean values into numeric.

True ===\> 1

False ===\> 0

**example:**

```python
print(10+True)   ===> 11

print(True+True)  ===>2

print(True*False+10)  ==>10
```

**3. text type or character type:**

any text data in python, we are calling as "string"

any string data can be represented in quotes (' ' or " " or """ """ or '''

```python
''')
```

**in python, we will have two types of strings:**

1)  inline string

when we want to represent the any string as inline, then we will use

"single or double quotes"

example:

"hello"

**2)  multi-line string**

when we want to represent the any string as multi-line, then we will

use "triple quotes"

**4)  sequence type:**

when we want to store the multiple values under one single name,

in python we are going to use "Sequence type"

in python , any data type store the "multiple values or objects under

single name", then the data type is also called as "collection type"

when we say any data type is "sequence type" in python, then the

data type must follow "indexing and slicing" and data will store

exactly  in the given order in the memory while creation

**in python, the following are the sequence data types:**

1)  list

2)  tuple

3)  string

4)  range()

above all will follow the indexing and slicing , all will store the data

exactly in the order

**in python, sequence types are divided into two types:**

1) mutable sequence type  (Which allow the changes)

2) immutable sequence type  (which not allow the changes)

when we say any sequence type is "mutable" , the sequence type will

allow the changes , here the changes can be done using " insert ,update

, delete" operation

**the following are mutable sequence types in Python:**

1)  list

when we say any sequence type is "immutable" , the sequence type will

not  allow the changes , here the changes can not be done using "

insert ,update , delete" operation

**the following are immutable sequence types:**

1)  tuple

2)  string

3)  range()

**list:**

list is a "mutable sequence type, which allow the insert, update, delete

, indexing and slicing operations"

**in python , list can be created using following ways:**

1) using "\[\]" (Subscript)

2) using list() constructor

**in python, list can be:**

1) empty

2) can have duplicate elements

3) can have any type of data

4) can also have another list(nested or inner list) as data

example:

\[1,2,3,4\]

\[\]

\[1,2,3,4,5,2,4,5,3,1\]

\[\[1,2,3,45\]\]

**tuple:**

tuple is a "immutable sequence type, which no allow the insert, update,

delete , but  allow indexing and slicing operations"

**in python , tuple can be created using following ways:**

1) using "()"

2) using tuple() constructor

**in python, tuple can be:**

1) empty

2) can have duplicate elements

3) can have any type of data

4) can also have another tuple(nested or inner tuple) as data

**example:**

()

(1,2,3,4)

((1,2,3,4,5))

**3.string:**

in Python, string is used to store the any data inside the quotes,

string is immutable sequence type, which allow the indexing and

slicing , but never allow the any changes (on strings, we can not able

to perform operations like insert, update and delete operations)

**in python, string can be created using following ways:**

1)  using quotes

2)  using str() constructor

string can be "Empty"

string can have any type of data inside the quotes

string can also have "duplicate data"

**example:**

' hello '

"hello world"

**4. range():**

in python,  range() is used to "generate the values for given  start to

end-1"

in python range() function , we can able to generate "only integer

data"

in python range() function , we can able to apply the "indexing and

slicing"

in python range() function , can not allow the duplicate values or

range() function can not  generate the duplicate values, always

generate the unique values

**in python, range() function can be created using following syntax:**

```python
                     range(start, end, step)
```

in python ,

range() function always give the values from "start to end-1"

range() function can take "start" as "+ve or -ve or zero"

range() function  can take "end" as "+ve or  -ve or zero"

range() function can take "step" as "+ve or -ve" , never ve "Zero"

when we are not given any value for start, then the range() function

always takes by default start as "Zero"

when we are not given any value for step, then the range() function

always take  by default step as  "1"

but in the range() function , end value is compulsory  value

when we take  "step" value in the range() function as "positive" ,

then "start \< end", otherwise no output from the range()

when we take "step"  value in the range() function as "negative" ,

then "start \> end", otherwise no output from the range()

on range() function, we can able to apply the "both indexing and

slicing ", but no changes can be made on the range(), because it  is

immutable

in range() function ,

start refers where to start

end refers where to end

step refers  difference between two consecutive elements in

range

in range() function , we are given only one value, then range() function

consider it as "end" value

**example:**

range(1,5) ===\> range(1,5,1)  ===\> 1, 2, 3, 4

range(10) ===\>range(0,10,1) ==\> 0, 1, 2 , 3 , 4 , 5 , 6, 7 , 8, 9

range(1,10,4) ===\> 1 5 9

range(1,10,-3) ===\> no output

range(10,0,-4)  ===\> 10  6  2

range(5,5,2) ====\> no output

**what is need of indexing:**

indexing is used in python, to access the any data from the "sequence

type"

via indexing, we can able to access only "one element"

when we are given any wrong index,  to access any data from the

sequence type, python will raise an error called "Index Error"

**what is need of slicing:**

slicing is used in python, to access the "zero or more elements

from the given sequence type"

when we apply the slicing on the any sequence type, then the result

**also sequence type it means**

slicing on list , return "list as result"

slicing on tuple , return "tuple as result"

slicing on string, return "string as a result"

slicing on range(), return "range() as a result"

when we doing slicing on "any sequence type" with wrong indexing ,

python never given any  index error

**set type:**

set type is used to "store the group of values, but set type always can

store only unique values"

in python, set type  is called as "non-sequence type" , because on

set type we can able to apply the "indexing and slicing"

in python , set type is also called as "un-ordered collection" , because

sets does not  store the  data in the given order always

**in python, we will have two types of sets:**

1)  set

in python, set is called as "mutable non-sequence type"

set allow the changes

when we want to create the set in python, we will use the following

**ways:**

1)  using "{}"

2)  using set() constructor

2) frozen set

in python, frozen set is called as "immutable non-sequence type"

frozen set   never allow the changes

when we want to create the frozen set in python, we will use a function

called "frozenset()"

in python, both frozen set and set , never allow the duplicates, indexing

, slicing

in python, only sets can allow the operations like insert, update, delete ,

union, intersection, difference, symmetric difference,..........., these all

are we can not apply on "frozen set"

**map type:**

when we want to store the data as a key and value pair, in python we

will use "map type"

in python, "dictionary" is represents "map" data type

in dictionary , the data is in the form "key and value" pairs

in dictionary,  we can able to have any number of keys, but keys never

be  duplicate , but values can be duplicate

in dictionary, we can have any type of data as " value", but key can

either numeric  or character type

in python, when we want to create the dictionary, we will use the

following ways:

1)  using "{}"

2)  using "dict()" constructor

**example:**

{1:2,3:4,5:6,7:8}

in the above , before colon all are keys ,  1,3,5,7

in the above, after colon all are values,  2,4,6,8

in python , dictionary is mutable type (it means , dictionary can allow

the changes)

in python, dictionary is non-sequence type( it means , no indexing and

slicing)

in python, dictionary , keys are act like a "indexes", to access the data

or values of the dictionary

**binary type:**

in python, we can represent binary information in the following   ways,

if the data is number, then the number we represent in the binary

using a prefix called "0b or oB"

if the data is other than , then the data can represent  in the binary

using "b-string or B-string"

syntax:

b" write the data here"

or

B "write the data here"

in python, to represent the data as binary (not number), we will use

**the following functions:**

1. bytes()

2. bytearray()

3. memoryview()

both bytes and bytearray will also allow the "both indexing and

slicing"

in python, bytes is immutable and bytearray is mutable

**None type:**

when we want to represent the any data as  "no value or no data or

nothing  or empty value or null value", in python we are this data type

to store none type value, python given a keyword called "None"

---

## Input and Output Statements

when we want to give the any input to program while execution by

processor, we will give using "input statement"

any input in python we are given using "input()" function

**syntax:**

```python
input("write the prompt here")
```

**example:**

```python
a=input("a:")
```

when we give the any input using input() function , input() always

takes any input in the form of string, to avoid this when we want to

take the given data exactly in given format, for this we are using

a process called  "Type conversion"

**in python, we will have two types of type conversion:**

1)  implicit type conversion

this type conversion will be performed automatically by

```python
        python(PVM)
```

2)  explicit type conversion

this type conversion will performed by programmer or developer

to perform the type conversions, we will use the following  important

**functions:**

```python
from                                       to                                      function
```

\====                                      =====                              ==========

integer                                  string                                  str()

float                                       string                                  str()

complex                               string                                   str()

Boolean                               string                                    str()

string                                    integer                                 int()

complex                              integer                                 not possible

Boolean                               integer                                 int()

float                                      integer                                int()

string                                    float                                    float()

integer                                 float                                    float()

Boolean                               float                                    float()

complex                              float                                   not possible

string                                   Boolean                             bool()

integer                                Boolean                              bool()

float                                     Boolean                              bool()

complex                              Boolean                               bool()

string                                   complex                            complex()

integer                                 complex                           complex()

float                                      complex                           complex()

Boolean                                complex                          complex()

**output statement:**

when we want to display the any result of the program after execution

or while execution , in python we will use "output statement"

in python, we are using to display any output of the program, using

a function called "print()"

syntax:

```python
   print(val1, val2, val2, val4,.........valn, sep=" ", end=" ")
```

**note:**

in python,

using  print() function, we can able to display the any numbers of

values,

while displaying the multiple values using print() function , how the

multiple values can be displayed  by print() function , defined using

"sep"

the default value of the sep is "space"

when want to display the any output using print(), on what line (  on

same line or new line) , can defined in  the print() function using "end"

the default value of the end is "new line" (\\n) , it means by default

every print() function  output can be visible in a new line

**example:**

```python
print(10)
print(20)
print(30)
```

**output:**

10  
20  
30

**example:**

```python
print(10,end=",")
print(20,end=",")
print(30,end=",")
```

**output:**

10,20,30,

**example:**

```python
print(10,20,30,40,sep="*")
```

**output:**

```python
print(10,20,30,40,sep="*")
```

**example:**

```python
print(10)
print(10,20,end="")
print(20,30,40)
print(20,30,40,sep="\n")
```

---

## Python Variables

variable means "named memory location" and using this we can able

to store a value or data in the memory with some name

the value or data of the variable can able to change any where in the

program

when we want to create the variable in python , we will use the

following syntax:

```python
                 variable_name=value
```

in python,

we can able to store the multiple values into  multiple variables at

a time

syntax:

```python
            var1, var2, var3,....varn=val1, val2, val3,...valn
```

we can able to store the same value for multiple variables  at a time

using following syntax:

```python
                    var1=var2=var3=var4=.....=value
```

we can able to store the  multiple values under single variable

syntax:

```python
             variable_name=val1,val2,val3,......valn
```

when we store the multiple values under one single name or variable,

then the we say it is  "packing" in python and all values stored under

variable as "tuple" form

**example:**

```python
a,b,c=10,20,30
print(a,b,c)
a=b=c=100
print(a,b,c)
a=10,20,30,40,50,60 #packing
print(a)
```

**example:**

```python
a=10,
print(a)
print(type(a))
a=(10,)
print(a)
print(type(a))
```

---

## Python Operators

operator is a  "symbol" and which is to perform operation on

"operands"

operand means "data"

example:

10+20  ===\> 30  where a, b are "operands" , + is operator

**in python, we will have the following operators:**

**1)  arithmetic  operator :**

arithmetic operator is used to perform "arithmetic operations"

(addition, subtraction, multiplication, division, exponent)

in python, we will use the following symbols to perform  a specific

operation:

symbol                        meaning

\+                                    addition

\-                                      subtraction

\*                                    multiplication

/                                      true division or real division

//                                    floor division

%                                    modulo division

\*\*                                  exponent

when we use "/" for  given operands, it always gives "quotient" as

a  float value as result

when we  use "//" for given operands, it always gives "quotient" as

integer value  as result

when we use "%" for given operands , it always gives "remainder"

as result

when we are working with "%",

if n1%n2 (n1\<n2), then the result is "n1"

if n1%n2(n1\>n2) , then the result is "actual remainder after the division"

**example:**

```python
a=int(input("a:"))#10
b=int(input("b:"))#20
print(a+b)#30
print(a-b) # -10
print(a*b)#200
print(a/b) # 0.5
print(a//b)#0
print(a**3)
```

**2) relational operator:**

relational operator is also called as "comparison operator"

when we want to compare the any two values, in python we will use

this operator

in python, relational operators will return result always "Boolean" , it

mean "either True or False"

**in python, we will have the following  comparison operators:**

1) \>

2) \<

3)\>= (greater than or equal to)

4) \<=

5) ==

6) !=(not equal to)

**example:**

```python
a=int(input("a:"))
b=int(input("b:"))
print(a>b)
print(a<b)
print(a>=b)
print(a<=b)
print(a==b)
print(a!=b)
```

**example:**

```python
a=int(input("a:"))#8
b=int(input("b:"))#9
print(a>b>a<b)
print(a<b<a)
print(b>a>b)
```

in above example, we are doing "Chained comparison", chained

comparison means "checking more than two values a time using

relational operators"

**3)  logical operator:**

logical operator is used to "Compare the any two conditions"

in python, logical operator, will return result always as "Boolean"

**in python, we have the following logical operators:**

**1) or   \<=== logical or**

in the case of  "logical or",  if any one condition is "true", then the

entire result is "True"

**2) and  \<=== logical and**

in the case of  "logical and",  if any one condition is "false", then the

entire result is "false"

**3 ) not  \<=== logical not:**

in the case of  logical not,

if the result is "true", then the logical not will return "False"

if the result is "False", then the logical not will return "True"

**example:**

```python
a=int(input("a:"))#8
b=int(input("b:"))#9
print((a>b) or (a<b))
print((a>b) and (a<b))
print(not(a>b))
```

**note:**

in python, both logical-or and logical-and will also  called as "short-

circuit  operators"

when we are working with  multiple conditions using "logical or" , if

any one condition is True, then the logical  or  will give result  as True

without checking  the remaining conditions " due to  short-circuit

behaviour

when we are working with  multiple conditions using "logical and" , if

any one condition is False, then the logical -and  will give result  as False

without checking  the remaining conditions " due to  short-circuit

behaviour

**example:**

```python
a=10
b=20
c=30
print(a or b or c)
print(a+b and b+c and c+a)
print(a or b and c)
```

**output:**

10  
40  
10

when we want to convert the any data into Boolean , in python ,

we should remember the following:

**following data always "True"**

any number other than zero,  any list with  data, any tuple with

data, any set with data, any dictionary with data, any range() with

data, any string with data

**following data always "False"**

zero, None, empty list  \| tuple  \| set \| dictionary \| range() \| string

**4) assignment operator:**

when we want to assign the any value to the variable in python , we

will use "Assignment operator"

symbol:

"="

in python, using assignment operator , we can able to perform

"compound" operation , compound operation refers "doing more than

one operation at a time is called as compound operation"

**example:**

```python
a=10
a+=(a*10) #a=a+(a*10)
print(a)#110
a*=100#a=a*100=110*100=11000
print(a)
a//=1000
print(a)
```

**5)  membership operator:**

when we want to check the "given data" is present or not  in the given

iterable, in python, we will use "membership operators"

**in python, iterables are following:**

1)  list

2)  tuple

3)  string

4)  set

5)  range()

6)  dictionary .....................

**in python, the following are membership operators:**

1) in  ( in is used "to check given data is present or not in the iterable")

if the data is present, in operator will return "True" as result

if the data is not present , in operator will return "False" as result

2) not in (not in is used to "check the given data is not present or not

in the given iterable)

if the data is not present, not in operator will return "True" as result

if the data is present , not in operator will return "False" as result

**example:**

```python
print("1" in "1234")
print(" " in "1234")
print("" in "1234")
print(1 in [1,2,3,4,5])
print("abc" in [1,23,4,5,6,7])
print("a" in (10,20,30,40))
print(100 not in (10,20,30,40,50))
```

**output:**

True  
False  
True  
True  
False  
False  
True

**6)  identity operator :**

in python, we will use "identity operator" to compare the given objects

are reside at "Same" memory location or not

when we compare the two objects (values) same or not, in python we

will use "==" operator, when we want to compare objects reside at

same memory location or not, we will use "identity operator"

**in python , identity operators are two types:**

1) is

2) is not

in python, memory management will taken care by "PVM" while

program execution , memory management is done automatically by

PVM  while program execution , in python memory management will

not taken care by "Programmer or developer"

memory management refers "  Memory allocation and Memory De-

allocation"

Memory allocation refers "giving the memory for python objects"

Memory de-allocation refers "removing the objects and re-assign

memory for new objects"

in PVM, we will have a program called "Python Memory Manager"  and

which is responsible for "Memory allocation"

while memory allocation, PVM will divide the "RAM" logically into

two components:

1)  Heap Area  or Private Heap Area

in this, we are going to store the actual objects (values)

in this, we are going to store the one object only once , but

one object can have multiple references in the stack area

2)  Stack Area

in this, we are going to store the "all objects references(name)"

in stack area , we multiple references can able to refer same object

in the Heap Area

if two references refer "Same" object , then their memory address also

same.

if two references refers "Different" objects, then their memory

address is also different.

**in python, we will have the following identity operators:**

1)   is  operator

using this operator ,

when the two objects are same, then the their memory location is also

same, then this operator will return "result"  True, otherwise False

2)  is not operator

using this operator ,

when the two objects are different, then the their memory location is

also different, then this operator will return "result"  True, otherwise

False

in python, identity operator will return "result" as Boolean (True or

False)

in Python, when we want to know the "Memory address" of the given

object , we will use a function called "id()"

**example:**

```python
a=10
b=20
c=30
d=a+b
f=a
g=b
print(id(a))
print(id(f))
print(id(b))
print(id(g))
print(id(c))
print(id(d))
```

**output:**

140728502883400  
140728502883400  
140728502883720  
140728502883720  
140728502884040  
140728502884040

**example:**

```python
a=10
b=20
c=30
d=a+b
f=a
g=b
print(a is b)
print(a is f)
print(a is not c)
print(b is not g)
print(d is c)
```

**output:**

False  
True  
True  
False  
True

**7)  conditional operator or ternary operator:**

when we want to perform the any operation based on condition  in

python, we will use conditional operator

syntax:

expression   if condition else expression

when the condition is "True", the code what we write before the "if"

will be executed

when the condition is "False", the code what we write after the "Else"

will be executed

**example:**

```python
a=10
b=20
res=(a+b) if a<b else a*b
print(res)
res=(a*b) if b>a else a+b
print(res)
print(a) if a>b else print(b)
```

**output:**

30  
200  
20

**8) walrus operator:**

when we want to perform the  "Assignment", "operation" and

"comparison" at a time, in python, we will use "walrus" operator

symbol:

" := "

**example:**

```python
a=10
print(a) if (a:=a*10+10)<=100 else print(100)
print(a)
```

**output:**

100

110

**example:**

```python
a=10
print(a) if (a:=a*10+10<=100) else print(100)
print(a)
```

**output:**

100  
False

**9) bitwise operator:**

when we want to perform the operation on the binary data of the

given data , then in python we are use "bitwise operators"

data ===\> binary ===\> bitwise ===\> binary ===\> data

in python , bitwise operators are also called as "binary operators"

**in python, we will have the following bitwise operators:**

1) bitwise or

symbol:  \|

in the case of bitwise-or , if any one input is  "1" , then the result is "1",

otherwise "0"

2) bitwise and

symbol:  \|

in the case of bitwise-and , if any one input is  "o" , then the result is

"o", otherwise "1"

3) bitwise ex-or

symbol:  ^

if both inputs are same, then the result is "0"

if both inputs are different, then the result is "1"

4) bitwise left shift

symbol: \<\<

formula:

n\<\<s ===\> n\* 2 power s

5) bitwise right shift

symbol: \>\>

formula:

n\>\>s ===\> n//2 power s

6) bitwise one's complement

symbol: ~

formula:

\~n ===\>  -(n+1)

**example:**

```python
a=43
b=24
print(a|b)
print(a&b)
print(a^b)
```

**output:**

59  
8  
51

**example:**

```python
a=59
b=63
print(a|b)
print(a&b)
print(a^b)
```

**output:**

63  
59  
4

**example:**

```python
a=4
b=3
print(a<<b)#4*2 power 3==> 32
print(a>>b)#4//2 power 3 ==> 0
print(~a)# -5
print(~b)# -4
```

---

## Practice Programs on Operators

write the  programs for the following  questions without using built-in

**functions, conditional statements and looping statements:**

1. find the remainder of the given two numbers without using "%"

**operator**

**code:**

```python
"""
find the remainder of the given two numbers
"""
num1=int(input("num1:"))
num2=int(input("num2:"))
print(num1) if num1<num2 else print(num1-(num2)*(num1//num2))
```

**2. find the maximum number of the given three numbers:**

**code:**

```python
"""
find the maximum number of the given three numbers
"""
a=int(input("a:"))
b=int(input("b:"))
c=int(input("c:"))
print(a) if a>b and a>c else print(b) if b>c else print(c)
```

3.check given number is even or odd without using relational operators:

**code:**

```python
"""check given number is even or odd
"""
a=int(input("a:"))
print("odd") if a%2 else print("even")
```

**4. check given number is perfect square or not:**

```python
"""check given number is perfect sqaure or not
"""
a=int(input("a:"))
res=((a)**(0.5))
print("perfect square") if a==res**2 else print("not perfect square")
```

5. write a python program to   remove the all duplicate elements of

**the given list:**

**code:**

```python
"""
remove the all duplicate elements of the given list
"""
l1=[1,2,3,4,5,2,3,4]
print([*{*l1}])
```

in python, \* is used to un-pack the elements of the given iterable

**code:**

```python
l1=[1,2,3,4]
print((*l1,))
l1="hello"
print([*l1])
```

**6. find the common elements of the given two lists:**

```python
l1=[1,2,3,4]

l2=[2,3,4]
```

output:

\[2,3,4\]

**code:**

```python
l1=[1,2,3,4]
l2=[2,3,4]
print([*{*l1}&{*l2}])
```

7. find the given two lists unique elements and result never contain

**common elements of the given two lists:**

```python
l1=[1,2,3,4]

l2=[2,3,4,10,20,30]
```

\[1,10,20,30\]

**code:**

```python
l1=[1,2,3,4]
l2=[2,3,4,10,20,30]
print([*{*l1}^{*l2}])
print([*{*l1}-{*l2}|{*l2}-{*l1}])
```

8. print the all even numbers from the given start to end

start:1

end: 20

2,4,6,8,10,12,14,16,18

**code:**

```sql
start=int(input("start:"))
end=int(input("end:"))
start=start if start%2==0 else start+1
print(*range(start,end,2),sep=",")
```

9. write a python program to add the given two number without using

**"+" operator:**

**code:**

```python
a=int(input("a:"))
b=int(input("b:"))
print(a-(-b))
```

**10.check given number contain prime digits or not :**

123 ===\>  yes

468 ===\> no

**code:**

```python
num=int(input("number:"))
#convert the num into string using f-string
num=f'{num}'
print("yes") if "2" in num or "3" in num or "5" in num or "7" in num else print("no")
```

**11.check given number contains all are same digits are not:**

111 ===\> yes

121 ===\>no

**code:**

```python
n=int(input("n:"))
print("yes") if {*f'{n%10}'}=={*f'{n}'} else print("no")
```

12. remove the all vowels of the given string, where order is not

**important , print the result as string only:**

abcd ===\> bcd

acedf ==\> cdf

**code:**

```python
string=input("string:")
string={*string}-{'a','e','i','o','u','A','E','I','O','U'}
print(*string,sep="")
```

13.check given strings are anagrams or not(where string lengths are not

**important):**

```python
s1="abc"

s2="bca"
```

**code:**

```python
s1=input("string1:")
s2=input("String2:")
print("anagram") if {*s1}=={*s2} else print("not anagram")
```

14. print the count of the how many even numbers in the given  range,

in the result , we need to print the "how many even numbers" we have

```python
for given range:
```

start: 1

end: 15

2,4,6,8,10,12,14  ===\> 7

**code:**

```sql
start=int(input("start:"))
end=int(input("end:"))
start=start if start%2==0 else start+1
end=end if end%2==0 else end-1
print(((end-start)//2)+1)
```

---

## Overloaded Operators

in python, when we use any operator more than once doing any

operation , then the operator is called as "overloaded operator"

**in python, the following are overloaded operators:**

1) "+"

addition of two numbers

merge the given two lists or tuples or strings

**example:**

```python
print(10+20)
print([1,2,3]+[4,5,6])
print((1,2,3)+(10,20,30))
```

**output:**

30  
\[1, 2, 3, 4, 5, 6\]  
(1, 2, 3, 10, 20, 30)

2."-"

using this we can able to perform "subtraction of given two

numbers"

using this, we can able to perform the " difference of two sets "

**example:**

```python
print(10-20)
print({1,2,3,4}-{4,5,6,7})
```

3. "\*"

using "\*", we can able to perform the multiplication of two

numbers

using "\*", we can able to un-pack the any given iterable

using "\*" , we can able to perform "repetition of the given iterable"

**example:**

```python
print(1*2)
print(*range(1,10))
print(*[1,2,3,4])
print(*"hello")
print([*{1,2,3,4,5}])
print(*{1:2,3:4,5:6})#it just give only keys, not values
print([1,2,3]*2)
print((1,2,3)*4)
print("abc"*5)
```

4. "\*\*"

using this operator, we can find the power of the given number

using this operator, copy the dictionary data

**example:**

```python
print(2**3)
a1={1:2,3:4,5:6,7:8}
print(*a1)
print({**a1})
```

5."\|"

using this we can able perform the "bitwise or"

using this, we can able to combine the two sets or dictionaries

**example:**

```python
print(10|20)
print({1,2,3,4}|{4,5,6,7})
print({1:2,3:4,4:6}|{4:5,6:7,8:9,1:3})
```

6. "^"

using this operator, we can able  perform "bitwise ex-or" operation

using this operator, we can able to perform "Symmetric difference"

**example:**

```python
print(10^20)
print({1,2,3,4}^{2,3,4,5,6,7,8})
```

7. "&"

using this , we can able find the "bitwise and" of the given

numbers

using this, we can able to find the "intersection of two sets"

**example:**

```python
print(10&20)
print({1,2,3,4}&{2,3,4,5,6,7,8})
```

8."=="

using this operator, we can able to compare the given two

numbers, two lists, two tuples , to sets, .... are same or not

when we comparing  the "lists or tuples or strings" , the order  is

very important

**example:**

```python
print(10==20)
print([1,2,3]==[3,2,1])
print([1,2,3]==[1,3,2])
print([1,2,3]==[1,2,3])
print("abc"=="bca")
print({1,2,3}=={3,2,1})
```

**output:**

False  
False  
False  
True  
False  
True

9. "\>"

using this operator, we can compare the given number is more

than another number or not

using this operator, we can check given set is super set or not

**example:**

```python
print(10>20)
print(20>10)
print({1,2,3,4}>{1,2,3,4})
```

**output:**

False  
True  
False

10. "\<"

using this operator, we can compare the given number is less

than another number or not

using this operator, we can check given set is sub set or not

**example:**

```python
print(10<20)
print(20<10)
print({1,2,3,4}<{1,2,3,4,5})
print({1,2,3,4}<{1,2,3,5})
```

**output:**

True  
False  
True  
False

in python, using "\>" and "\<", we can able to compare the strings

**example:**

```python
print("abc">"aca")
print("aca">"abc")
print("a">"b")
print("a"<"b")
print("abc"<"aca")
print("abc"<"a")
```

**output:**

False  
True  
False  
True  
True  
False

in python, using "\>" and "\<", we can able to compare the lists and tuples

**example:**

```python
print([1,2,3]>[3,4,5])
print([3,1,2]>[1,2,3])
print([3,1,2]>[4,-1,-2])
print((1,2,3)>(4,5,6))
print((4,5,6)>(1,2,3))
```

**output:**

False  
True  
False  
False  
True

---

## Conditional Statements

when we want to execute the any logic, based on the condition , in

python, we will use the "conditional statements"

in python, conditional operator, we can able to execute only statement

at a time based on the condition , but in the conditional statements we

can able to write the any number of "statements"

**in python, we will have the following conditional statements:**

1) simple if statement

2) if-else statement

3) else-if ladder

4) match case statement

5) nested conditional statement

**simple if statement:**

when we want to execute the  "any logic" based on the condition,

in python we will use  simple if statement

syntax:

```python
          if condition:

               #write the logic here
```

any logic what we write under the "if" will be executed only when the

condition is "True", if the condition  is "False", the logic under the "if"

will not be executed

simple if statement  will works only  for "true" part , it means when

the condition  is True, then when we want to execute any logic  in

python we will use "Simple if"  statement

**example:**

```python
a=1000
if a>100:
   print(a)
   print("the value of a is more than 100")
```

**if-else:**

when we want to execute the logic  for both "True and False" , in

python we will use "if-else"

when the condition  is "True", the logic under the  "if" will be executed

when the condition  is "False", the logic under the "else" will be

executed

syntax:

```python
           if condition:

                  #write the logic  here
          else:

                   #write the logic here
```

**example:**

```python
a=1
if a>100:
   print(a)
   print("the value of a is more than 100")
else:
    print(a)
    print("the value of a is less than 100")
```

**output:**

1  
the value of a is less than 100

in python,

we can able to write the "if" without "else"

we can not able to write the "else" without "if"

we can not write the "any condition for else", because else will execute

by default , the condition what we taken for "if" is "false"

**else-if ladder:**

using this we can able execute the logic  based condition wise , in

this we can able take three or more conditions

when we want execute the a particular logic based on a particular

condition , in python we are going to "else-if" ladder

in python, else-if ladder always starts with "if" , followed by multiple

"elif" conditions, for else-if ladder, we can able to write the else also

but, for else-if ladder else always we write at the end and it is optional

for "else-if ladder"

syntax:

```python
if   condition :
     #write the logic here
elif condition:
    #write the logic here
elif condition:
    #write the logic here
elif condition:
 #write the logic here
.
.
else:
  #write the logic here
```

**example:**

```python
a=int(input("a:"))#10
b=int(input("b:"))#20
c=int(input("c:"))#30
if a>b and a>c:
    print("a is maximum!")
elif b>c:
    print("b is maximum!")
else:
    print("c is maximum!")
```

**match case statement:**

match case statement in python as similar to "switch case statement"

in C, C++, JavaScript

when we want to execute the "any logic" based on the given choice

value or case value, instead of condition, in python we are going to

use "match case statement"

in real-time, we are using "match case statement" for "Menu Driven

programs"

syntax:

```python
match choice:

   case  value1:

                    #write the logic

    case value2:

                #write the logic here

    case value3:

               #write the logic here

     .
     .
     .

     case valuen:

             #write the logic here

     case _:   <==== default case

             #write the logic here
```

when we are working with match case statement, any logic what we

write under the "match case statement"  will executed, based on

the give choice , which case value is matches with "choice value", that

case logic will be executed

if given choice value is not matches with any case value, then match

case statement  uses a case called "Default" case statement , this is

always we write end of the all cases  and this will write using following

syntax:

```python
            case _:
```

write the logic

**example:**

```python
choice=int(input("choice:"))
match choice:
    case 1:
         print("you given choice-1")
    case 2:
         print("you given choice-2")
    case 3:
         print("you given choice-3")
    case 4:
         print("you given choice-4")
    case _:
        print("Invalid Choice!")
```

**nested conditional statements:**

in python, we can able to write the "conditional statements inside

the another conditional statements"

when we write the conditional statement inside the another conditional

statement , then the conditional what write under the another

conditional statement is called "inner or nested conditional statement"

nested conditional statements are used "for branching".

when we  want execute the any logic  based on multiple conditions

and each  condition need check one after another, then we are going to

use nested conditional statements

syntax:

```python
if condition:

         if condition:

                        if condition:

                        else:

        else:

else:

        if condition :

        else:

                       if condition :
```

**example:**

```python
age=int(input("age:"))
if age>21:
    if age>21 and age<=30:
        print("please enjoy the bachelors Life!")
    elif age>30 and age<=40:
        print("right age, consult exprets!")
    elif age>40 and age<=50:
        print("you already in Heaven, pleae continue!")
    elif age>50 and age<=60:
        print("you already ready to hit bucket!")
    else:
       print("RIP!")
else:
    print("this is not a PUBG!")
```

---

## Looping Statements

looping statements are also called as "iterative statements"

when we want to execute the any logic for any number of times

until the condition is become False, in python we are going to use

"looping statements"  or "Iterative statements"

**in python, we will the following looping statements:**

1)  While Loop

2) For Loop

in python, we do not have "do-while" loop

conditional statement  will execute any logic only once based on

condition (either True or False)

looping statement  can execute the logic for "n" number of times

based on the condition

when we want to create the loop based on the "Condition", in python

we are going to use "While loop" , that is reason "While" loop is

also called as "conditional based loop"

**syntax for while loop:**

```python
while condition:

        #write the logic here
```

when we create the any while loop in python program, the while loop

execution start and end at "condition" only , if the condition is "true" ,

then loop is always executed , if the condition  is  "false", then the

loop terminates it's execution

in python, inside the while loop , we can also can able to create the

another while loop, the while loop what we create inside the another

while loop is called  as "nested while loop or inner while loop"

when the inner while loop is executing , the outer while loop pause

it's execution  and once inner while loop done it's execution , outer

while resume it's execution

**example:**

```python
a=1
while a<=5:
    print(a)
    a+=1
```

**output:**

1  
2  
3  
4  
5

**example:**

```python
a,b,count=1,1,0
while a<=5:
    while b<=5:
        count+=20
        b+=1
    a+=1
    count+=10
print(count)
```

**example:**

```python
a,b,c,count=1,1,1,0
while a<=5:
    while b<=5:
        while c<=5:
            count+=40
            c+=1
        count+=30
        b+=1
    a+=1
    count+=10
print(count)
```

**example:**

```python
a,b,c,count=1,1,1,0
while a<=5:
    while b<=5:
        while c<=5:
            c+=1
            count+=25
        c=1
        b+=1
        count+=25
    a+=1
    b,c=1,1
    count+=35
print(count)
```

**example:**

```python
a,b,c,d,count=1,1,1,1,0
while a<=6:
    while b<=4:
        while c<=5:
            while d<=4:
                d+=1
                count+=20
            c+=1
            count+=30
        b+=1
        count+=20
    a+=1
    b,c,d=1,1,1
    count+=40
print(count)
```

**example:**

```python
a,b,c,count=1,1,1,0
while a<=3:
    while b<=3:
        while c<=3:
            c+=1
            count+=20
        b+=1
        count+=40
    a+=1
    count+=50
    b,c=1,1
print(count)
```

**example:**

```python
a,b,c,d,count=1,1,1,1,0
while a<=6:
    while b<=4:
        while c<=5:
            while d<=4:
                d+=1
                count+=20
            c+=1
            count+=30
            d=1
        b+=1
        count+=20
        c=1
    a+=1
    b,c,d=1,1,1
    count+=40
print(count)
```

when we want to create the loop for given iterable (list or tuple or

string or range() or set or dictionary), in python we are going to use

"for loop" , because for loop is also called as "itetable-based loop"

syntax:

```python
      for variable_name in iterable_name:

                      #write the logic here
```

**example-1:**

```python
l1=[1,2,3,4,5,6,7,8,9,10]
for i in l1:
    print(i)
```

**output:**

1  
2  
3  
4  
5  
6  
7  
8  
9  
10

**example-2:**

```python
l1=(1,2,3,4,5,6,7,8,9,10)
for i in l1:
    print(i)
```

**output:**

1  
2  
3  
4  
5  
6  
7  
8  
9  
10

**example:**

```python
l1="hello world"
for i in l1:
    print(i)
```

**output:**

h  
e  
l  
l  
o

w  
o  
r  
l  
d

**example:**

```python
l1={1,2,3,4,5,6,7,8,9,10}
for i in l1:
    print(i)
```

**output:**

1  
2  
3  
4  
5  
6  
7  
8  
9  
10

**example:**

```python
l1={1:2,3:4,5:6,7:8,9:10}
for key in l1:
    print(key)
```

**output:**

1  
3  
5  
7  
9

when we want to access the any key from the "dictionary", we can able

to  use following syntax:

dictionary\_name\[key\_name\]

**example:**

```python
l1={1:2,3:4,5:6,7:8,9:10}
for key in l1:
    print(key,":",l1[key])
```

**example:**

```python
for i in range(1,10):
    print(i)
```

output:  
1  
2  
3  
4  
5  
6  
7  
8  
9

**example:**

```python
for i in range(1,10):
    print(i)
    i+=1
```

**output:**

1  
2  
3  
4  
5  
6  
7  
8  
9

---

## Programs on Strings and Lists (Without Built-in Functions)

1. write a python program to print the length of the given string ,

**without using any built-in function:**

input:   hello

output : 5

**code:**

```python
s1=input("String:")
length=0
```

for \_ in s1: length+=1

```python
print(length)
```

2. write a python program remove the vowels of the from the given

**string , print the result again as string, without using built-in function:**

input: abcd efgh

output: bcd fgh

**code:**

```python
s1=input("String:")#abcd
for i in s1: #abcd
    if i not in "aeiouAEIOU":
        print(i,end="")#bcd
```

3. write a python program print the maximum number in the given

**list:**

input: \[1,2,3,4,5,6\]

output: 6

**code:**

```python
l1=[-1,-2,-3,-4,-5]
maximum=l1[0]  # 1 (first element)
for i in l1:
    if maximum<i:
        maximum=i  #maximum=-1
print(maximum)
```

**4. find the minimum number in the list:**

```python
input=[1,2,3,4,5]
```

output: 1

**code:**

```python
l1=[-1,-2,-3,-4,-5]
minimum=l1[0]  # -1 (first element)
for i in l1:
    if minimum>i:
        minimum=i
print(minimum)
```

**5. find the maximum character in the string:**

input: abcd

output: d

**code:**

```python
l1=input("string:")
maximum=l1[0]
for i in l1:
    if maximum<i:
        maximum=i
print(maximum)
```

**6. find the minimum character in the given string:**

**code:**

```python
l1=input("string:")
minimum=l1[0]
for i in l1:
    if minimum>i:
        minimum=i
print(minimum)
```

7.write a python program to print the second maximum number of

**the given list, without using any built-in function:**

**code:**

```python
l1=[-1,-2,-3,0,4]
max1=max2=l1[0]
for i in l1: #i=4
    if max1<i: #4<15
        max2=max1 #max2=4
        max1=i #max1=15
    elif max1==max2:
        if max2>i:
           max2=i
print(max2)
```

8. write a python program to print the numbers which are having only

prime digits for given range:

start:1

end: 30

2  3  5  7  22 23 25 27

**code:**

```sql
start=int(input("start:"))
end=int(input("end:"))
for i in range(start,end+1):
    if not {*f'{i}'}-{'2','3','5','7'}:
        print(i)
```

---

## Programs on Numbers

**1)  write a python program to print the factors of the given number:**

**code:**

```python
num=int(input("num:"))#6
fact=1
while fact<=num:
    if num%fact==0:
        print(fact) #1 2 3 6
    fact+=1# fact=3
```

**2) count the number of factors of the given number:**

**code:**

```python
num=int(input("num:"))#6
fact,count=1,0
while fact<=num:
    if num%fact==0:
        count+=1
    fact+=1
print(count)
```

**3. check the given number is prime or not:**

**code:**

```python
num=int(input("num:"))#6
fact,count=1,0
while fact<=num:
    if num%fact==0:
        count+=1
    fact+=1
print("prime") if count==2 else print("not prime")
```

**4. check the given number is perfect number or not:**

**code:**

```python
num=int(input("num:"))#6
fact,sum=1,0
while fact<num:
    if num%fact==0:
        sum+=fact
    fact+=1
print("perfect") if sum==num else print("not perfect")
```

5. write a python program print the maximum  digit in the given

**number:**

**code:**

```python
num=int(input("num:"))#456
maximum=0 #maximum=0
while num!=0: #456!=0
    if maximum<num%10: # 6<4
        maximum=num%10 #maximum=6
    num//=10 #num=0
print(maximum)
```

6. write a python program to print the minimum digit of the given

**number:**

**code:**

```python
num=int(input("num:"))#456
minimum=9 #minimum=9
while num!=0: #0!=0
    if minimum>num%10: #5>4
        minimum=num%10 #minimum=4
    num//=10 #num=0
print(minimum)
```

**7. write a python to remove the all even digit of the given number:**

num: 1234

output:  13

**code:**

```python
num=int(input("num:"))
num=f'{num}'
for i in num:
    if i not in "02468":
        print(i,end="")
```

**8.check the given number is palindrome or not:**

num: 121

reverse: 121

**code:**

```python
num=int(input("num:"))#123
result=0
temp=num
while num!=0:
    result=(num%10)+result*10
    num//=10
```

if temp==result:print("palindrome")  
else:print("not paliendrome")

9. print the all combinations of the given 3-digit number, where the

number must be 3-digit number and where number never contain

duplicate digits and where the combination also never contain duplicate

**digit:**

number: 123

123  
132  
213  
231  
312  
321

**code:**

```python
num=int(input("num:"))#123
length=0
```

for i in f'{num}':length+=1

```python
if length==3:
    res=''
    ucount=0
    #unique digits count
    for i in f'{num}':
        if i not in res:
            res+=i
            ucount+=1
    if ucount==length:
        temp=num
        minimum,maximum=9,0
        while temp!=0:
            if maximum<temp%10: maximum=temp%10
            if minimum>temp%10: minimum=temp%10
            temp//=10
        minimum=(minimum)*(10**(length-1))
        maximum=(maximum+1)*(10**(length-1))
        for i in range(minimum,maximum):
            if {*f'{i}'}=={*f'{num}'}:
                print(i)
    else:
        print("given number contain duplicate digits")

else:
    print("given number is not valid 3-digit number")
```

**10. write a python program to find the given number length:**

number: 1234

length: 4

**code:**

```python
num=int(input("num:"))#123
length=0
```

for i in f'{num}':length+=1

```python
print(length)
```

11.print the all combinations of the given n-digit number, where number

never contain duplicate digits and where the combination also never

**contain duplicate digit:**

**code:**

```python
num=int(input("num:"))#123
length=0
```

for i in f'{num}':length+=1

```python
res=''
ucount=0
#unique digits count
for i in f'{num}':
    if i not in res:
        res+=i
        ucount+=1
if ucount==length:
    temp=num
    minimum,maximum=9,0
    while temp!=0:
        if maximum<temp%10: maximum=temp%10
        if minimum>temp%10: minimum=temp%10
        temp//=10
    minimum=(minimum)*(10**(length-1))
    maximum=(maximum+1)*(10**(length-1))
    for i in range(minimum,maximum):
        if {*f'{i}'}=={*f'{num}'}:
            print(i)
else:
    print("given number contain duplicate digits")
```

12.print the all combinations of the given n-digit number, where number

can contain duplicate digits and where the combination also can

**contain duplicate digit:**

**code:**

```python
num=int(input("num:"))#123
length=0
```

for i in f'{num}':length+=1

```python
temp=num
minimum,maximum=9,0
while temp!=0:
     if maximum<temp%10: maximum=temp%10
     if minimum>temp%10: minimum=temp%10
     temp//=10
minimum=(minimum)*(10**(length-1))
maximum=(maximum+1)*(10**(length-1))
for i in range(minimum,maximum):
     if {*f'{i}'}=={*f'{num}'}:
         print(i)
```

13. write a python program, to print the numbers for the given range,

**where number must contain digits in the increasing order:**

start: 120

end: 130

123, 124, 125, 126, 127,128,129

**code:**

```sql
start=int(input("start:"))
end=int(input("end:"))
while start<=end:
    #check the start having digits which are increasing order
    temp=start
    length=count=0
    digit=start%10
    temp=temp//10
    while temp!=0:
        if digit>temp%10:
            count+=1
        digit=temp%10
        temp=temp//10
        length+=1
    if length==count:
        print(start)
    start+=1
```

**14. write a python program to find the factorial of the given number:**

0! ===\> 1

1!===\> 1

4!===\> 24

**code:**

```python
num=int(input("num:"))
if num==1 or num==0:
    print(1)
elif num<0:
    print("number never be negative for factorial!")
else:
    fact=1
    while num!=0:
        fact=fact*num
        num-=1
    print(fact)
```

**15. check the given number is Armstrong number or not:**

**code:**

```python
num=int(input("num:"))
if num>=1 and num<=9:
    print("given number is armstrong")
else:
    length=0
    for i in f'{num}':length+=1
    sum=0
    temp=num
    while num!=0:
        sum=sum+(num%10)**length
        num//=10
    if sum==temp:
        print("armstrong")
    else:
        print("not a armstrong!")
```

**16. check the given number is "Strong number" or not:**

145 ===\> 1!+4!+5! ===\> 1+24+120===\>145

**code:**

```python
num=int(input("num:"))
temp=num
sum=0
while num!=0:
    digit=num%10
    fact=1
    #factorial of the each digit of the number
    while digit!=0:
        fact*=digit
        digit-=1
    sum+=fact
    num//=10
```

if sum==temp:print("Strong!")  
else:print("Not Strong!")

**17.find the gcd or hcf of the given two numbers:**

num1: 12

num2: 14

output:  2

**code:**

```python
num1=int(input("num1:"))
num2=int(input("num2:"))
```

if num1\>num2:num1,num2=num2,num1

```python
fact=num1
while fact!=0:
    if num1%fact==0 and num2%fact==0:
        print(fact)
        break
    fact-=1
```

**18. find the lcm of the given two numbers:**

**code:**

```python
num1=int(input("num1:"))
num2=int(input("num2:"))
```

if num1\>num2:num1,num2=num2,num1

```python
fact=num1
while fact!=0:
    if num1%fact==0 and num2%fact==0:
        print((num1*num2)//fact)
        break
    fact-=1
```

19.print the common digits of the given two numbers , as a number,

**where the duplicate digits are not allowed:**

num1: 123

num2: 234

output: 23

**code:**

```python
num1=int(input("num1:"))
num2=int(input("num2:"))
res=''
for digit in [*f'{num1}']:
    if digit in [*f'{num2}']:
        if digit not in res:res+=digit
print(res)
```

20. write a python program to print the highest common digit in the

**given two numbers:**

num1: 123

num2: 234

output: 3

**code:**

```python
num1=int(input("num1:"))
num2=int(input("num2:"))
maximum='0'
for digit in [*f'{num1}']:
    if digit in [*f'{num2}']:
        if maximum<digit:
            maximum=digit

print(maximum)
```

21. write a python program to check the given digit is present or not

**in the given number:**

number: 1234

digit: 3

output : found

number:12345

digit: 9

output:  not found

**code:**

```python
num=int(input("num:"))
digit=int(input("digit:"))
```

if f'{digit}' in f'{num}':print("found!")  
else:print("not found")

**23. print the prime numbers for the given range:**

start: 1

end: 20

2,3,5,7,11,13,17,19

**code:**

```sql
start=int(input("start:"))
end=int(input("end:"))
for num in range(start,end+1):
    count=0
    #this loop will find num of factors of the given number
    for fact in range(1,num+1):
        if num%fact==0:
            count+=1
    if count==2:
        print(num)
```

---

## Programs on Patterns

1\.  
1  
1 2  
1 2 3  
1 2 3 4  
1 2 3 4 5

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    #for each row data starts with 1
    data=1
    #print the columns for each row
    for colnum in range(1,rownum+1):
        print(data,end=" ")
        data+=1
    #for new line
    print()
or

rows=int(input("rows:"))
for rownum in range(1,rows+1):
    print(*range(1,rownum+1))
```

2\.

0  
2 4  
6 8 10  
12 14 16 18

**code:**

```python
rows=int(input("rows:"))
data=0
for rownum in range(1,rows+1):
    #print the columns for each row
    for colnum in range(1,rownum+1):
        print(data,end=" ")
        data+=2
    #for new line
    print()
```

3\.

1  
1 2  
1 1 3  
1 1 1 4  
1 1 1 1 5

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    #print the columns for each row
    for colnum in range(1,rownum+1):
        if rownum!=colnum:print(1,end=" ")
        else:print(rownum,end=" ")
    #for new line
    print()
```

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    print(*"1"*(rownum-1),rownum)
```

4\.

1 2 3 4 5  
1 2 3 4  
1 2 3  
1 2  
1

**code:**

```python
rows=int(input("rows:"))
cpr=rows
for rownum in range(1,rows+1):
    #for each row data starts with 1
    data=1
    #print the columns for each row
    for colnum in range(1,cpr+1):
        print(data,end=" ")
        data+=1
    #for new line
    print()
    cpr-=1
```

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    print(*range(1,(rows-rownum+1)+1))
```

or

**code:**

```python
rows=int(input("rows:"))
cpr=rows
for rownum in range(1,rows+1):
    print(*range(1,cpr+1))
    cpr-=1
```

5\.

5 4 3 2 1  
4 3 2 1  
3 2 1  
2 1  
1

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    print(*range(rows-rownum+1,0,-1))

or

rows=int(input("rows:"))
cpr=rows
for rownum in range(1,rows+1):
    data=cpr
    for colnum in range(1,cpr+1):
        print(data,end=" ")
        data-=1
    print()
    cpr-=1
```

6\.

\*  
\* \*  
\* \* \*  
\* \* \* \*  
\* \* \* \* \*

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    print("* "*rownum)

or

rows=int(input("rows:"))
for rownum in range(1,rows+1):
    for colnum in range(1,rownum+1):
        print("*",end=" ")
    print()
```

7\.

\* \* \* \* \*  
\* \* \* \*  
\* \* \*  
\* \*  
\*

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    print("* "*(rows-rownum+1))
```

or

**code:**

```python
rows=int(input("rows:"))
cpr=rows
for rownum in range(1,rows+1):
    for colnum in range(1,cpr+1):
         print("*",end=" ")
    print()
    cpr-=1
```

8\.

\*  
\*  \*  
\*  \*  \*  
\*  \*  \*  \*  
\*  \*  \*  \*  \*

**code:**

```python
rows=int(input("rows:"))
cpr=rows
for rownum in range(1,rows+1):
    print(" "*(rows-rownum)+"* "*rownum)

or

rows=int(input("rows:"))
for rownum in range(1,rows+1):
    #spaces
    print(" "*(rows-rownum),end="")
    #stars
    print("* "*rownum)
```

9\)

\*  \*  \*  \*  \*  
\*  \*  \*  \*  
\*  \*  \*  
\*  \*  
\*

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    #spaces
    print(" "*(rownum-1),end="")
    #stars
    print("* "*(rows-rownum+1))
```

10\.

1   2   3  4  5  
1  2  3  4  
1  2  3  
1  2  
1

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    #spaces
    print(" "*(rownum-1),end="")
    #stars
    print(*range(1,(rows-rownum+1)+1))
```

11\.

1  
1  2  
1  2  3  
1  2  3  4  
1  2  3  4  5

code:

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    #spaces
    print(" "*(rownum-1),end="")
    #stars
    print(*range(1,(rows-rownum+1)+1))
```

12\.  
1  
1 2  
1 2 3  
1 2 3 4  
1 2 3 4 5  
1 2 3 4  
1 2 3  
1 2  
1

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows*2):
    if rownum<=rows:#rownum=1,2,3,4...rows
        print(*range(1,rownum+1))
    else:
        print(*range(1,(rows-(rownum-rows))+1))
```

13\.

\*  
\* \*  
\* \* \*  
\* \* \* \*  
\* \* \* \* \*  
\* \* \* \*  
\* \* \*  
\* \*  
\*

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows*2):
    if rownum<=rows:#rownum=1,2,3,4...rows
        print("* "*rownum)
    else:
        print("* "*(rows-(rownum-rows)))
```

14\.

1  
1  2  
1  2  3  
1  2  3  4  
1  2  3 4 5  
1  2  3  4  
1  2  3  
1  2  
1

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows*2):
    if rownum<=rows:#rownum=1,2,3,4...rows
        print(" "*(rows-rownum),*range(1,rownum+1))
    else:
        print(" "*(rownum-rows),*range(1,(rows-(rownum-rows))+1))
```

15\.

\*  
\*  \*  
\*  \*  \*  
\*  \*  \*  \*  
\*  \*  \*  \*  \*  
\*  \*  \*  \*  
\*  \*  \*  
\*  \*  
\*  
code:

```python
rows=int(input("rows:"))
for rownum in range(1,rows*2):
    if rownum<=rows:#rownum=1,2,3,4...rows
        print(" "*(rows-rownum),"* "*rownum)
    else:
        print(" "*(rownum-rows),"* "*(rows-(rownum-rows)))
```

16\.

1  
2 2  
3 3 3  
4 4 4 4  
5 5 5 5 5

code:

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    print(f'{rownum} '*rownum)
```

17\.

1  
1 2 1  
1 2 3 2 1  
1 2 3 4 3 2 1

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
   print(" "*(rows-rownum),*range(1,rownum+1),*range((rownum-1),0,-1),sep="")
```

18\.

1  
10  
101  
1010  
10101

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    for colnum in range(1,rownum+1):
        if colnum%2==0:print(0,end="")
        else:print(1,end="")
    print()
```

19\)

101010  
010101  
101010  
010101  
101010

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    if rownum%2==0:print("01"*(rows-2))
    else:print("10"*(rows-2))
```

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    for colnum in range(1,rows+2):
        if rownum%2!=0:
            if colnum%2==0:
                print(0,end="")
            else:
                print(1,end="")
        else:
            if colnum%2==0:
                print(1,end="")
            else:
                print(0,end="")

    print()
```

20\.

1 1 1 1 1  
0 1 1 1 1  
0 0 1 1 1  
0 0 0 1 1  
0 0 0 0 1

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    print("0"*(rownum-1),"1"*(rows-rownum+1),sep="")
```

21\)

1 2 3 4 5  
1 2 3 4  
1 2 3  
1 2  
1  
1 2  
1 2 3  
1  2  3 4  
1  2  3  4  5

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows*2):
    if rownum<=rows:
        print(" "*(rownum),*range(1,(rows-rownum+1)+1))
    else:
        print(" "*(rows-(rownum-rows)),*range(1,(rownum-rows+1)+1))
```

22\)

1  
1 2  
1 2 3  
1 2 3 4  
1 2 3 4 5

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    print(" "*(rows-rownum),*range(1,rownum+1),sep="")
```

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    print(" "*(((rows-rownum)*2)),end="")
    print(*range(1,rownum+1))
```

23\.

1  
1 3  
1 2 6  
1 2 3 10  
1 2 3 4 15

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    print(*range(1,rownum),((rownum)*(rownum+1))//2)
```

24\.

1  
1 2  
1 2 6  
1 2 3 24  
1 2 3 4 120

code:

```python
rows=int(input("rows:"))
fact=1
for rownum in range(1,rows+1):
    fact*=rownum
    print(*range(1,rownum),fact)
```

25\.

1  
3 2  
4 5 6  
10 9 8 7  
11 12 13 14 15

**code:**

```python
rows=int(input("rows:"))
start=1
end=0
for rownum in range(1,rows+1):
   end=end+rownum #end=15
   if rownum%2!=0: #when rownumber is odd
       print(*range(start,end+1))
   else:
       print(*range(end,start-1,-1))
   start=end+1 #start=11
```

26\.

1 2 3 4 5  
10 9 8 7 6  
11 12 13 14 15  
20 19 18 17 16  
21 22 23 24 25

**code:**

```python
rows=int(input("rows:"))
start=1
for rownum in range(1,rows+1):
   if rownum%2!=0: #when rownumber is odd
       print(*range(start,start+rows,1))
       start+=(rows*2)
   else:
       print(*range(start-1,start-rows-1,-1))
```

in python, when we want to print the character for given unicode

number, we will use a function called "chr()"

chr() will return "character" for given unicode number

Unicode number of upper case letters will start from "65 to 90"

Unicode  number of the lower case letters will start from "97 to 122"

Unicode number of digits will start from "48 to 57"

**example:**

```python
print(chr(97))
print(chr(122))
print(chr(65))
print(chr(90))
print(chr(48))
print(chr(57))
```

1\.

A  
A B  
A B C  
A B C D  
A B C D E

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    data=65
    for colnum in range(1,rownum+1):
        print(chr(data),end=" ")
        data+=1
    print()
```

2\.

A B C D E  
A B C D  
A B C  
A B  
A

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    data=65
    for colnum in range(1,(rows-rownum+1)+1):
        print(chr(data),end=" ")
        data+=1
    print()

or

rows=int(input("rows:"))
for rownum in range(1,rows+1):
    for colnum in range(1,(rows-rownum+1)+1):
        print(chr(65+colnum-1),end=" ")
    print()
```

3\.

A  
B C  
D E F  
G H I J  
K L M N O  
P Q R S T U  
V W X Y Z A B

**code:**

```python
rows=int(input("rows:"))
data=65
for rownum in range(1,rows+1):
    for colnum in range(1,rownum+1):
        print(chr(data),end=" ")
        if data>=90:
            data=65
        else:
            data+=1
    print()
```

3\.

A  
B A  
C B A  
D C B A  
E D C B A

**code:**

```python
rows=int(input("rows:"))
data=65
for rownum in range(1,rows+1):
    data=65+rownum-1
    for colnum in range(1,rownum+1):
        print(chr(data),end=" ")
        data-=1
    print()
```

4\.

A  
A   B  
A   B  C  
A  B  C  D

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    data=65
    print(" "*(rows-rownum),end="")
    for colnum in range(1,rownum+1):
        print(chr(data),end=" ")
        data+=1
    print()
```

5\.

A B C D E  
A B C D  
A B C  
A B  
A

code:

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    data=65
    print(" "*(rownum),end="")
    for colnum in range(1,(rows-rownum+1)+1):
        print(chr(data),end=" ")
        data+=1
    print()
```

6\.

A  
A B  
A B C  
A B C D  
A B C D E  
A B C D  
A B C  
A B  
A

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows*2):
    data=65
    if rownum<=rows:
        for colnum in range(1,rownum+1):
            print(chr(data),end=" ")
            data+=1
    else:
        for colnum in range(1,(rows-(rownum-rows))+1):
            print(chr(data),end=" ")
            data+=1

    print()
```

7\.

A B C D E  
A B C D  
A B C  
A B  
A  
A B  
A  B  C  
A  B  C D  
A B C D E

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows*2):
    data=65
    if rownum<=rows:
        print(" "*(rownum),end="")
        for colnum in range(1,(rows-rownum+1)+1):
            print(chr(data),end=" ")
            data+=1
    else:
        print(" "*(rows-(rownum-rows)),end="")
        for colnum in range(1,(rownum-rows+1)+1):
            print(chr(data),end=" ")
            data+=1

    print()
```

8\.

A  
A  B  
A  B  C  
A  B  C  D  
A  B  C  D  E

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    print(" "*((rows-rownum)*2),end="")
    data=65
    for colnum in range(1,rownum+1):
        print(chr(data),end=" ")
        data+=1

    print()
```

9\.

\* \* \* \* \*  
\*           \*  
\*           \*  
\*           \*  
\* \* \* \* \*

**code:**

```python
rows=int(input("rows:"))
for rownum in range(1,rows+1):
    if rownum==1 or rownum==rows:
        print("* "*rows)
    else:
        print("* "+" "*(rows)+"*")
```

---

## Un-conditional Statements

**in python, we will have the following un-conditional statements:**

**1)  break :**

break statement is used to "stop the loop execution"

break is used only inside the loop or break always part of the loop

a break can able to stop the loop execution , when the break is

executed, any code after the break, we have , that code will never be

executed

when we use "break" inside the "inner or nested loop", then break

can stop the only inner or nested loop execution , never stop the

outer loop execution

syntax:

```python
                        break
```

**example:**

```python
a=1
while a<=10:
    if a==5:
        break
    print(a)
    a+=1
```

**example:**

```python
a,b=1,1
count=0
while a<=5:
    while b<=5:
        if b==4:
            break
        count+=10
    a+=1
    b=1
    count+=20
print(count )
```

**example:**

```python
a,b=1,1
count=0
while a<=5:
    while b<=5:
        if b==4:
            break
        count+=10
        b+=1
    a+=1
    b=1
    count+=20
print(count )
```

**output:**

250

**example:**

```python
a,b,c,count=1,1,1,0
while a<=5:
    while b<=5:
        if a>=3:
            break
        print("a:",a)
        while c<=5:
            if b>=4:
                break
            c+=1
            count+=30
        b+=1
        count+=20
    b,c=1,1
    count+=10
    a+=1
print(count)
```

**output:**

```python
a,b,c,count=1,1,1,0
while a<=5:
    while b<=5:
        if a>=3:
            break
        print("a:",a)
        while c<=5:
            if b>=4:
                break
            c+=1
            count+=30
        b+=1
        count+=20
    b,c=1,1
    count+=10
    a+=1
print(count)
```

**example:**

```python
a,b,c,count=1,1,1,0
while a<=5:
    while b<=5:
        count+=30
        b+=1
        while c<=5:
            count+=40
            c+=1
            if b>=4:
                break
        if a>=4:
            break
        c=1
    b,c=1,1
    count,a=count+40,a+1
print(count)
```

**output:**

2670

**2) continue**

continue is also used only in  "looping statement"

continue never stop the loop execution, it always  stop the "current

iteration" or skip the current iteration

when the continue is executed , the code after continue what we write

will not be executed

**syntax:**

```python
      continue
```

**example:**

```python
a=1
while a<=10:
    if a==5:
        continue
    print(a)
    a+=1
```

output:

infinite loop

**example:**

```python
a=1
while a<=10:
    a+=1
    if a==5:
        continue
    print(a)
```

**3)  pass**

in python, pass is used to "to specify the no code", when we are

working with any loop or conditional statement  or class or function,

if there is no code for any loop or conditional statement or  class or

function ,  in python, we will use "pass"

in python, pass is act as a "placeholder, to tell there is no code"

**example:**

```python
a=10
if a>100:
  pass
```

**example:**

```python
a=1
while a<=10:
    pass
```

when we are working with "while loop" or "for loop", along with

while loop or for loop, we can able to write the "else" block

syntax:

```python
while cond.:

     #write the logic here
else:
     #write the logic here

syntax:

for var_name in iterable_name:

    #write the logic here
else:
#write the logic here
```

when we take "else" block with "while loop" and "for loop" , the

"Else" always going to be "Executed" after the loop execution

when we take "Else" block with "for loop"  and inside the "For loop", if

any break statement is executed , the else block execution will be

skipped.

when we take "Else" block with "while loop"  and inside the "while

loop",  if any break statement is executed , the else block execution will

be  skipped.

**example:**

```python
a=1
while a<=3:
    print(a)
    a+=1
else:
    print("else block from while")
```

**output:**

1  
2  
3  
else block from while

**example:**

```python
a=1
while a<=5:
    if a==3:
        break
    print(a)
    a+=1
else:
    print("else block from while")
```

**output:**

1  
2

**example:**

```python
a=1
while a<=5:
    print(a) #1 2 3 4 5
    a+=1 #a=6
    if a==3:
        continue
else:
    print("else block from while")
```

**output:**

1  
2  
3  
4  
5  
else block from while

**example:**

```python
a=1
while a<=10:
    if a>=11:
        break
    print(a)
    a+=1
else:
    print("else block from while")
```

**output:**

1  
2  
3  
4  
5  
6  
7  
8  
9  
10  
else block from while

**example:**

```python
for i in range(1,10):
    if i==5:
        continue
    print(i)
else:
    print("else block from for")
```

**output:**

1  
2  
3  
4  
6  
7  
8  
9  
else block from for

**example:**

```python
for i in range(1,10):
    if i==5:
        break
    print(i)
else:
    print("else block from for")
```

**output:**

1  
2  
3  
4

---

## String Formatting

when we want to print the "both text and data together" in python,

we will use the following methods with print() function:

1) format specifiers

2) format() function

3) f-string

**1) format specifiers:**

like C or C++, python also uses format specifiers to "display the both

string and data" together

**in python, we will have the following format specifiers:**

1)  "%d" ===\> for integer numbers

2) "%f"  ===\> for floating-point numbers

3) "%s"  ===\> for string data

**example:**

```python
a=10
b="hello"
print("the value of a is:%d"%(a))
print("the value of b is:%s"%(b))
print("a:%d,b:%s"%(a,b))
```

**output:**

the value of a is:10  
the value of b is:hello  
a:10,b:hello

**example:**

```python
a=1.23
print("the value of a is:%f"%(a))
a=1.234
print("the value of a is:%f"%(a))
a=1.2345
print("the value of a is:%f"%(a))
a=1.23456789
print("the value of a is:%f"%(a))
a=1.248986243
print("the value of a is:%f"%(a))
```

**output:**

the value of a is:1.230000  
the value of a is:1.234000  
the value of a is:1.234500  
the value of a is:1.234568  
the value of a is:1.248986

**example:**

```python
a=1.23
print("the value of a is:%.2f"%(a))
a=1.23
print("the value of a is:%.9f"%(a))
a=1.23
print("the value of a is:%.4f"%(a))
```

**output:**

the value of a is:1.23  
the value of a is:1.230000000  
the value of a is:1.2300

**example:**

```python
a=1.2345656783452
print("the value of a is:%.2f"%(a))
a=1.2345656783452
print("the value of a is:%.4f"%(a))
a=1.2345656783452
print("the value of a is:%.5f"%(a))
a=1.2345656783452
print("the value of a is:%.6f"%(a))
a=1.2345656783452
print("the value of a is:%.9f"%(a))
```

**example:**

```python
a=1.799
print("the value of a is:%.2f"%(a))
a=1.799999
print("the value of a is:%.3f"%(a))
a=1.799999
print("the value of a is:%.5f"%(a))
```

**2) format() function:**

when we want to print the "both text and data together" in python we

will use a method called "format()" method

when we are using to format() function to print  the "both text and

data" together , we keep always keep the data representation using

{} (braces), we can display the data, where the braces will use to

print the data, inside the braces, we will uses "either numbering or

naming"

the numbering always will start from "o" onwards

**example:**

```python
a=10
b=20
print("the value of a is:{0}".format(a))
print("the value of a is:{0} and b:{1}".format(a,b))
print("the value of a is:{1} and b is:{0}".format(a,b))
```

**output:**

the value of a is:10  
the value of a is:10 and b:20  
the value of a is:20 and b is:10

**example:**

```python
a=10
b=20
print("the value of a is:{r1}".format(r1=a))
print("the value of a is:{r1} and b:{r2}".format(r1=a,r2=b))
print("the value of a is:{r2} and b is:{r1}".format(r1=a,r2=b))
```

---

## Data Structures

**in python, we will have the following data structures:**

1)  list

2)  tuple

3)  set

4)  string

5)  dictionary

6)  array  from array module

7)  deque from  collections module

---

## Indexing and Slicing

**in python, we can apply indexing and slicing on the following:**

1)  list

2)  tuple

3)  string

4)  bytes()

5) bytearray()

6) memoryview()

using indexing and slicing , we can able to "Access the data from the

list or tuple or string or any other"

in lists , with help of indexing, we can able to "access the data, update the

data, we can able to delete the data"

via indexing, we can able to access only value for given index, if the given

index is not valid for given any sequence type (list,tuple, string, range(),...),

python will raise an error

via indexing, we can able to access only one value

when we want to access the zero or more values from the given sequence

type, in python we will use "slicing"

slicing can be done via "indexing"

while doing slicing on any given sequence type, if given any wrong index,  
slicing never give any error

when we apply the slicing  on the any sequence type, the result always

in the sequence type

when we done the slicing on the list , result of the slicing is "list"

when we done the slicing on the tuple , result of the slicing is "tuple"

when we done the slicing on the string , result of the slicing is "string"

when we done the slicing on the range() , result of the slicing is "range()"

when given slicing with wrong indexing, we will get always "empty

sequence type" as result

**in Python, indexing will be two types:**

1)  positive indexing

this indexing will start from "0 to n-1"

this indexing number will start from "left to right direction" or "From

starting of the list to end of the list"

where "n" refers " number of elements in the given sequence type"

2) negative indexing

this indexing will start from "-1 to -n"

this indexing numbering  will start from "right to left direction" or "From

ending of the list to starting of the list"

where "n" refers " number of elements in the given sequence type"

when we want to access the any data from the sequence type using

indexing , we will use the following syntax:

sequence\_name\[index\]

**example:**

```python
 l1=[10,20,30,40,50,60,70,80,90,100]
print(l1[4])#50
print(l1[-1])#100
print(l1[-6])#50
print(l1[-9])#20
print(l1[8])#90
```

**example:**

```python
l1=(10,20,30,40,50,60,70,80,90,100)
print(l1[4])#50
print(l1[-1])#100
print(l1[-6])#50
print(l1[-9])#20
print(l1[8])#90
```

**example:**

```python
l1="hello world"
print(l1[4])#o
print(l1[-1])#d
print(l1[-6])#space
print(l1[-9])#l
print(l1[8])#r
```

**example:**

```python
l1=range(10,110,10)
print(l1[4])#50
print(l1[-1])#100
print(l1[-6])#50
print(l1[-9])#20
print(l1[8])#90
```

in list, using indexing ,

we can access the element  
list\_name\[index\]

we can able to update the data

```python
     list_name[index]=value
```

we can able to delete the data using indexing with help of a keyword

called "del"

```python
        del  list_name[index]
```

**example:**

```python
l1=[10,2,6,7,30,50,60,4,-10,100]
#accessing the data from the list using indexing
print(l1[5])
print(l1[-5])
#update the data int the list using indexing
l1[0]=100 #[100,2,6,7,30,50,60,4,-10,100]
l1[7]=560 #[100,2,6,7,30,50,60,560,-10,100]
```

l1\[-8\]=200#\[100,2,200,7,30,50,60,560,-10,100\]

```python
print(l1)
#delete the data from the list using indexing
del l1[0]
print(l1)#[2,200,7,30,50,60,560,-10,100]
del l1[3]
print(l1)#[100,2,200,7,50,60,560,-10,100]
```

when we want to access the data from the sequence type, we will use

following for slicing :

sequence\_type\[start:end:step\]

slicing always gives the values from "start to end-1"

step by default "1"

start by default  "0"

end by default "-1 or n-1"

**example:**

```python
l1=[10,2,6,7,30,50,60,4,-10,100]
print(l1[3:])#[7,30,50,60,4,-10,100]
print(l1[:3])#[10,2,6]
print(l1[2:6])#[6,7,30,50]
print(l1[:])#[10,2,6,7,30,50,60,4,-10,100]
print(l1[::2])#[10,6,30,60,-10]
print(l1[1:8:3])#[2,30,4]
print(l1[1:200:4])#[2,50,100]
print(l1[100:200:5])#[]
```

**example:**

```python
l1="hello world"
print(l1[3:])#lo world
print(l1[:3])#hel
print(l1[2:6])#llo
print(l1[:])# hello world
print(l1[::2])#hlowrd
print(l1[1:8:3])#eoo
print(l1[1:200:4])#e l
print(l1[100:200:5])#empty string
```

**example:**

```python
l1=[10,2,6,7,30,50,60,4,-10,100]
print(l1[-8:-1])#[6,7,30,50,60,4,-10]
print(l1[1:10:-4])#[]
print(l1[10:1:-4])#[100,50]
print(l1[::-1])#reverse the list
print(l1[::-4])
print(l1[10:0:-4])
```

---

## Programs on Lists and Strings

write a python program to swap the even index elements with odd index

**elements without using any built-in function for the given list:**

example:  
\[1,2,3,4,5,6\]

\[2,1,4,3,6,5\]

**code:**

```python
l1=[1,2,3,4,5,6,7]
length=0
```

for \_ in l1:length+=1

```python
if length%2==0:
   l1[0::2],l1[1::2]=l1[1::2],l1[0::2]
   print(l1)
else:
    element=l1[-1]
    l1=l1[:-1]
    l1[0::2],l1[1::2]=l1[1::2],l1[0::2]
    print(l1+[element])
```

write a python program insert the given element into the list for given

**any position  without using any built-in function:**

```python
l1=[1,2,3,4,5,6,7,8]
pos=3
ele=100
l1=[1,2,100,3,4,5,6,7,8] <=== result
```

**code:**

```python
l1=[1,2,3,4,5,6,7]
pos=int(input("position:"))
ele=int(input("element:"))
l1=l1[:pos-1]+[ele]+l1[pos-1:]
print(l1)
```

write a python program delete the element from the list for given

**any position  without using any built-in function:**

```python
l1=[1,2,3,4,5,6,7,8]
pos=3
l1=[1,2,4,5,6,7,8] <=== result
```

**code:**

```python
l1=[1,2,3,4,5,6,7,8]
pos=int(input("position:"))#3
l1=l1[:pos-1]+l1[pos:]
print(l1)
```

leet code-1:

**move the all zeros to the end of the given array or list:**

```python
l1=[1,2,3,0,4,5,0,6]
```

result: \[1,2,3,4,5,6,0,0\]

code:

```python
l1=[1,2,3,0,4,5,0,6]
result,count=[],0
for i in l1:
    if i!=0:
        result+=[i]
    else:
        count+=1
print(result+[0]*count)
```

leet code-2:

**rotate the array or list for k number of times towards right :**

```python
l1=[1,2,3,4,5,6]
```

**code:**

```python
l1=[1,2,3,4,5,6]
k=int(input("k:"))
length=0
```

for \_ in l1:length+=1

```python
k=k%length
print(l1[-k:]+l1[:-k])
```

leet code-3

**rotate the array or list for k number of times towards left :**

```python
l1=[1,2,3,4,5,6]
```

**code:**

```python
l1=[1,2,3,4,5,6]
k=int(input("k:"))
length=0
```

for \_ in l1:length+=1

```python
k=k%length
print(l1[k:]+l1[:k])
```

write a python program to make the list left side all are even elements and  
right side all are odd elements for the given list:

input: \[1,2,3,4,5,6\]

output: \[2,4,6,1,3,5\]

**code:**

```python
l1=[1,2,3,4,5,6]
even,odd=[],[]
for i in l1:
    if i%2==0: even+=[i]
    else: odd+=[i]
print(even+odd)
```

write a python program to find the maximum element in the given list:  
input: \[1,2,3,4,5\]  
output: 5  
code:

```python
l1=[0,-2,30,3,4,5,6]
maximum=l1[2]
for i in l1:
    if maximum<i:maximum=i
print(maximum)
```

write a python program to second maximum element in the given list:

```python
l1=[1,2,3,4,5,6]
maximum=5
```

**code:**

**code:**

```python
l1=[100,1,1,1,1]
max1=max2=l1[2] #0
for i in l1:
    if max1<i:
        max2=max1  #100
        max1=i#20
    elif max2==max1:
        max2=i #max2=-1
    elif max2<i:
        max2=i #0
print(max2)
```

**write a python program to find the highest frequency of the given element:**

```python
l1=[1,2,3,4,5,2,3,4,3,4,3,3]
output:  3
l1=[1,2,1,2,1,2]
```

output: 1,2

**code:**

```python
l1=[1,2,3,4,5,2,3,4,4,4,3,4,3,3]
d1={}
#make the empty dictionary
for i in l1:
    d1[i]=0
#calcuate the count of the each element
for i in l1:
    d1[i]+=1
freq=0
ele=[]
#find the maximum frequecy
for i in d1:
    if freq<d1[i]:
        freq=d1[i]
#make the list with elements with maximum freq.

for i in d1:
    if freq==d1[i]:
        ele+=[i]
print(ele)
```

write a python program to print the string in following format for  given  
input string:

input:  abcdabcdaabb  
output:  a4b4c2d2

**code:**

```python
l1="abcdabcdaabb"
d1={}
#make the empty dictionary
for i in l1:
    d1[i]=0
#calcuate the count of the each element
for i in l1:
    d1[i]+=1
for i in d1:
    print(f'{i}{d1[i]}',end="")
```

write a python program to  first-non repeating character in the given string:

input:   ababcdef  
output: c

**code:**

```python
l1="abfcdabefgcdaabb"
d1={}
#make the empty dictionary
for i in l1:
    d1[i]=0
#calcuate the count of the each element
for i in l1:
    d1[i]+=1
for i in d1:
    if d1[i]==1:
        print(i)
        break
else:
    print("all are repeating!")
```

write a python program to  print all non repeating characters as string  in the given string:  
input:   ababcdef  
output: cdef  
code:

```python
l1="aaff"
d1={}
flag=False
#make the empty dictionary
for i in l1:
    d1[i]=0
#calcuate the count of the each element
for i in l1:
    d1[i]+=1
for i in d1:
    if d1[i]==1:
        print(i,end="")
        flag=True
if not flag:
       print("all are repeating")
```

**write a python program to print the words of the given string as a list:**

input:  i am not learning python  
output: \["i","am","not","learning","python"\]  
code:

```python
s1="i am from india"
word=''
l1=[]
for i in s1:
    if i!=' ':
        word+=i
    else:
        if word!='':
           l1+=[word]
        word=''
if word!='':
  l1+=[word]
print(l1)
```

write a python program to reverse the each word of the string  
input: i am from india  
output:  i ma morf aidni  
code:

```python
s1="i am from india"
word=''
for i in s1:
    if i!=' ':
        word+=i
    else:
        if word!='':
           print(word[::-1],end=" ")
        word=''
if word!='':
  print(word[::-1],end=" ")
```

write a python program to print the next alphabet to character of the  
given string:

input: abcd  
output:  bcde

**code:**

```python
s1=input("string:")
for i in s1:
    if i!='z' and i!='9':
        print(chr(ord(i)+1),end="")
    elif i!='9':
        print(chr(ord(i)-25),end="")
    else:
        print(chr(ord(i)-9),end="")
```

write a python program substitute the vowel with next alphabet in the

**given string:**

input: abcde  
output: bbcdf  
code:

```python
s1=input("string:")
for i in s1:
    if i in "aeiouAEIOU":
        print(chr(ord(i)+1),end="")
    else:
        print(i,end="")
```

write a python program to print the maximum sum of the sub array of  
given size k :  
input:  
\[1,2,3,4,5,6,7\]

```python
k=3  ===>  [1,2,3],[2,3,4],[3,4,5],[4,5,6],[5,6,7] (18)
code:
l1=[1,2,3,4,5,6,7]
k=int(input("k:"))
if k>0:
    #length of the list
    length=0
    for _ in l1:length+=1
    sum=0
    #find the given k-size sum
    for i in l1[:k]:
        sum+=i
    maximum=sum
    index=k
    for i in l1[k:]:
        sum=sum+l1[index]-l1[index-k]
        if maximum<sum:
            maximum=sum
        index+=1
    print(maximum)
else:
    print("k never be negative")
```

write a python program to print the sub array which give maximum sum of  
given size k :  
input:  
\[1,2,3,4,5,6,7\]  
code:

```python
l1=[1,2,300,40,50,100]
k=int(input("k:"))
if k>0:
    #length of the list
    length=0
    for _ in l1:length+=1
    sum=0
    #find the given k-size sum
    for i in l1[:k]:
        sum+=i
    maximum=sum
    index=k
    maxindex=k
    for i in l1[k:]:
        sum=sum+l1[index]-l1[index-k]
        if maximum<sum:
            maximum=sum
            maxindex=index
        index+=1
    print(maxindex)
    print(l1[maxindex-k+1:maxindex+1])
else:
    print("k never be negative")
```

**write a python program to print the all sub arrays of the given size k :**

input: \[1,2,3,4,5\]

```python
k=4
```

\[1,2,3,4\],\[2,3,4,5\]

```python
k=2
```

\[1,2\],\[2,3\],\[3,4\],\[4,5\]

**code:**

```python
l1=[1,2,300,40,50]
length=0
```

for \_ in l1: length+=1

```sql
start,end=0,0
while start<length:
    print(l1[start:end+1],end=",")
    if end<length-1:
        end+=1
    else:
        start+=1
        end=start
```

**write a python program print the all substrings of the given string:**

input:  abcd  
a,b,c,d,ab,bc,cd,abc,bcd,abcd

**code:**

```python
l1="abcd"
length=0
```

for \_ in l1: length+=1

```sql
start,end=0,0
while start<length:
    print(l1[start:end+1],end=",")
    if end<length-1:
        end+=1
    else:
        start+=1
        end=start
```

**write a python program to print the maximum sub string of the string given length k , where k is sub-string length and k is positive number:**

input:  
abcde  
length= 3  
abc, bcd, cde   (cde)  
code:

```python
l1="abcdef"
k=int(input("k:"))
if k>0:
    #length of the list
    length=0
    for _ in l1:length+=1
    sum=''
    #find the given k-size sum
    for i in l1[:k]:
        sum=sum+i
    maximum=sum
    index=1
    for i in l1[k:]:
        print(l1[index-1:index+k-1])
        index+=1
else:
    print("k never be negative")
```

---

## Searching and Sorting

**Linear search:**

linear search is nothing but "searching the given element or key or value  
from the  starting of the list or array to end of the array or list"

linear search is perform on "un-sorted array or list"

**example:**

```python
l1=[1,2,3,4,5,6,7,8,9,10]
element=int(input("element:"))
for i in l1:
    if i==element:
        print("found!")
        break
else:
    print("not found!")
```

**Binary Search:**

binary search is a perform on "sorted array or list"  
when we want to perform the "binary search" , we will always need to sort  
the data , when the data not in given sorted form  
in binary search , only  half of the array or list only verified for searching, not the complete data  due to "data is in sorted form"

in binary search we always , find the "mid" element

```python
mid=(low+high)//2
low=start index
high=end index
```

**example:**

```python
l1=[1,2,3,4,5,6,7,8]
element=int(input("element:"))
times=0
#length of the array
length=0
```

for \_ in l1:length+=1

```sql
start=0
end=length-1
while start<=end:
    times+=1
    mid=(start+end)//2
    if l1[mid]==element:
        print("found!")
        print(times)
        break
    if l1[mid]>element:end=mid-1
    else:start=mid+1
else:
    print("not found!")
    print(times)
```

**Bubble sort:**

```python
l1=[4,5,6,-2,-1,-3]
#length of the array
length=0
```

for \_ in l1:length+=1

```python
for i in range(length):
    for j in range(i+1,length):
        if l1[i]>l1[j]:
            l1[i],l1[j]=l1[j],l1[i]
print(l1)
```

write a python program arrange the all alphabets of the given string in

**the alphabetical order and print the result as a string:**

input:  dfgabc  
output: abcdfg  
code:

```python
l1=input("string:")
print(l1)
l1=[*l1]
#length of the array
length=0
```

for \_ in l1:length+=1

```python
for i in range(length):
    for j in range(i+1,length):
        if l1[i]>l1[j]:
            l1[i],l1[j]=l1[j],l1[i]
print(*l1,sep="")
```

**code:**

```python
l1=["abc","zef","bca","cab","aa","a","b","def"]
print(l1)
#length of the array
length=0
```

for \_ in l1:length+=1

```python
for i in range(length):
    for j in range(i+1,length):
        if l1[i]>l1[j]:
            l1[i],l1[j]=l1[j],l1[i]
print(l1)
```

**code:**

```python
l1="ab023ghjcd"
l1=[*l1]
#length of the array
length=0
```

for \_ in l1:length+=1

```python
for i in range(length):
    for j in range(i+1,length):
        if l1[i]>l1[j]:
            l1[i],l1[j]=l1[j],l1[i]
print(*l1,sep="")

code:
l1=["zef","10"," ","fgh","123","abc","456","ghi","789"]
l1=[*l1]
#length of the array
length=0
```

for \_ in l1:length+=1

```python
for i in range(length):
    for j in range(i+1,length):
        if l1[i]>l1[j]:
            l1[i],l1[j]=l1[j],l1[i]
print(l1)

code:
l1=["zef"," ","fgh","abc","ghi"]
l1=[*l1]
#length of the array
length=0
```

for \_ in l1:length+=1

```python
for i in range(length):
    for j in range(i+1,length):
        if l1[i]>l1[j]:
            l1[i],l1[j]=l1[j],l1[i]
print(l1)
```

**insertion sort:**

**code:**

```python
l1=[5,4,3,2,1]
length=0
```

for \_ in l1:length+=1

```python
for i in range(1,length):
    key=l1[i]
    j=i-1
    while j>=0 and l1[j]>=key:
        l1[j+1]=l1[j]
        j-=1
    l1[j+1]=key
    print(l1)
print(l1)
```

**selection sort:**

**code:**

```python
l1=[5,4,3,2,1]
length=0
```

for \_ in l1:length+=1

```python
for i in range(length):
   min=i
   for j in range(i,length):
       if l1[j]<l1[min]:
           min=j
   #swap
   l1[i],l1[min]=l1[min],l1[i]
   print(l1)#each pass result
print(l1)
```

---

## Comprehensions

in python, we can able to create the list using another list or iterable using  
list comprehension  
syntax:  
\[i for i in iterable\_name if cond.\]

**example:**

```python
print([i for i in range(1,11)])
print([i for i in range(1,11) if i>=5])
print([i for i in range(1,11) if i<=5])
print([i for i in range(1,11) if i==5])
```

**example:**

```python
print([i for i in "hello"])
print([i for i in {1,2,3,4,5}])
print([i for i in {1:2,3:4,5:6}])
d1={1:2,3:4,5:6}
print([d1[i] for i in {1:2,3:4,5:6}])
```

**set comprehension:**

in python, we can able to create the set using another set or iterable using  
set comprehension  
syntax:  
{i for i in iterable\_name if cond.}

**example:**

```python
print({i for i in range(1,10) if i>=5})
print({i for i in range(1,10) if i<=5})
print({i for i in range(1,10) if i==5})
```

**dictionary comprehension:**

in python, we can able to create the dictionary using another dictionary or iterable using dictionary comprehension  
syntax:  
{key:value for key in iterable\_name if cond.}

**example:**

```python
print({i:i**2 for i in range(1,11)})
print({i:i**2 for i in range(1,11) if i<=5})
print({i:i**2 for i in range(1,11) if i>=5})
print({i:i**2 for i in range(1,11) if i==5})
```

---

## Working with Lists

**on list we can able to apply the following built-in functions:**

1.max()  
using this function we can able to get the maximum element in the given  
list  
2.min()  
using this function we can able to get the minimum element in the given  
list  
3.sum()  
using this function we can able to get the sum of the all elements of the  
given list  
4.len()  
using this function we can able to "total number of elements of the given  
list"  
5.sorted()  
using this function we can able to "sort the given list elements either in  
ascending order or descending order" and this function will work on any  
iterable , but it always return the result as list  
6.reversed()  
using this function we can able to "Reverse the given list"  and reversed()  
always returns result as "object" form, in order to see the result again  
we need to convert into list  using list() function  
reversed() we can able apply only  on "sequence data types"

**example:**

```python
l1=[-1,2,3,4,-10,-99,22,34,56,78]
print(max(l1))#78
print(min(l1))#-99
print(sum(l1)) # 99
print(len(l1))#10
print(sorted(l1))#[-99,-10,-1,2,3,4,22,34,56,78]
print(sorted(l1,reverse=True))#[78,56,34,22,4,3,2,-1,-10,-99]
print([*reversed(l1)])#[78,56,34,22,-99,-10,4,3,2,-1]
print(list(reversed(l1)))
```

**working with list class functions:**

in python, list is built-in class  
when we create the list with some name, the name is referred as "object  
of the list"  
when we want to know the all functions or method of the list in python,  
we will use a function in python called "dir()"

syntax:  
dir(list)   or dir(object\_name or list\_name)

example:

```python
print(dir(list))
or
l1=[]
print(dir(l1))
```

**in list class, we will have the following functions or methods:**

1) append()  
this function is used to add the element to the list at the end

**example:**

```python
l1=[1,2,3,4]
l1.append(100)
print(l1)
l1.append(200)
print(l1)
l1.append(300)
print(l1)
l1+=[int(input("element:"))]
print(l1)
```

2) insert()

this function is used to add the element to the list at the any position ,  
where position refers index

**example:**

```python
l1=[1,2,3,4]
l1.insert(2,200)
print(l1)#[1,2,200,3,4]
l1.insert(3,300)
print(l1)
```

3) pop()  
this function is used to remove the element from the list based on the  
given index, if we not given any index for pop() function, it will remove  
last element from the list

**example:**

```python
l1=[1,2,3,4,5]
l1.pop()
print(l1)#[1,2,3,4]
l1.pop(1)#[1,3,4]
print(l1)
```

4) clear()  
using this function, we can able to remove the all elements from the list,  
this function will make the list as empty

**example:**

```python
l1=[10,20,30,40,50]
l1.clear()
print(l1)
l1=[10,20,30,40,50]
```

del l1\[:\]# it will remove all elements from the list

```python
print(l1)
```

5) remove()  
using this function, we can able to remove the given element from the list,  
if given element is not present , then it will give an error

**example:**

```python
l1=[10,20,10,30,40,50]
l1.remove(10)
print(l1)
l1.remove(20)
print(l1)
```

**example:**

```python
l1=[10,20,10,30,40,50]
element=int(input("element:"))
if element in l1:
    l1.remove(element)
    print(l1)
else:
    print("given element is not present!")
```

6)  extend()  
using this function we can able to merge the given two lists

**example:**

```python
 l1=[10,20,10,30,40,50]
l2=[1,2,3,4]
l3=[4,5,6,7]
print(l1+l2+l3)
l1.extend(l2)
l1.extend(l3)
print(l1)
```

7) copy()  
using this function we can able to copy the one list data into another

**example:**

```python
l1=[10,20,10,30,40,50]
l2=l1.copy()
print(l2)
print(id(l1))
print(id(l2))
```

**example:**

```python
l1=[10,20,10,30,40,50]
l2=l1
print(l2)
print(id(l1))
print(id(l2))
#update
l1[0]=1000
l1[1]=2000
print(l2)
```

**example:**

```python
l1=[10,20,10,30,40,50]
l2=l1.copy()
print(l2)
print(id(l1))
print(id(l2))
#update
l1[0]=1000
l1[1]=2000
print(l2)
print(l1)
```

8) reverse()  
using this function we can able to reverse the given list

**example:**

```python
l1=[10,20,10,30,40,50]
l1.reverse()
print(l1)
l1=[10,20,10,30,40,50]
print(l1[::-1])
```

9) sort()  
using this function we can able to sort the given list either in ascending  
order or descending order

**example:**

```python
l1=[10,20,10,30,40,50,20,30,40]
l1.sort()
print(l1)
l1=[10,20,10,30,40,50,20,30,40,1.234]
l1.sort(reverse=True)
print(l1)
l1=["a","b","c","d"]
l1.sort(reverse=True)
print(l1)
```

10) count()  
using this function we can able to count the given element is present how  
many times in the entire list

**code:**

```python
l1=[10,20,10,30,40,50,20,30,40]
print(l1.count(10))
print(l1.count(20))
print(l1.count(30))
print(l1.count(100))
```

11) index()  
using this function we can able to get the given element index in the list,  
if the given element present multiple times, then this function always return first occurrence index

**example:**

```python
l1=[10,20,10,30,40,50,20,30,40]
print(l1.index(10))
print(l1.index(20))
print(l1.index(30))
print(l1.index(100))
```

write a python program to create the list dynamically with given number  
of elements:  
size: 5  
\[10,20,30,40,50\]  
code:

```python
size=int(input("size:"))
l1=[]
if size<=0:
    print("size never be zero or negative")
else:
    for _ in range(size):#range(2)#0,1
        l1+=[int(input("element:"))]
    print(l1)
```

**write a python program to make the dynamic list for given size, where it allow only even and positive integers:**

input:  5  
output: \[2,100,4,8,10\]  
code:

```python
size=int(input("size:"))
l1=[]
if size<=0:
    print("size never be zero or negative")
else:
    count=0
    while count<size:
        element=int(input("element:"))
        if element%2==0 and element>0:
            l1+=[element]
            count+=1
    print(l1)
```

note:  
when we are working with append() and insert() functions , append()  
function will add the elements into the list at the end and it never going  
to change the index of the previous elements in the list, insert() function  
is used to add the element into list at any position , but insert() function  
will may change the previous elements indexes

while working with insert() function , if we give any wrong index , based  
on index type, it will add the element into list at end(if the given index is more than maximum index of the list) or begin (if the given index is less  
than minimum index of the list)

while working with pop() function , if we are not given any value, then it  
always remove the "last element from the list" , if we are given any value,  
the given value it always consider as "index", if the index valid that index  
element will removed from the list, otherwise pop() ,will raise an error  
called "IndexError"

while working with "remove()" function , remove always the value from  
the given , what given for remove() function , it always consider as value,  
if the given value is not found in the list, remove() function always gives  
an error called "ValueError"

if the given value is not found in the given list, then count() function will  
return always "zero" as result

if the given value is not found in the given list, then index() function will  
always gives "IndexError"

**flatten the list:**

flatten list means "make the list with out any nested list"

example:

```python
l1=[[10,20,30],[50,60,70]] ====> flattening ===> [10,20,30,50,60,70]
```

**code:**

```python
l1=[[10,20,30],[40,50,60],100,200,300,"hello",(10,20,30)]
result=[]
for i in l1:
    if f'{i}'[0]=='[':
        result+=i
    elif f'{i}'[0]=='(':
        result+=[*i]
    else:
        result+=[i]
print(result)
```

---

## Working with Tuples

**on tuple we can able to apply the following built-in functions:**

1.max()  
using this function we can able to get the maximum element in the given  
tuple  
2.min()  
using this function we can able to get the minimum element in the given  
tuple  
3.sum()  
using this function we can able to get the sum of the all elements of the  
given tuple  
4.len()  
using this function we can able to "total number of elements of the given  
tuple"  
5.sorted()  
using this function we can able to "sort the given tuple elements either in  
ascending order or descending order" and this function will work on any  
iterable , but it always return the result as list  
6.reversed()  
using this function we can able to "Reverse the given tuple"  and reversed() always returns result as "object" form, in order to see the result again we need to convert into list  using tuple() function  
reversed() we can able apply only  on "sequence data types"

**example:**

```python
t1=(10,20,30,40,50,60)
print(max(t1))
print(min(t1))
print(sum(t1))
print(len(t1))
print(sorted(t1))
print((*reversed(t1),))
```

**working with  tuple class functions:**

in python, tule is built-in class  
when we create the tuple with some name, the name is referred as "object  
of the tuple"  
when we want to know the all functions or method of the tuple in python,  
we will use a function in python called "dir()"

syntax:  
dir(tuple)   or dir(object\_name or tuple\_name)

example:

```python
print(dir(tuple))
t1=()
print(dir(t1))
```

**in python, we will have only two function from the tuple class:**

1) index() ==\> to get the index of the given element from the tuple  
2) count()==\> to get the given element is present how many times in  
given tuple

**example:**

```python
t1=(10,20,30,40,20,30,40,50,10)
print(t1.index(10))
print(t1.index(50))
print(t1.count(10))
print(t1.count(100))
```

**example:**

```python
t1=1,
print(t1)
t2=1,2,3,4,5,6,7,8,9,10
print(t2)
t3=[1,2,3],[4,5,6]
print(t3)
t4='a','b','c'
print(t4)
```

**while working with lists and tuples, we need to remember the following:**

1) we can able to combine the two lists or tuple using "+" operator  
2)  we can able to repeat the data of the list or tuple by multiplying with  
given number, where number represents "number of times to repeat"  
3) we cab able to un-pack the data of the list or tuple using "\*" operator

**example:**

```python
t1=(10,20,30,40,50)
t2=(10,20,30,40)
print(t1+t2)
print((*t1,*t2))
t1=[10,20,30,40,50]
t2=[10,20,30,40]
print(t1+t2)
print([*t1,*t2])
```

**example:**

```python
t1=(10,20,30,40,50)
print(t1*3)
t1=[10,20,30,40,50]
print(t1*3)
```

---

## Working with Strings

**on string we can able to apply the following built-in functions:**

1.max()  
using this function we can able to get the maximum character in the given  
string  
2.min()  
using this function we can able to get the minimum character in the given  
string  
3.len()  
using this function we can able to "total number of characters of the given string"  
4.sorted()  
using this function we can able to "sort the given string characters either in ascending order or descending order" and this function will work on any  
iterable , but it always return the result as list  
5.reversed()  
using this function we can able to "Reverse the given string"  and reversed() always returns result as "object" form, in order to see the result again we need to convert into result into list or tuple  
reversed() we can able apply only  on "sequence data types"

**example:**

```python
s1="hello"
s2="hai"
print(len(s1))
print(len(s2))
print(max(s1))
print(max(s2))
print(min(s1))
print(min(s2))
print(sorted(s1))
print(sorted(s2))
print(*reversed(s1),sep="")
print(*reversed(s2),sep="")
```

on string, we can able to apply the following functions of string class called "str":

**type conversion functions of the string class called "str"**

1)  lower()  ===\> this function will convert  the given string characters  
into lower case

2) upper() ===\> this function will convert the given string characters into  
uppercase

3) swapcase()===\> this function will convert the lower case into uppercase and viceversa

4) title() ===\> this function will convert every word starting character  
of the string into uppercase

5) capitalize()===\> this function will convert the starting character of the  
string into uppercase

6) casefold() ===\> this function will convert the all characters of the  
string into lowercase

**example:**

```python
s1="hello"
print(s1.upper())
s1="HELLO"
print(s1.lower())
print(s1.casefold())
s1="heLLO"
print(s1.swapcase())
s1="hello world"
print(s1.title())
s1="hello world"
print(s1.capitalize())
```

**when we want to given string lower case or upper case or not, in python we will use the following functions:**

1)isupper()

this function will give the result True, if all characters of the string are uppercase, other wise "false"

2) islower()  
this function will give the result True, if all characters of the string are  
lowercase , otherwise "False"

**example:**

```python
s1="abc123"
print(s1.islower())
s1="122"
print(s1.islower())
s1="a1"
print(s1.islower())
s1="Aa12"
print(s1.islower())
s1="abcd"
print(s1.islower())
```

**example:**

```python
s1="ABCD"
print(s1.isupper())
s1="ABCD123"
print(s1.isupper())
s1="ABCDa"
print(s1.isupper())
s1=""
print(s1.isupper())
```

when we want to check the content type of the stirng, we will use the following functions:

1) isdigit()

to check the given all characters of string are digits or not  
this function will give the result in the form  of  Boolean

2) isspace()

to check the given string space or not  
this function will give the result in the form  of  Boolean

3)isidentifier()  
to check the given all characters of string are identifier characters  
this function will give the result in the form  of  Boolean

4) isalpha()  
to check the given all characters of string are alphabets or not  
this function will give the result in the form  of  Boolean

5) isalnum()  
to check the given of string are digits or alphabets or both or not  
this function will give the result in the form  of  Boolean

**example:**

```python
s1="1234"
print(s1.isdigit())
s1="a1234"
print(s1.isdigit())
s1="1234abc"
print(s1.isdigit())
```

**example:**

```python
s1="hello"
print(s1.isalpha())
s1="hello123"
print(s1.isalpha())
s1="hello   "
print(s1.isalpha())
s1="hello   123"
print(s1.isalpha())
s1="helloHELLO"
print(s1.isalnum())
s1="helloHELLO123"
print(s1.isalnum())
s1="12345"
print(s1.isalnum())
s1="helloHELLO_"
print(s1.isalnum())
```

**example:**

```python
s1=""
print(s1.isspace())
s1=" "
print(s1.isspace())
s1="                  "
print(s1.isspace())
s1="         123"
print(s1.isspace())
```

**example:**

```python
s1="hello"
print(s1.isidentifier())
s1="_hello"
print(s1.isidentifier())
s1="hello_"
print(s1.isidentifier())
s1="123"
print(s1.isidentifier())
s1="a123"
print(s1.isidentifier())
```

**the other string class (str) functions of the python are:**

**1) count() :**

using this function, we can able to find the given string is repeated how  
many times in the complete string

**example:**

```python
s1="hello world"
print(s1.count(''))
print(s1.count("h"))#1
print(s1.count("l"))#3
print(s1.count("L"))
print(s1.count("r"))#1
```

**2) index():**

using this function, we can able to find the given string index in the whole  
string, if the given string is not found, this function will raise an error  
called  "ValueError"

**example:**

```python
s1="hello world"
print(s1.index("l"))
print(s1.index(""))
```

**3) lstrip():**

lstrip() is used to remove the all spaces of the string from beginning or  
any given string from the starting of the string, if given string present

while using "lstrip()", if given string is not found at beginning, if always

```python
return the same string
```

while using "lstrip()", if we are not given any value or data in the function ,  
lstrip() always remove only spaces from the string at beginning, if string  
contain spaces

**example:**

```python
s1="hello"
s2=s1.lstrip()
print(s2)
s1="    hello"
s2=s1.lstrip()
print(s2)
```

**example:**

```python
s1="hello world"
s2=s1.lstrip("e")
print(s2)
s1="hello world"
s2=s1.lstrip("eh")
print(s2)
s1="hello world"
s2=s1.lstrip("ehl")
print(s2)
s1=" hello world"
s2=s1.lstrip("ehlo ")
print(s2)
s1="hello world"
s2=s1.lstrip("ehlo w")
print(s2)
s1="hello world"
s2=s1.lstrip("ehlo wrd")
print(s2)
```

4) rstrip()

rstrip() is used to remove the all spaces of the string from  ending or  
any given string from the ending of the string, if given string present  
at ending of the string

while using "rstrip()", if given string is not found at ending, it always  
return the same string as result

while using "rstrip()", if we are not given any value or data in the function ,  
rstrip() always remove only spaces from the string at ending, if string  
contain spaces

**example:**

```python
s1="hello      "
print(len(s1))
print(s1.rstrip())
print(len(s1.rstrip()))
```

**example:**

```python
s1="hello world"
print(s1.rstrip("r"))
print(s1.rstrip("d"))
print(s1.rstrip("rld"))
print(s1.rstrip("orldw "))
print(s1.rstrip("orldw e"))
```

**strip():**

strip() means " lstrip()+ rstrip()"

strip() is used to remove the all spaces of the string from  ending or starting of the  any given string, if string  contains spaces at starting or at ending or at both , then strip() function will remove  spaces

while using "strip()", if given string is not found at ending or starting or  
both , it always return the same string as result

while using "strip()", if we are not given any value or data in the function ,  
strip() always remove only spaces from the string  from starting or ending  
or both , if string contain spaces

**example:**

```python
 s1="hello world"
print(s1.strip())
s1="    hello world"
print(s1.strip())
s1="hello world      "
print(s1.strip())
s1="        hello world       "
print(len(s1))
print(s1.strip())
print(len(s1.strip()))
```

**example:**

```python
s1="hello world"
print(s1.strip())
print(s1.strip("h"))
print(s1.strip("hd"))
print(s1.strip("hdel"))
print(s1.strip("hdelwr o"))
```

**6) replace() :**

using this function we can able to replace the given string in the whole  
string , based on the given source string

this function will replace all possible matches of the given string , in the  
whole string

this function will also take a "number" as input and this number will tell  
how many times we can able to replace the given string ,if we are not given any number , then it will replace all possible matches of the given  
string

**example:**

```python
s1="hello world"
print(s1.replace("l","L"))
print(s1.replace("d",""))
print(s1.replace("ld",""))
print(s1.replace(" world",""))
print(s1.replace("l","L",1))
print(s1.replace("l","L",2))
print(s1.replace("l","L",30000))
```

**7) join() :**

join() function is used to add the given character or symbol between the  
characters of the given string

this function we can also use with "tuple or set or list", when the data inside the list or tuple or set must be string or character , other wise  
this function will raise an error

this function always add the given character or symbol , only in between  
the alphabets or characters, not at the starting or ending of the string

**code:**

```python
s1="hello world"
print(",".join(s1))#h,e,l,l,o, ,w,o,r,l,d
s1="1,2,3,4,5"
print("".join(s1))#1,2,3,4,5
s1=["1","2","3","4"]
print("".join(s1))#1234
s1=("1","2","3","4")
print("-".join(s1))#1-2-3-4
s1={"1","2","3","4"}
print("-".join(s1))#2-1-4-3
```

**8) format()**

format() function is used to display the output of the given data and text  
, mostly this is used for output formatting

**9) split()**

using this function we can able to split the given string into list of string

given                                     convert into  
string ===\> to the split() function  ==========\> list of words , where the words are separated by the split() function based on the given delimiter

while using split() function , if we are not given any delimiter , then split()  
function will take default delimiter as "space"

here delimiter means "on what basis split() function will divide the given  
string into list of words"

**example:**

```python
s1="hello world"
print(s1.split())
s1="hello world"
print(s1.split("o"))
s1="hello world"
print(s1.split("r"))
```

**example:**

```python
s1="hello world"
print(s1.split("l"))
s1="lhello world"
print(s1.split("l"))
s1="lhello worldl"
print(s1.split("l"))
s1="hello worldl"
print(s1.split("l"))
s1="hellllo worldl"
print(s1.split("l"))
```

**10. startswith():**

in python, when we want to check the given string is starting or not, in  
python we will use this function  
this function will return "True", if the given string is starting string  
this function will return "False", if the given string is not a starting string

**example:**

```python
s1="hello world"
print(s1.startswith("he"))
print(s1.startswith("He"))
print(s1.startswith("world"))
```

**11.endswith():**

in python, when we want to check the given string is ending or not, in  
python we will use this function  
this function will return "True", if the given string is ending string  
this function will return "False", if the given string is not a ending string

**example:**

```python
s1="hello world"
print(s1.endswith("he"))
print(s1.endswith("He"))
print(s1.endswith("world"))
print(s1.endswith("d"))
print(s1.endswith(""))
```

**12. find():**

using this function, we can able to find the given string present or not in  
the entire string  
if the given  string is present the whole string,  then this function always  
return "first occurrence string index"  
if the given string is not present in the whole string, then this function  
always return "-1" as result

when we want to search the given string is present or not in python we  
will have the following:

1) using in and not in

2) index()

3) startswith()

4) endswith()

5) find()

**example:**

```python
s1="hello world"
print(s1.find("llo"))
print(s1.find("llohe"))
print(s1.find("hello"))
print(s1.find("llold"))
s1="hello world"
print(s1.find(""))
```

anagram means "both strings must have same kind of characters or letters, where letters frequency also must be same, where given strings  
length must be same, order of letters does not important in the given  
two strings"

**example:**

```python
s1=input("s1:")
s2=input("s2:")
l1=0
l2=0
```

for \_ in s1:l1+=1  
for \_ in s2:l2+=1

```python
s1={*s1}
s2={*s2}
l3,l4=0,0
```

for \_ in s1:l3+=1  
for \_ in s2:l4+=1

```python
if l1==l3 and l2==l4:
    print("anagram") if s1==s2 else print("not anagram")
else:
    print("not anagram")

or
s1=input("s1:")
s2=input("s2:")
d1,d2={},{}
l1=0
l2=0
```

for \_ in s1:l1+=1  
for \_ in s2:l2+=1

```python
for i in s1:
    if i in d1:
        d1[i]+=1
    else:
        d1[i]=1
for i in s2:
    if i in d2:
        d2[i]+=1
    else:
        d2[i]=1
print("anagram") if d1==d2 else print("not anagram")
```

---

## Working with Sets

**on sets, we can able to apply the following functions:**

1. max()  
this function will give the " maximum element of the set "  
2.min()  
this function will give the "minimum element of the set"

3.sum()  
this function will give the "sum of the elements of the set"

4.sorted()  
this function will give the "ascending or descending order of the set"  
as list

5.len()  
this function will give the "total number of elements inside the set"

**example:**

```python
s1={1,2,3,4,5,6,7,8,9,10,-1,-2,-3,0}
print(max(s1))
print(min(s1))
print(sum(s1))
print(sorted(s1))
print(len(s1))
```

in python, set class name is "set"

**in "set" class , we will have the following functions:**

1) add()  
when we want to add the any new element into the set, we will use this  
function  
2) copy()  
when we want to copy the data from the one set to another  
3) discard()  
when we want to discard or remove the element from the set , this function  will never going this give any error, if the given element is not  
present in the whole set  
4) remove()  
when we want to remove the element from the set , this function will going to give error, if the given element is not present in the whole set, otherwise remove the given element from the set

**example:**

```python
s1={1,2,3,4,5,6,7,8,9,10,-1,-2,-3,0}
s1.discard(200)
s1.discard(-20)
s1.discard(10)
print(s1.discard(4))
print(s1)
```

**example:**

```python
s1={1,2,3,4,5,6,7,8,9,10,-1,-2,-3,0}
s1.remove(10)
print(s1)
s1.remove(1)
print(s1)
```

**example:**

```python
s1={1,2,3,4,5,6,7,8,9,10,-1,-2,-3,0}
s1.remove(10)
print(s1)
s1.remove(1)
print(s1)
s1.remove(0)
print(s1)
```

**5) union():**

using this function we can able to get the "Combined set as result of multiple sets, union means combine the multiple sets into single set, where it will not consider the duplicate elements while union operation"

in python, we can able to apply the union using "\|" operator

**example:**

```python
s1={1,2,3,4,5,6,7,8,9,10,-1,-2,-3,0}
s2={1,2,3,4,5}
print(s1|s2)
print(s1.union(s2))
```

**6) intersection() :**

intersection means "getting the common elements or data from the given  
two sets"  
when we want to perform intersection of the given two sets, in python  
we will use this function  
when we want to perform "intersection of the given two sets", we will use  
an operators called "&"

**example:**

```python
s1={1,2,3,4,5,6,7,8,9,10,-1,-2,-3,0}
s2={1,2,3,4,5}
print(s1&s2)
print(s1.intersection(s2))
```

**7) intersection\_update() :**

using this function also , we can able perform the "intersection of the given two sets" and make the result as "result any one of the set", based  
on the given  order  
this function does not return any result as a set, but simply update the  
any one of the given sets as result of the intersection  after the intersection

**example:**

```python
s1={1,2,3,4,5,6,7,8,9,10,-1,-2,-3,0}
s2={1,2,3,4,5}
s1.intersection_update(s2)
print(s1)
```

**8) difference():**

difference means "getting the  elements of only set  and eliminate which are common in both"  
when we want to perform difference of the given two sets, in python  
we will use this function  
when we want to perform "difference of the given two sets", we will use  
an operators called "-"

**example:**

```python
 s1={1,2,3,4,5,6,7,8,9,10,-1,-2,-3,0}
s2={1,2,3,4,5}
print(s1.difference(s2))
print(s1-s2)
```

**9)difference\_update():**

using this function also , we can able perform the "difference of the given two sets" and make the result as "result any one of the set", based  
on the given  order  
this function does not return any result as a set, but simply update the  
any one of the given sets as result of the difference  after the difference  
operation

**example:**

```python
s1={1,2,3,4,5,6,7,8,9,10,-1,-2,-3,0}
s2={1,2,3,4,5}
s1.difference_update(s2)
print(s1)
```

**10) symmetric\_difference():**

this function will used to perform the  "symmetric difference of the given  
two sets"  
when we perform symmetric difference of the given two sets, it always  
return only "unique elements of the given two sets as a result or it will  
return the elements which are not common in the both sets"

this is exact opposite to "intersection"  
in python , we can also do this operation using "^" operator

**example:**

```python
 s1={1,2,3,4,5,6,7,8,9,10,-1,-2,-3,0}
s2={1,2,3,4,5,100,200}
print(s1-s2)
print(s1.difference(s2))
print(s1^s2)
print(s1.symmetric_difference(s2))
```

**11) symmetric\_difference\_update():**

when we want to perform the symmetric difference of the given two sets  
and make any one of the set as "Result of symmetric difference" , then we  
we will use this function

**example:**

```python
s1={1,2,3,4,5,6,7,8,9,10,-1,-2,-3,0}
s2={1,2,3,4,5,100,200}
s1.symmetric_difference_update(s2)
print(s1)
s1={1,2,3,4,5,6,7,8,9,10,-1,-2,-3,0}
s2={1,2,3,4,5,100,200}
s2.symmetric_difference_update(s1)
print(s2)
s1={1,2,3,4,5,6,7,8,9,10,-1,-2,-3,0}
s2={1,2,3,4,5,100,200}
s1=s1^s2
print(s1)
```

12) issubset()  
using this function we check given set is sub set or not  
if the given set is "sub set", then this function will return "true", otherwise  
false \`

**example:**

13) issuperset()  
using this function we check given set is super set or not  
if the given set is "super set", then this function will return "true", otherwise false

**example:**

```python
s1={1,2,3,4,5,6,7,8}
s2={3,4,5,6,7,8}
print(s1>=s2)
print(s1.issuperset(s2))
print(s2>=s1)
print(s2<=s1)
print(s2.issubset(s2))
print(s2.issubset(s1))
```

14) isdisjoint()  
using this function we check given set are disjoints or not  
if the given two sets are "disjoint", then this function will return "true", otherwise false  
when we say any two sets are "disjoint", then their intersection is  always  
"empty set"

**example:**

```python
a={1,2,3,4,5}
b={3,4,5}
c={10,20,30}
print(a&b)
print(a.isdisjoint(b))
print(b&c)
print(b.isdisjoint(c))
print(a&c)
print(a.isdisjoint(c))
```

**15) update():**

using this function, we can able to add the new elements into sets  
when we are using this function, the data always we need to take as  
"iterable" format  
it means the data always need to be "list, tuple , range(), string,........."

**example:**

```python
 a={1,2,3,4,5}
a.update("100")
print(a)
a.update([10,20,30,40,50])
print(a)
a.update((1,2,3,4,5))
print(a)
a.update({100,20,30,40})
print(a)
```

**16)clear()**

using this function we can able to remove the all elements from the set

**example:**

```python
a={1,2,3,4,5}
a.clear()
print(a)
```

**17.copy():**

using this function, we can able to copy the list data into another list

**example:**

```python
a={1,2,3,4,5}
b=a.copy()
print(b)
```

in python, sets are mutable, it means on sets, we can do insert or delete  
operation

when we want to make the set as "immutable", then the set can not allow  
operations like insert or delete , for making set as immutable in python  
we will use a function called "frozenset()" , frozenset is a set , which does  
not allow any changes

when we take any data for frozen set , always we need to give the data  
as "iterable"  format

**example:**

```python
a={1,2,3,4,5,6,7,8,9,10}
a=frozenset(a)
print(a)
b={10,20,30,40,50}
print(a|b)
print(a.intersection(b))
print(a^b)
print(a-b)
```

**when the set is "frozen set", we can able to apply the following operations:**

1) union  
2) intersection  
3) difference  
4) symmetric difference

---

## Working with Dictionaries

**on dictionary , we can able to apply the following built-in functions:**

1) max()  
this function will return  "maximum key" as a value  
2) min()  
this function will return "minimum key" as a value  
3) sum()  
this function will give the "sum of keys (Where keys are numeric,  
otherwise it will give error)  
4) len()  
this function will return "number of key and value pairs" of the  
dictionary  
5) sorted()  
this function will give the all keys in the either in ascending order or  
descending order  
in python dictionary , dictionary key can be "number or string" only  
in python dictionary , value can be anything  
in python dictionary , when we want to access the any value from the  
dictionary , we will use the following syntax:  
dictionary\_name\[key\_name\]  
if the given key is not present while accessing any value via key, then python will give an error

**example:**

```python
d1={1:2,3:4,5:6,7:8,9:10}
print(d1[1])
print(d1[9])
print(d1[5])
print(max(d1))
print(min(d1))
print(sum(d1))
print(sorted(d1))
```

in python,  
dictionary is mutable  and dictionary is "non-sequence type"  
dictionary is "ordered collection"

**on python dictionary, we can able to apply the following operations:**

1) insert  
2) update  
3) delete  
4) search

**1) insert:**

when we want to insert the data into dictionary , we will use  key  
if the given key is present in the dictionary , then it become update operation  
if the given key is not present in the dictionary, then it will insert key and  
value pair at the end of the dictionary

**example**

```python
d1={1:2,3:4,5:6,7:8,9:10}
d1[1]=100
print(d1)
d1[11]=1100
print(d1)
d1[13]=1300
print(d1)
```

**2.update:**

when we want to update the data in dictionary , we will use  key  
if the given key is present in the dictionary , then it become update operation  
if the given key is not present in the dictionary, then it will insert key and  
value pair at the end of the dictionary

**example:**

```python
d1={1:2,3:4,5:6,7:8,9:10}
d1[1]=100
print(d1)
d1[3]=1100
print(d1)
d1[13]=1300
print(d1)
```

**3.delete operations:**

when we want to delete the data from the dictionary, we will use the key  
syntax:

```python
    del dictionary[key_name]
```

if the key is not present while using  "Del" for delete, then it will raise an  
error , otherwise it will simply given key and value pair from the dictionary  
example:

```python
d1={1:2,3:4,5:6,7:8,9:10}
del d1[1]
print(d1)
del d1[9]
print(d1)
```

**example:**

```python
d1={1:2,3:4,5:6,8:9,9:10}
d1[10]=1000
print(d1)
d1[1]=200
print(d1)
```

when we want to delete the data from the dictionary, we will use the

**following functions:**

1) pop()  
using this function  we can remove the any key and pair always using  
key, if the given key is not present , pop() will raise an error

2) popitem()  
using this function we can remove key and value pair from the  
dictionary and this function always remove the key and value from the  
end of the dictionary

**example:**

```python
d1={1:2,3:4,5:6,8:9,9:10}
d1.pop(1)#here 1 means key
print(d1)
d1.pop(3)#here 3 means key
print(d1)
```

**example:**

```python
d1={1:2,3:4,5:6,8:9,9:10}
d1.popitem()
print(d1)
d1.popitem()
print(d1)
```

to remove the all key and value pairs from the dictionary , we will use  
a function called  "clear()"

**example:**

```python
d1={1:2,3:4,5:6,8:9,9:10}
d1.clear()
print(d1)
```

when we want get the only keys of the dictionary , in python we will use  
a function called "keys()"  
when we want to get the only values of the dictionary, in python we will  
use a function called "values()"  
when we want  to get the both  keys and value pairs of the dictionary, in  
python we will use function called "items()"

**example:**

```python
d1={1:2,3:4,5:6,8:9,9:10}
print(d1.keys())
print(d1.values())
print(d1.items())
```

when we want to copy the dictionary data into another dictionary , in python we will use a function called "copy()"

**example:**

```python
d1={1:2,3:4,5:6,8:9,9:10}
d2=d1.copy()
print(d2)
print({**d1})
```

when we want to access the any data from the dictionary based on the  
given key, we will use a function called "get()", if given key is not found,  
then this function will return  "None" as output  
instead of None, we can able to return any value by using following  
syntax:

```python
                    dictionary_name.get(key)
```

or  
dictionary \_name.get(key,value)

the value what we given in the function , will come as a output , when the  
given key is not found , generally, if the given key is not found, then get()  
always return "None" , otherwise given value in the get(), if the given  
key present, then what value the given key is having  in the dictionary , get() will return as a result

**example:**

```python
d1={1:2,3:4,5:6,8:9,9:10}
print(d1.get(1))
print(d1.get(10))
print(d1.get(10,100))
print(d1.get(12,1000))
print(d1.get(3,300))
```

in dictionary , we will have a function called "fromkeys()", using this function with help of given iterable, we can able to create the each element  of the iterable consider as "key" and every key it will assign the  
same value

**example:**

```python
d1={}
d1=d1.fromkeys([1,2,3,4,5,6],100)
print(d1)
d1={}
d1=d1.fromkeys("hello",100)
print(d1)
d1={}
d1=d1.fromkeys(range(10,100,10),100)
print(d1)
```

in dictionary , we will have a function called "setdefault()"  
when we given any key and value with setdefault() function , setdefault()  
check first given key is there or not, if given key is present, then it will return given key value as result.

if the given key is not present, then it will insert the given key and value into dictionary and return the value as result , while using setdefault(), we given only key with out value.

if key is not present in the dictionary , then setdefault() will insert the key with "None" as value, return "None" as result

**example:**

```python
d1={1:2,2:3,3:4,4:5,1:10}
print(d1)
d1={1:2,1:3,2:4,1:4,1:5}
print(d1)
```

---

## Python Functions

function is a "collection or a block of statements", which is used to perform  a specified task  in the program

in python functions are used to avoid the "code duplication", it means  
when we create the any code as a function , then the code can be re-used  
as many times wherever we want inside the program by just calling the function

in Python , with help of functions, we can able to divide the python program into "n" number of parts or modules as a functions

in python, when we make any code as function , then the functions can be  
re-used inside the another python, when we make the any code as a function, then functions can able export to another python file using a  
concept called "module"

**in Python, we will have two types of functions:**

1) built-in function  
the functions which are given python  
example: int(), str(), print(), input(), list(), tuple(),max(),min()

2) user-defined function or custom function  
any function which is created by programmer or developer in python, then the function is called as "user-defined" function

**in python, we can able to create the user-defined functions in the following ways:**

1) using "def" keyword  
any function we create using "def", then the function is called as "  
named  function", when we create the any function  with  "def", we  
always give the name  
the function what we create using "def" keyword  ,the  function is also  
called as "multi-line function"

in python, we can create the  "user-defined" function using following

**syntax:**

```python
def user_defined_function_name(arg1,arg2,arg3,arg4,.......argn):
         #write the code here
```

when we create the function with "def" keyword, the function may take  
the arguments  
arguments are "data", which are act like a input to the functions  
when we give the arguments while creating the function , the arguments of the function can get via "function calling"

**what is mean by function calling:**

function calling means "Executing the function" , because when we create  
the function , the function will not execute when we run the program , the  
functions which are created inside the program, are executed only when  
we call the function  
when we want to call the function , we always use "name of the function"  
syntax:

```python
               function_name(val1, val2,val3,.......valn)
```

the values inside the function  call, we give only when we have arguments  
inside the function

**example:**

```python
def display():
    """here display is function
    name"""
    print("this is my first function!")
#call the function
display()
display()
display()
```

**in python, we can able to create the function in the following ways:**

**1) function without arguments and without return type:**

in this model, function will not create with any arguments and after the  
function execution , function will not return any result

**example:**

def sum():#here no arguments in the function

```python
  a=int(input("a:"))
  b=int(input("b:"))
  print(a+b)
#calling the funciton sum()
sum()
```

**2) function with arguments and without return type :**

in this model, function will create with arguments and after the  
function execution , function will not return any result

**example:**

```python
def square(x):#x=a
    print(x**2)
a=int(input("x:"))
square(a)
```

**3) function with arguments and with return type**

in this function will take arguments and after the function execution ,  
function will return result

after the function  execution, function will return any result using a keyword called "return"

in python,  
return keyword can able to return  "Zero or more values"

return statement "always we write at end of the function", because once the return  statement  of the  function execution will done, the code  
after return will not be executed

if any return statement is executed inside the function, the code what we  
write after the return will not be executed , because of this return often  
called "function exit statement" and the control will from "return statement to function calling"

when the function returns any value using "return", the function return  
value will come to where we call the function , because this reason function calling  need to be done either in print() function  or we need to store the function calling inside the variable

when the return statement is returning "two or more values", then the  
function return the all values to function calling as a "Tuple" form

syntax:

```python
                 return va1, val2, val3, val4,..............valn
```

when the write only return without any value inside the function , then  
the function return "None " as a output

syntax:

```python
                             return
```

**example:**

```python
def display(x,y):
    print(x)
    print(y)
    return x+y
result=display(10,20)
print(result)
print(display(3,4))
```

**example:**

```python
def display(x,y):
    return
    print(x)
    print(y)
print(display(10,20))
```

**example:**

```python
def display(x,y):
    return x,y,x+y,x*y,x/y,x%y
print(display(3,4))
```

by default every function in will return "None" as result, if function does  
not having any return statement

**example:**

```python
def display(x,y):
    print(x)#3
    print(y)#4
print(display(3,4))
display(1,2)
```

**example:**

```python
print(print("10"))
```

**example:**

```python
print(print("10"),print("20"),print("30"))
```

**example:**

```python
print(print(print(print("10"))))
```

**4) function without arguments and with return type**

in this model, function will not take any arguments and function will return  
result after the execution

**example:**

```python
def display():
    a=int(input("a:"))#10
    b=int(input("b:"))#20
    return a+b #30
result=display() #result=30
print(result)#30
```

when we want to give the any value to the function from the function  
calling, we will use argument , argument is nothing "data to the function"  
in python, we will different types of arguments

when we are working with functions in python, the functions in python

**will take the following types of arguments:**

**1) positional arguments:**

when we say any argument in the python function is "positional argument", the arguments will take the values from the function calling  
based on the position  
if any argument in the function are positional argument, then the arguments will take the values always based on the position

**example:**

```python
def display():
    a=int(input("a:"))#10
    b=int(input("b:"))#20
    return a+b #30
result=display() #result=30
print(result)#30
```

when function is having all are positional arguments, then from the function calling we need to give values to every argument of the function ,  
otherwise we will get an error called "TypeError"

**2) keyword arguments:**

when we want to give the values to the function arguments from the  
calling, we can give in general position wise , but in python, we can give  
the values to the function arguments, using name of the argument, this  
way of giving is called as "keyword arguments"

where keyword is called as "name of the argument" , it is can not take any  
another name, if give any other name , we will get an error

**example:**

```python
def display(a,b,c):
    print(a,b,c)
display(10,20,30)
#giving the values to the arguments via keyword
display(a=100, c=200,b=1000)
display(a=10, b=200,c=30)
display(c=1000, b=2000, a=3000)
display(c=1000, b=1000,a=1000)
```

**3) default arguments:**

when we are defining the arguments in the function , we will define the  
argument with some default value, this default value will take the argument  when we are not given any value while calling the function ,

when we define the argument with some value while creating the function , then the argument is called "Default argument"

the argument will take default value, only when we are not given any value  
while calling the function , otherwise it always take the given value from  
the function calling via position or keyword (name)

**example:**

```python
def display(a=10,b=20,c=30):
    print(a,b,c)
display()
display(c=100)
display(b=123)
display(b=123,a=456)
display(c=789,a=145,b=150)
display(11,12,13)
display(int(input("a:")),int(input("b:")),int(input("c:")))
a,b,c=int(input("a:")),int(input("b:")),int(input("c:"))
display(a,b,c)
```

**4) variable length arguments:**

in general, the maximum number of arguments we can give from the  
function calling  is always equal to "the maximum number of arguments  
in the function"

when we want to give the any number of values from the function calling ,  
for any one argument, in python we need to make the argument as variable length argument , where the variable length argument can take  
any  number of values from the function calling  
in python we can make the argument as variable length argument using

**following ways:**

**1) arbitrary arguments (\*args)**

when the argument is arbitrary argument, then function can receive any  
number of values from the function calling.

if the argument is arbitrary argument , from the function calling it will  
any number values and all values it will take as "tuple" form

generally arbitrary argument will take "Zero or more values from the  
function calling"

for one function , we can able to define only one arbitrary argument

to tell the argument is arbitrary argument in the function , the name of the argument always starts with "\*" and the name we give always "\*args"

when the function argument is  "arbitrary argument", then the argument  
will never get value via "keyword" from the function calling  
when the function argument is  "arbitrary argument", then the argument  
will never get default value

**example:**

```python
def display(a,b,c,*d):
    print(a,b,c)
    print(d)
display(10,20,30,40,50,60,70,80,90,100)
display(10,20,30)
display(10,20,30,40,50,60,70,80,90)
```

**example:**

```python
def display(a=10,b=20,c=30,*d):
    print(a,b,c)
    print(d)
display()
display(100)
display(100,200)
display(a=100,b=200,c=300)
display(101,201,301,401,501,1000)
```

**2) keyword arbitrary arguments(\*\*kwargs)**

it is same as  "Arbitrary argument"  
when we define the any argument as "keyword arbitrary argument" in the function  , then the argument will take any number of values from the function calling as a key and value pair and these values will taken by keyword arbitrary argument as a "dictionary"

for one function , we can take one keyword arbitrary argument

to make the argument as "keyword arbitrary argument" , we will use  
"\*\*"before the name of the argument, in general we can take any name, but we will prefer always name of the keyword arbitrary argument as "\*\*kwargs"

**example:**

```python
def display(a,b,c,**kwargs):
    print(a,b,c)
    print(kwargs)
display(10,20,30)
display(a=100, b=200,c=300, a1=1,b1=10,c1=2)
display(100,200,300,a1=10,b1=20,c1=30,d1=40)
```

**example:**

```python
def display(a=10,b=20,c=30,**kwargs):
    print(a,b,c)
    print(kwargs)
display()
display(a1=10,b1=20,c1=30,d1=40)
display(a=101,a3=400,b=201,c=300,a2=100,b2=300,c2=300)
display(1000,kwargs={1:2,3:4,5:6})
```

for a function ,  
we can define both arbitrary and keyword arbitrary arguments

**example:**

```python
def display(*args,**kwargs):
    print(args)
    print(kwargs)
display()
display(10)
display(a=100)
display(10,20,30,a=100,b=220)
```

**5) position-only arguments :**

when we are defining the arguments inside the function , we specify  
any symbol called "/", then the arguments what we have before the "/"  
are called as "position only arguments", those gets value always via position not via "keyword" from the function calling

**example:**

```python
def display(a,b,c,/,d,e,f):
    print(a,b,c,d)
    print(e,f)
display(10,20,30,40,50,60)
display(10,20,30,d=40,f=60,e=50)
```

**6) keyword only arguments**

when we are defining the arguments inside the function , we specify  
any symbol called "\*", then the arguments what we have after the "\*"  
are called as "keyword only arguments", those gets value always via keyword not via "position" from the function calling

**example:**

```python
def display(a,b,c,*,d,e,f):
    print(a,b,c,d)
    print(e,f)
display(10,20,30,e=40,d=50,f=60)
display(10,20,30,d=40,f=60,e=50)
```

**rules to give the arguments in the function or function calling:**

1) when we have positional arguments and default arguments in the  
function, we always give the  first positional arguments and then  
default arguments  
2) when we have positional arguments and arbitrary arguments in the  
function , it better to give arbitrary arguments after  positional  
arguments or give the values to the positional arguments via keyword

3)when we have positional arguments, arbitrary argument, keyword  
arbitrary  argument, then we give always gives first positional  
arguments, and then arbitrary arguments, and then keyword arbitrary  
arguments in the function  
4) when we have positional, default, arbitrary, keyword arbitrary  
arguments, first we always give "positional, and then default, and then  
arbitrary, and then keyword arbitrary arguments in the function  
5) in the function calling, we always gives values, then we will give keyword  
with values, we can not give mixed order , always first values and then  
the value with keyword, while giving from the function call to function

2) using "lambda" keyword  
any function we create using "lambda" keyword in python, the function  
is called as "anonymous function" (function without any name)  
the function what we create using lambda keyword is also called as "  
single line function or inline function"

syntax:

lambda arg1, arg2, arg3, ...argn: expression

the lambda function can take any number of arguments  
the lambda function can also create with out arguments also  
the lambda function always takes only one line as code  
the lambda function always return result , except we write the  print()  
statement as code.

**example:**

```python
result=lambda:print("this is my first lambda function!")
result()
result=lambda a,b:print(a+b)
result(10,20)
result=lambda a,b,c:print(a*b*c)
result(10,20,30)
```

**example:**

```python
result=lambda a,b,c:a+b+c
print(result(10,20,30))
result=lambda:10*20*3/4*3
print(result())
result=lambda:2**3**2
print(result())
result=lambda:2*3*2//4*5*3/2*4
print(result())
result=lambda:2*3*2//3*2**2*3//4*2**3
print(result())
result=lambda:2**3**2//4**2*4//2*3
print(result())
result=lambda:2*3*4//3**3*4*2**3//5**2*2+100
print(result())
```

**inner functions or nested functions or closures**

in python, we can able to create the a function inside the another function  
the function what we create the inside the another function is called as  
inner or nested function

in python, in a function , we can able to create any number of  inner  
functions  or nested functions

when we create the inner function, we always need to call the inner  
function where we create the inner function , otherwise we can not able to  
call or execute inner function

inner function can able to access the outer function data, but outer function can not able to access the inner function data

when the outer function  is having inner functions, then the inner functions can also called outside the outer function , by exporting the inner functions outside the outer function , in order to export the inner  
function outside the outer function we will use "return" keyword

**example:**

```python
def outer():
    def inner1():
        print("this is inner1 function!")
    def inner2():
        print("this is inner2 function!")
    def inner3():
        print("this is inner3 function!")
    def inner4():
        print("this is inner4 function!")
    inner1()
    inner2()
    inner3()
    inner4()
outer()
```

**example:**

```python
def outer(a,b): #a=10,b=20
    def inner1():
        print("this is inner1 function!")
        print(a+b)
    def inner2():
        print("this is inner2 function!")
        print(a*b)
    def inner3():
        print("this is inner3 function!")
        print(a/b)
    def inner4():
        print("this is inner4 function!")
        print(a%b)
    inner1()
    inner2()
    inner3()
    inner4()
outer(10,20)
```

**example:**

```python
def outer(a,b): #a=10,b=20
    def inner1(x):#x=100
        print("this is inner1 function!")
        print(a*x+b*x) #3000
    def inner2(y):#y=200
        print("this is inner2 function!")
        print(a*b+y)#400
    inner1(100)
    inner2(200)

outer(10,20)
```

**example:**

```python
def outer():
    def inner1():
        print("this is inner1")
    def inner2():
        print("this is inner2")
    return inner1, inner2
inner1,inner2=outer()
inner1()
inner2()
```

**example:**

```python
def display(x):
    return lambda y:x*y
result=display(10)
print(result(20))
```

**example:**

```python
def outer(x):
    def inner1(y):
        return lambda z:x*y*z
    return inner1
result=outer(11)
result2=result(12)
print(result2(13))
```

**example:**

```python
def outer(a):
    def inner1(y):
        def inner2(x):
            return lambda z:x*z+y*3+a*20
        return inner2
    return inner1
r1=outer(9) #x=2,y=3,a=9,z=12 r1=>inner1
r2=r1(3) #r2==> inner2
r3=r2(2)
r4=r3(12)
print(r4)
```

**example:**

```python
def outer(a):
    def inner1(p):
        def inner2(q):
            return a*q
        return p*inner2(8)
    return lambda x:lambda y:lambda z:z*inner1(3)
r1=outer(2) #a=2,p=4,q=5,x=6,y=7,z=9
r2=r1(6)
r3=r2(7)
r4=r3(9)
print(r4)
```

**example:**

```python
def outer(x,y,z):#x=4,y=5,z=6
    def inner1(a,b):
        a+=10 #a=11
        b+=20#b=22
        def inner2(d,e):
            d+=a  #d=18
            e+=b #e=30
            def inner3(r):
                return x*a+r*b+z*d+e
            return inner3
        return inner2
    return inner1
r1=outer(4,5,6) #x=4,y=5,y=6,a=1,b=2,d=7,e=8,r=3
r2=r1(1,2) #inner1(1,2)
r3=r2(7,8) #inner2(7,8)
result=r3(3)
print(result)
```

---

## Recursion

recursion means  implementing the "recurrence relation"  
if we say any relation is  "Recurrence", then relation can used recursively  
for getting the result , these recurrence relations can be implemented  
in python using function  
if any function can implement any recurrence relation , then we can call  
the function "recursive function", the recursive function can able to call  
by itself  
call by itself is called "recursion"  
recursion making the function can call by itself

in python, we can implement the recursive function using "Def" keyword  
when we are working with recursive functions, we always need specify  
the valid condition, otherwise it will reaches maximum depth , where  
maximum depth refers "how many times a function call by itself", in python maximum recursion  depth is not unlimited, it can be fixed size, we can able to change the maximum recursion depth using "sys" module

when we are working with recursive function , we will never use any looping statement  inside the function

**programs with recursion:**

**1) print the numbers 1 to n using recursion:**

```python
n=10
```

1 2 3 4 5 6 7 8 10

code:

```python
def display(start,n):
    if start<=n:
        print(start)
        display(start+1,n)
n=int(input("n:"))
display(1,n)
```

2. print the remove the all vowels of the string using recursion  
input: abcder  
output:  bcdr

**code:**

```python
def vowels_remove(index,length):
    if index<length:
        if string[index] not in "aeiouAEIOU":
            print(string[index],end="")
        vowels_remove(index+1, length)
string=input("String:")
length=0
```

for \_ in string:length+=1

```python
vowels_remove(0,length)
```

**3. print the maximum digit of the given number:**

**code:**

```python
def maximum_digit(maximum,num):
    #maximum=3, num=0
    if num!=0:
        if maximum<num%10:
            maximum=num%10  #maixmum=3
        maximum_digit(maximum,num//10)
    else:
        print(maximum)#3
num=int(input("number:"))
maximum_digit(0,num)#num=123
```

4. program to combine the two lists into single list without duplicates

**using recursion, without any built-in function:**

```python
l1=[1,2,3,4,5]
l2=[3,4,5,6,7,8]
result=[1,2,3,4,5,6,7,8]
code:
def merge_list(index,total,mylist,result):
    if index<total:
        if mylist[index] not in result:
            result+=[mylist[index]]
        merge_list(index+1,total,mylist,result)
    else:
        print(result)

l1=[1,2,2,3,3,4,5]
l2=[3,4,5,6,7,8]
length1=length2=0
```

for \_ in l1:length1+=1  
for \_ in l2:length2+=1

```python
merge_list(0,length2+length1,l1+l2,[])
```

**5. write a python program to find the  common maximum element of the given two lists using recursion  without using any built-in function:**

**code:**

```python
def maximum_element(index,total,mylist,result):
    #index=13, total=13,mylist=[1,2,2,3,3,4,5,3,4,5,6,7,8]
    #result=8
    if index<total:
       if result<mylist[index]:
           result=mylist[index]
       maximum_element(index+1,total,mylist,result)
    else:
        print(result)

l1=[1,2,2,3,3,4,5]
l2=[3,4,5,6,7,8]
length1=length2=0
```

for \_ in l1:length1+=1  
for \_ in l2:length2+=1

```python
maximum=l1+l2
maximum=maximum[0]
maximum_element(0,length2+length1,l1+l2,maximum)
```

6. write a python program to print the following pattern without loops,

**with using recursion, without any built-in function:**

1  
1 2  
1 2 3  
1 2 3 4  
1 2 3 4 5

**code:**

```python
def pattern(rownum,rows):
    def row(colnum,data,cpr):
        if colnum<=cpr:
            print(data,end=" ")
            row(colnum+1,data+1,cpr)
    if rownum<=rows:
        row(1,1,rownum)
        print()#new line
        pattern(rownum+1, rows)

rows=int(input("Rows:"))
pattern(1,rows)
```

7.write a python program to print the following pattern without loops,

**with using recursion, without any built-in function:**

1 2 3 4 5  
1 2 3 4  
1 2 3  
1 2  
1

**code:**

```python
def pattern(rownum,rows):
    def row(colnum,data,cpr):
        if colnum<=cpr:
            print(data,end=" ")
            row(colnum+1,data+1,cpr)
    if rownum<=rows:
        row(1,1,rows-rownum+1)
        print()#new line
        pattern(rownum+1, rows)

rows=int(input("Rows:"))
pattern(1,rows)
```

8. write a python program to print the following pattern without loops,

**with using recursion, without any built-in function:**

\*  
\* \*  
\* \* \*  
\* \* \* \*  
\* \* \* \* \*

**code:**

```python
def pattern(rownum,rows):
    if rownum<=rows:
        print("* "*rownum)#new line
        pattern(rownum+1, rows)

rows=int(input("Rows:"))
pattern(1,rows)
```

**9. find the factorial of the given number using recursion:**

**code:**

```python
def factorial(num):
    if num==0 or num==1:
        return 1
    return num*factorial(num-1)
num=int(input("num:"))
print(factorial(num))
```

10.  print the fibnocii series for the given n, where n refers number of fibnocii values need to print in the result using recursion, without using looping statements:

```python
n=10
```

0 1 1 2 3 5 8 13 21 34

**code:**

```python
def fibnocii(a,b,n):
    #a=5,b=8,n=0
    if n!=0:
        print(a,end=" ")#0 1 1 2 3
        a,b=b,a+b
        fibnocii(a, b, n-1)
n=int(input("n:"))#5
fibnocii(0, 1, n)
```

11. print  the prime numbers for the given range using recursion, without

**using built-in functions and looping statements:**

start:1  
end: 20  
2 3 5 7 11 13 17 19

**code:**

```python
def prime(start,end):
    def check_prime(num,fact,count):
        if fact<=num:
            if num%fact==0:
                count+=1
            return check_prime(num,fact+1,count)
        else:
            return count
    if start<=end:
        if check_prime(start,1,0)==2:
            print(start,end=" ")
        prime(start+1,end)

start=int(input("start:"))
end=int(input("end:"))
prime(start,end)
```

12.write a python program to convert the given decimal number into

**binary using recursion, without using any looping statement:**

input:  120  
output: 1111000

**code:**

```python
number=int(input("number:"))
def decimal_to_binary(num,res):
    if num!=0:
        res=res+f'{num%2}'
        num//=2
        decimal_to_binary(num, res)
    else:
        print(res[::-1])
decimal_to_binary(number,'')
```

13.  write a python program using recursion for the following , without

**using any looping statement  and  built-in function:**

input:  1234  
output:  One Two Three Four  
input:  -100  
output: One Zero Zero

**code:**

```python
number=int(input("number:"))
words=["zero","one",'two','three','four',"five",'six',
       "seven","eight","nine"]
def number_to_text(num,res):
    #num=1 res=one two three
    if num!=0:
        res=words[num%10]+" "+res
        number_to_text(num//10, res)
    else:
        print(res)

number_to_text(number,'')
```

14 write a python program find the 2nd maximum digit in the given number using recursion , without using looping statement and built-in

**function:**

input: 128993  
output: 8

**code:**

```python
number=int(input("number:"))
def second_maximum(num,first_max,second_max):
    #num=0 first_max=9 second_max=8
    if num!=0:
        if first_max<num%10:
            second_max=first_max
            first_max=num%10
        elif second_max<num%10 and num%10<first_max:
            second_max=num%10
        second_maximum(num//10,first_max,second_max)
    else:
        if second_max!=0:
           print(second_max)
        else:
            if {*f'{number}'}=={*f'{number%10}'}:
                print(number%10)
            else:
                print(0)

second_maximum(number,0,1)
```

15. write a python program print the  words of the string using recursion,

**without using built-in function  and looping statements:**

input: "am i learning python really"  
output:  
am  
i  
learning  
python  
really

**code:**

```python
def words(str1,res):
    if str1!='':
        char=str1[0]
        if char!=" ":
            words(str1[1:],res+char)
        elif char==" " and res=='':
            words(str1[1:],'')
        else:
            print(res)
            words(str1[1:],'')
    else:
        print(res)
string=input("string:")
words(string,'')
```

17. write a python program print the all characters of the string in the  
ascending order without using any built-in function  and any sorting method, write the code using recursion, where function never contain  
any looping statements:  
input:  dabc  
output: abcd  
input: a1dcb  
output: a1bcd  
code:

```python
upper="ABCDEFGHIJKLMNOPQRSTUVWXYZ"
lower="abcdefghijklmnopqrstuvwxyz"
digits="0123456789"
def sort_characters(str1):
    if str1!='':
        if str1[0] in string:
            print(str1[0],end="")
        sort_characters(str1[1:])

string=input("string:")
sort_characters(upper+lower+digits)
```

---

## Monkey Patching

in python, when we create the function , we can able to change the function code or enhance the function code without changing the code  
directly , to change or enhance any function code in python, we will use

**the following ways:**

1) monkey patching  
2) decorators

**monkey patching**

when we want to change the any function code without changing the  
function code directly, in python we will use "monkey patching"  
in monkey patching , we can change the function  code as like how we  
change the value of variable

**how to perform  monkey patching in Python:**

syntax:

```python
function_name=new_function_name
```

when we apply the monkey patching on any function , after monkey patching the complete code of the function  will changes, it means original  
function code will replace completely by new function

**example:**

```python
def display():
    print("this is display function")
def add(a,b):
    print(a)
    print(b)
    print(f"add:{a+b}")
def sub(a,b):
    print(a)
    print(b)
    print(f"sub:{a-b}")
display()
#monkey patching
display=add
display(10,20)
#monkey patching
display=sub
display(10,20)
```

---

## Decorators

decorator is a higher order function , which takes another function as  
argument and which function it takes as argument, it will enhances and  
return enhanced function as a result, original function code always  
unchanged  
as argument                     returns  
function===========\> decorator ====\> enhanced function as result

if we say any function is higher order function , then the function always takes  another function as argument

**when we are working with decorators we will use the following terminology:**

1) wrapped function  
the function which is given as argument to the decorator,  
for enhancement, is called as "Wrapped function"  
2) wrapper function  
the function which is present inside the decorator and which is used  
to enhance the wrapped function

wrapped function==\> decorator(wrapper) ==\> enhanced function as result

**when we are working with decorators, we will use the following steps:**

step-1:  
create the wrapped function with some name

step-2:  
create the decorator with some name

step-3:  
create the wrapper function inside the decorator as inner function

step-4:  
return the wrapper as a result of the decorator

when we want to give the any decorator to the any function (wrapped  
function), in python we will use a symbol called "@" symbol , when  
we want to decorator using "@", we will use the following syntax:

```python
@decorator_name
def wrapped_function_name(arg1, arg2,arg3,..............argn):
            #write the logic here
```

for a one function (wrapped function), we can able to give any number of  
decorators, when we give the "two or more decorators" at a time to  
a function(wrapped function), then we will say it as "chain of decorators"

when we give the "chain of decorators(two or more decorators)", then  
all decorators will be called "from bottom to top" order by the wrapped  
function

when we are working with "chain of decorators", wrapper function of  
one decorator can able to share the "Data" to another decorator , when  
the data is common for the all decorators using "return"

**Decorator Coding Template:**

```python
#create the decorator
```

def decorator\_name(func\_name):(step-2)  
def wrapper\_function\_name(): (step-3)

```python
        pass
    return wrapper_function_name (step-4)
#create the wrapped function (step-1)
def wrapped_function_name():
    pass
```

**example:**

```python
def artist(func):
    def makeup():
       func() #devil()
       print("artist start the patchwork!")
       print("1000 hours after!")
       print("Devil look like angel!")
    return makeup
@artist
def devil(): #devil+makeup===> angel
    print("Now i am looking like Pure Devil!")
devil()
```

**example:**

```python
def decorator1(func):
    def wrapper():
        func()
        print("this is from decorator-1")
    return wrapper
def decorator2(func):
    def wrapper():
        func()
        print("this is from decorator-2")
    return wrapper
def decorator3(func):
    def wrapper():
        func()
        print("this is from decorator-3")
    return wrapper
@decorator1
@decorator2
@decorator3
def wrapped():
    print("this is wrapped!")
wrapped()
```

create a decorator to a function called "number()", when the add the  
decorator to the  "number()", number() will calculate the given number  
square, otherwise the given number always print the number() function

**as result:**

**code:**

```python
def square(func):
    def wrapper():
        return func()**2
    return wrapper
@square
def number():
    return int(input("n:"))
print(number())
```

create a 3 decorators for the a function  "get\_salary()" , where get\_salary() will always return "Salary of the employee" as result , when  
given a decorator called "getbonus()", it will give the bonus of the  
salary (Where bonus is 10 % of the salary) and along with salary as result,  
when the we give "gettotaltax()" decorator , it will give the total tax of  
the employee (where tax is 25% of the salary) along with salary as result,  
when we give the "getnetsalary()" decorator, it will give  total net salary  
of the employee with salary,  net salary means after deducting the salary-tax amount

**code:**

```python
def getbonus(func):
    def wrapper():
        salary=func()
        print(f"salary:{salary}")
        print(f"bonus:{salary*0.1}")
        return salary
    return wrapper
def gettotaltax(func):
    def wrapper():
        salary=func()
        print(f"totaltax:{salary*0.25}")
        return salary
    return wrapper
def getnetsalary(func):
    def wrapper():
        salary=func()
        print(f"net:{salary-salary*0.25}")
    return wrapper
@getnetsalary
@gettotaltax
@getbonus
def get_salary():
    return int(input("salary:"))
get_salary()
```

---

## Iterators and Generators

**iterator:**

iterators  are used in  python "to traverse the data of the given iterable" ,  
using this we can able to achieve the  "Memory Efficiency"

iterators are created in python, using a function called "iter()" , any data  
we taken for iterator, the data always need to be "iterable", it means  
the data can be "list , tuple, set, string, range(), dictionary"

syntax:

```python
                iter(iterable_name)
```

from iterator we can  able to traverse the data "using a function called  
next()" , any data we traverse using "next()", then data is never available  
in the iterator  
syntax:

```python
                next(iterable_name)
```

when we are traversing the data from the iterator using "next()" function ,  
if the iterator does not have any data , then the next() function will raise  
an error called  "StopIteration"

**example:**

```python
l1=[1,2,3,4,5,6,7]
#create the iterator for l1
i1=iter(l1)
print(next(i1))#1
print(next(i1))#2
print(next(i1))#3
#convert the iterator into list using list()
print(list(i1))
```

**example:**

```python
l1=[1,2,3,4,5,6,7]
#create the iterator for l1
i1=iter(l1)
print(next(i1))#1
print(next(i1))#2
print(next(i1))#3
#convert the iterator into list using list()
print(list(i1))
print(list(i1))
print(next(i1))
```

**example:**

```python
t1=(10,20,30,40,50,60)
#create the iterator for t1
i1=iter(t1)
print(next(i1))
print(next(i1))
print(next(i1))
print(*i1)
```

**example:**

```python
t1="hello"
#create the iterator for t1
i1=iter(t1)
print(next(i1))
print(next(i1))
print(next(i1))
print(*i1)
```

**example:**

```python
t1={1,2,3,4,5,6,7,8,"hello"}
#create the iterator for t1
i1=iter(t1)
print(next(i1))
print(next(i1))
print(next(i1))
print(*i1)
```

**example:**

```python
t1={1:2,3:4,5:6,7:8,9:10}
#create the iterator for t1
i1=iter(t1)
print(next(i1))
print(next(i1))
print(next(i1))
print(*i1)
```

**example:**

```python
t1={1:2,3:4,5:6,7:8,9:10}
#create the iterator for t1
i1=iter(t1)
print(next(i1))
print(next(i1))
print(next(i1))
print(*i1)
```

when we are working with iterators, the data from the iterators can be  
accessed via " for loop" also  
when we are traversing the data from the iterators using for loop, if the  
data is not present in the iterator, then for loop does not given any error  
like "StopIteration"

**example:**

```python
l1=[1,2,3,4,5,6]
i1=iter(l1)
for i in i1:
    print(i)
```

for i in i1:print(i)

**Working with generators:**

when we want to create the "custom iterators" , in python we will use  
"Generators" , both generators and iterators will behave the same, but  
both are different  
using generator, we can able to create "iterator" for any type of data ,  
here  data can be in the any form, here the generator can be created in

**python, in the following ways:**

1)  generator as a function

when we want to create the  function with at least one "yield" statement ,  
then the function is called as "generator"  
in a function , we can  able to write any number of "yield" statements  
with help of "yield", we can able to "remember the execution state  
of the function" , yield of the function , can make the function  work like  
"pause and play"

syntax:

```python
       def generator_name(arg1, arg2, arg3, arg4,........argn):
                    #write the logic here
                     yield statement1
                     yield statement2
                     yield statement3
                    .
                    .
                    yield statement
```

in python, when we want to create the generator, first we need to call  
the function which is having "yield" statement with some name like a  
value, then we will get "generator" as a result  
with that name we can able to work with generator  
any data from the generator we want to access , we will always traverse  
using following ways:  
1) using next() function  
2) using for loop

when we are accessing the data from the generator using next() function ,  
if there is no data in the generator to read or traverse, then next()  
will raise an exception called "StopIteration"

**example:**

```python
def mygenerator():
    yield 1
    yield 2
    yield 3
    yield 4
    yield 5
#give the name for generator by calling the function
g1=mygenerator()
print(next(g1))
print(next(g1))
print(next(g1))
print(next(g1))
print(next(g1))
```

in python,

we can able to convert the given the iterator into generator using  
"generator as expression"

syntax:

```python
generator_name=(var.name for var.name in iterator_name if cond.)
```

we can able to convert the given generator into iterator using "iter()"  
function

**example:**

```python
def mygenerator():
    yield 1
    yield 2
#accessing the data from the generator using for loop
g1=mygenerator()
#convert the generator into iterator
i1=iter(g1)
#generator as expression
g2=(i for i in i1)
print(*g2)
```

**2)  generator as a expression**

we can able to create the "generator " as same as "list comprehension" ,  
when we want to create the  generator using any iterator or any iterable,  
in python we will use "generator as expression"

---

## Annotations and Doc Strings

annotations are give the information about "what type of data the  function arguments will take from the function calling"  
in order to get the "annotations" of the function, we will use following  
syntax:  
function\_name.\_\_annotations\_\_  
the annotations of the function will stored as a "dictionary"  
if the function does not create with annotations, then the annotation of  
the function is always "Empty" dictionary

when we want to give the annotation of the function , we will use the  
following syntax:

```python
def function_name(arg1:type, arg2:type arg3:type,.........argn:type)->type:
            #write the code here
```

**example:**

```python
 def display():
    pass
print(display.__annotations__)
```

**example:**

```python
def display(a:int,b:int,c:int)->int:
    print(a,b,c)
    print(a+b+c)
print(display.__annotations__)
display(10,20,30)
"""
{'a': <class 'int'>, 'b': <class 'int'>,
 'c': <class 'int'>,
 'return': <class 'int'>}
"""
```

annotations will give the "type hinting" of the arguments of the function  
and return value type of the function

**doc string of the function:**

when we want to give the "Description" of the function what we create ,  
then we will define the "Complete description" of the function using  
"doc string" , this doc string can be retrieved using following syntax:

function\_name.\_\_doc\_\_  
this description we will keep inside the function  using only triple quotes  
(""" """)

**example:**

```python
def display(a,b):
    """
     this function will take two arguments
     , those are a and b, return sum of
     the both a and b
    """
    print(a,b)
    return a+b
print(display.__doc__)
```

when we want to retrieve the meta data of the function, we will use the

**following ways:**

1) \_\_name\_\_  
this will return name of the function  
2)\_\_doc\_\_  
this will return "description of the function , which given as doc string"  
3)\_\_module\_\_  
this will return "the function will belongs to which module"  
4)\_\_code\_\_  
this will return "code of the function"  
5)\_\_annotations\_\_  
this will return "annotations of the function"  
6) \_\_dict\_\_  
using this we can define the user-defined information of the function  
7) \_\_defaults\_\_  
this will return "Default argument values as tuple of the function"

**example:**

```python
def display(a:int,b:int=10)->int:
    """
     this function will take two arguments
     , those are a and b, return sum of
     the both a and b
    """
    print(a,b)
    return a+b
display.__dict__['name']='ram'
display.__dict__['version']="1.0"
print(display.__name__)
print(display.__doc__)
print(display.__module__)
print(display.__code__)
print(display.__annotations__)
print(display.__dict__)
print(display.__defaults__)
```

---

## Packing and Unpacking

"storing the multiple values under the one name is called as packing"

when we pack the "multiple values" under one name, then all values can  
be stored, while packing is "tuple" format

**in python, packing can be done in the following ways:**

1) at variable level  
2) at function level

**example:**

```python
a=1,2,3,4,5,6,7,8,9,10 #packing
print(a)
def display():
    return 1,2,3,4,5,6,7,8,9,10
res=display() #packing
print(res)
```

"retrieving the one or multiple values from the packed object or any iterable in python is called as un-packing"

when we retrieve  only one or mores values from the iterable or packed object, the remaining values will stored under "list" form

we can un-pack the all values from the "packed object" or "any iterable"  
we will use "\*" operator in python

syntax:  
\*iterable\_name or \*packed\_object\_name

**example:**

```python
a=1,2,3,4,5,6,7,8,9,10 #packing
print(a)
print(*a) #un-packing usning "*"
x,y,*z=a
print(x)
print(y)
print(z)
```

**example:**

```python
a=1,2,3,4,5,6,7,8,9,10 #packing
print(a)
print(*a) #un-packing usning "*"
x,*z,y=a
print(x)
print(y)
print(z)
```

**example:**

```python
l1=[10,20,30]
x,y,z=l1
print(x,y,z)
(*x,)=l1
print(x)
x,*y=l1
print(x,y)
*x,y=l1
print(x,y)
```

**example:**

```python
t1=(10,20,30,40,50)
*x,y=t1
print(x,y)
*x,y,z=t1
print(y)
print(z)
print(x)
```

**example:**

```python
t1="hello world"
*x,y=t1
print(x,y)
*x,y,z=t1
print(y)
print(z)
print(x)
```

**example:**

```python
t1={1,2,3,4,5,"hello","hai"}
*x,y=t1
print(x,y)
```

**example:**

```python
t1={1:2,3:4,5:6,7:8,9:10,11:12}
print(t1)
x,*y,z=t1
print(x)
print(y)
print(z)
```

---

## Python Built-in Functions

any function which is given by python, then the function is called as  
"built-in function"

**in python, we will have the following built-in functions:**

1)input()  2) int()  3) float()  4) str()  5)complex()   6) bool()

7) list()  8) tuple()  9) set()  10) dict()   11) hash()  12) bin()  13) oct()

14) hex()  15) max()  16) min()  17) sum()  18) sorted() 19) reversed()

20) len()  21) print()  22) range() 23) dir()  24) vars()  25) all()  26) any()

27) chr()  28) ord()  29) eval() 30) exec()  31) zip()  32) enumerate()

33) super()  34) isinstance()  35) callable() 36)id()  37) map()  38) filter()

39) setattr()  40) getattr()  41) delattr()  42) help()  43) round()

44) abs()  45) divmod()   46) bytes()  47) bytearray()  48) memoryview()

49) type()   50) compile()

**working with bin() function:**

using this function we can able to convert the given number into binary

**example:**

```python
print(bin(120))
print(bin(0o177))
print(bin(0xabc))
```

**working with oct() function:**

using this function we can able to convert the given number into octal

**example:**

```python
print(oct(89))
print(oct(0b10101101))
print(oct(0xbcd))
```

**working with hex() function:**

using this function we can able to convert the given number into hexadecimal number

**example:**

```python
print(hex(162))
print(hex(0b101010))
print(hex(0o175))
```

any binary or octal or hexa-decimal number into "decimal", we will always  
use "int()"

**code:**

```python
print(int(0b101011))
print(int(0o177))
print(int(0xabcd))
```

**working with map() function**

map() function is also called as "higher order function" , any function we  
say "higher-order function", the function will take another function as  
argument

map() function is used in python for "Data transformation of the given  
iterable"

map() function will always takes two arguments, one is function and another  is data , the data always we give only iterable(list, tuple, set, string,range(), dictionary,...........................)

the map() function is always apply the "given function " on the "each element of the given iterable"

the map() is going to "change the any data of the given iterable" ,always  
using "function" which is given as argument to the map() function

the map() function always return the result as "map object", in order to  
see the result again we need to convert into given iterable type

**example:**

```python
print(list(map(lambda x:x*10,[1,2,3,4,5,6])))
print([*map(lambda x:x**2,[1,2,3,4,5,6])])
```

**example:**

```python
rows=int(input("rows:"))
print(*map(lambda x:"* "*x,range(1,rows+1)),sep="\n")
print()
print(*map(lambda x:"* "*x,range(rows,0,-1)),sep="\n")
print()
print(*map(lambda x:" "*(rows-x)+"* "*x,range(1,rows+1)),sep="\n")
print()
print(*map(lambda x:" "*(rows-x)+"* "*x,range(rows,0,-1)),sep="\n")
print()
```

example:  
1  
1 2  
1 2 3  
1 2 3 4  
1 2 3 4 5

**code:**

```python
rows=int(input("rows:"))
for i in [*map(lambda x:range(1,x+1),range(1,rows+1))]:
        print(*i)
print()
for i in [*map(lambda x:range(1,x+1),range(rows,0,-1))]:
        print(*i)
print()
count=1
for i in [*map(lambda x:range(1,x+1),range(1,rows+1))]:
        print(" "*(rows-count),*i)
        count+=1
print()
count=1
for i in [*map(lambda x:range(1,x+1),range(rows,0,-1))]:
        print(" "*(count),*i)
        count+=1
```

**working with filter() function:**

filter() function is also called as "higher order function" , any function we  
say "higher-order function", the function will take another function as  
argument

filter() function is used in python for "Data filtering of the given  
iterable"

filter() function will always takes two arguments, one is function and another  is data , the data always we give only iterable(list, tuple, set, string,range(), dictionary,...........................)

the filter() function is always apply the "given function " on the "each element of the given iterable"

the filter() is not going to "change the any data of the given iterable" ,always going to return the data which are satisfy the given condition in the function ,which is given as argument to the filter()function

the filter()function always return the result as "filter object", in order to  
see the result again we need to convert into given iterable type

**example:**

```python
print(*filter(lambda x:x>5,range(1,10)))
print(*filter(lambda x:x<5,range(1,10)))
print(*filter(lambda x:x>=5,range(1,10)))
print(*filter(lambda x:x%2==0,range(1,10)))
```

write a python program print the string without vowels , print the result  
always as string:  
\=========================================================code:

```python
string=input("string:")#abcde
vowels="aeiouAEIOU"
print(*filter(lambda x: x not in vowels,string),sep="")
```

**write a python program to print the prime numbers in the given range:**

```sql
start=1
end=20
```

2 3 5 7 11 13 17 19

**code:**

```python
print(*filter(lambda x:len([*filter(lambda y:x%y==0,range(1,x+1))])==2, range(start,end)))
```

**example:**

```sql
start=int(input("start:"))
end=int(input("end:"))
```

if start\<0:start=-start  
if end\<0:start=-end  
if start\>end: start,end=end, start

```python
print(*filter(lambda x:len([*filter(lambda y:x%y==0,
                                    range(1,x+1))])==2,
              range(start,end)))
```

**round():**

using this function we can able to round the number

**example:**

```python
print(round(1.23456,2))#1.23
print(round(1.23456,3))#1.235
print(round(1.234567,4))#1.2346
print(round(1.234567,0))#1.0
```

**all():**

using this function we can check the all values of the given iterable are  
True or not  
for this function we will give the "Data" always as "iterable" format  
this function always return result as "Boolean"(True or False)

**example:**

```python
print(all([1,2,3,4,5,6,7,8]))
print(all([1,2,3,4,5,6,7,8,0]))
print(all([]))
```

**any():**

using this function we can check the at least one value of the given iterable are True or not  
for this function we will give the "Data" always as "iterable" format  
this function always return result as "Boolean"(True or False)

**example:**

```python
print(any([1,2,3,4,5,6,7,8]))
print(any([1,2,3,4,5,6,7,8,0]))
print(any([]))
```

**eval()**

when we want to execute the any "expression as a string", where the expression  never contain "=" operator

**example:**

```python
a=10
b=20
print(eval("10*20//3"))
print(eval("a+b"))
print(eval("a*b+b*a"))
print(eval("a*b*b*a"))
```

**exec()**

this function is used to execute any code "Which is given in  the form of  
string"  
when we give any code using assignment operator, exec() function will  
execute

**example:**

```python
exec("a=10")
exec("b=20")
exec("print(a+b)")
exec("print(a)")
exec("print(b)")
print(a,b)
```

**example:**

```python
exec("a=10")
exec("b=20")
exec("a=a+b")
exec("print(a)")
exec("print(a*b)")
```

**zip():**

zip() function is used "Zip the given itreables into tuples"  
zip() function always zip the given iterables into tuple based on the  
position  wise  
zip() function always make the tuple based on the given number of iterables, so here the tuple will have how many elements means it always  
depends on "number of iterables" we are given to zip()

the maximum numbers of tuples given by zip() function always depends on "the minimum number of elements of the given iteable"

zip() function always return result as "zip()" object

**example:**

```python
l1=[1,2,3,4]
l2=[10,20,30,40]
print(list(zip(l1,l2)))
l1=[1,2]
l2=[10,20,30,40]
print(list(zip(l1,l2)))
l1=[]
l2=[10,20,30,40]
print(list(zip(l1,l2)))
l1="hello"
l2="hai"
print(list(zip(l1,l2)))
```

**example:**

```python
l1=[1,2,3,4,5]
l2=[10,20,30,40,50]
res=zip(l1,l2)
for i in res:
    print(i)
print(list(res))
```

**example:**

```python
l1=[1,2,3,4,5]
l2=[10,20,30,40,50]
res=zip(l1,l2)
print(next(res))
print(next(res))
print(next(res))
print(*res)
```

**enumerate()**

enumerate() function is used "enumerate the given itreables into tuples"  
where the "tuple  will contain both index and value"  
enumerate() function always return result as "enumerate" object  
this function will apply the "custom index" also, to give the custom index,  
we will use a argument called "start" , by default this function always give  
"0" as starting index

**example:**

```python
l1=[1,2,3,4,5]
print([*enumerate(l1)])
l1=(10,20,30,40,50)
print([*enumerate(l1)])
l1="hello world"
print([*enumerate(l1,start=10)])
l1={1,2,3,4,5}
print([*enumerate(l1)])
```

**abs() function:**

this function will return "absolute value of the given number", it means  
it always return "positive number" as result

**divmod():**

this function will return always "given two numbers" ", quotient and remainder

**example:**

```python
print(abs(-10))
print(abs(-1.234))
print(divmod(10,20))
print(divmod(20,10))
print(divmod(10.0,3))
print(divmod(10,20.0))
```

**hash():**

hashing means "convert the data into another type with some representation"  
for hashing in python, we will use a function called "hash()" function  
using this function we can able to convert the given data into number  
this function always give the same hash value for given same data  
this function always give the different hash value for given different data

this will convert the given data  mostly  number, string, tuple, range()  
into number  
it can not convert the "set, dictionary , list" into hash code using  hashing  
due to those are mutable

**example:**

```python
a=10
b=20
c=30
a="hello"
b="hello"
print(hash(a))
print(hash(b))
print(hash(a))
print(hash(b))
x=1.234
print(hash(x))
print(hash(-1.567))
a1=-1000
print(hash(a1))
print(hash(-1000))
```

**example:**

```python
a=-1.234
print(hash(a))
a=4.567
print(hash(a))
a="Hello"
print(hash(a))
a=(1,2,3,4,5)
print(hash(a))
a1=range(1,10)
print(hash(a1))
a=257
print(hash(a))
b=257
print(hash(b))
print(id(a))
print(id(b))
print(id(a)==id(b))
```

**isinstance():**

using this function  we can check given object is given class type or not  
this function always return result as "Boolean"

**example:**

```python
print(isinstance(10,int))
print(isinstance(10,float))
print(isinstance(1.23,int))
print(isinstance("hello",float))
print(isinstance([1,2,3,4,5],list))
print(isinstance((10,20,30),tuple))
print(isinstance({1,2,3,4},set))
print(isinstance({1:3},set))
print(isinstance({1:2},dict))
print(isinstance(10+3j,complex))
print(isinstance([1,23,4,5],range))
```

**callable():**

when we want to check given name is function name or not, in python we  
will use this function  
this function will always return "Boolean value" as result

**example:**

```python
a=10
b=20
res=lambda:print("this is lambda function")
def display():
    print("This is display function")
print(callable(display))
print(callable(a))
print(callable(b))
print(callable(res))
```

**example:**

```python
a=int("10")
print(a)
a=int("+12")
print(a)
a=int("-12")
print(a)
a=int("1_2_3")
print(a)
a=int("1_1")
print(a)
a=int("1_2")
print(a)
```

**example:**

```python
a=float("1.23")
print(a)
a=float(".23")
print(a)
a=float("1.")
print(a)
a=float("+1.23")
print(a)
a=float("-1.23")
print(a)
a=float("1.2_3")
print(a)
a=int("16",10)#001010011
print(a)
```

---

## Scope

Scope refers  "where we can able to access the data"  or  "Accessibility of  
the data in the program"

**in general, we will have two types of scope:**

1) Local Scope  
any data we define inside the function , then the data will have "local"  
scope  
when we have "local scope data", then the data can accessed and can be  
changed only with in the function

2) Global Scope  
any data we define outside the function , then the data will have "global"  
scope  
when we have "global scope data", then the data can be accessed anywhere in the program, but can be changed we define

**example:**

```python
x=10 #global data
y=20 #global data
def display():
    a,b=1,2 #local data
    print(a)
    print(b)
    a+=100
    b+=100
    print(a,b)
    print(x,y)
display()
```

**in python we will have the following scopes, those are :**

1) local Scope  
this scope refers the data which is defined in function  
2) enclosed Scope  
this scope refers the data which is defined in  outer function  
3) global Scope  
this scope refers the data which is defined outside the function  or  data  
which is not define in the function  
4) built-in Scope  
this scope refers "python built-in names"

different scopes of data,  will define with same name, but change in scope,  
in order to access the data which is defined in the ,multiple scopes with  
same name, python will uses "LEGB" rule, where LEGB is for "Scope  
Resolution Order"

L==\>Local   (Rank-1)  
E===\> Enclosed (Rank-2 ,check it's outer funcitons)  
G===\> Global (Rank-3)  
B===\> Built-in (Rank-4)

**example:**

```python
x=10#global data
def display():
    x,y=11,12  #local data
    print(x,y) #11 12
print(x)#10
display()
#LOE:1,5,6,2,3,4
```

**example:**

```python
x=10
def display():
    x=111 #local data of display
    def display2():
        x=11 #local data of display2
        def display3():
            y=200 #local data of display3
            print(x,y)#11 200
        display3()
        print(x)#11
    display2()
    print(x)#111
display()
#LOE: 1,13,2,3,11,4,5,9,6,7,8,10,12
```

**example:**

```python
x=10
def display():
    x,y=1,2
    print(x,y) #1 2
    def display2():
        a,b=100,200
        def display3():
            a1,b1=11,12
            print(a,b,a1,b1,x,y)#100 200 11 12 1 2
        display3()
    display2()
    print(x,y)#1 2
print(x)#10
display()
#LOE:1,13,14,2,3,4,11,5,6,10,7,8,9,12
```

when we want to change the global data, in general, we can able to change  
where define the global data  
when we want to change the global data inside the function , we will use  
a keyword called  "global"

syntax:

```python
                       global var_name1, var_name2,...........var_namen
```

when we are using global keyword to change the global data inside the  
function , python will consider any name which is defined in the function  
as follows :  
1) if name already present, then it take the value what originally name contains  
2) if name is not present, then it take the name as global directly , we need  
to define  value the after declaration with global, while using global  
keyword we can not assign any name to the variable

**example:**

```python
x=10
def display():
    global x
    x+=10 #20
    print(x) #20
print(x)#10
display()
print(x)#20
```

**example:**

```python
 x=10
def display():
    global x
    x+=10 #20
    print(x) #20
print(x)#10
display()
print(x)#20
```

**example:**

```python
x=10
def display():
    global x,y
    x+=10 #20
    y=200
    print(x) #20
print(x)#10
display()
print(x)#20
y+=300
print(y) #500
```

**example:**

```python
x=10
def display():
    global x,y
    x+=10 #20
    y=200
    print(x) #20
print(x)#10
display()
print(x)#20
y+=300
print(y) #500
```

**example:**

```python
a,b=10,20
x,y=11,12
def display():
    x,y=1,2 #local data
    def display2():
        global x,y #global data
        x+=100
        y+=200
    print(a+x,a+y)#11 12
    display2()
    print(x,y)#1 2
display()
print(x,y)#111 212
print(a,b)#10 20
#LOE:1,10,2,3,8,9,4,5,6,7,11,12
```

**example:**

```python
a,b=10,20
def display():
    global a,b
    a+=10 #a=20
    b+=20  #b=40
    def display2():
        global x,y
        x=1  #x=1
        y=2 # y=2
        def display3():
            x,y=10,20  #local data
            print(a+x,a+y) #30 40
        display3()
    display2()
display()
#LOE:1,15,2,3,4,5,14,6,7,8,9,13,10,11,12
```

**example:**

```python
a,b=10,20
def display():
    global a,b  #a=210, b=420
    if a>=b:
        a+=100
        b+=200
    else:
        a+=100 #a=310
        b+=200# b=620
        display()
    def display2():
       global a,b
       a+=100
       b+=200
    display2()
display()
print(a,b)
```

**example:**

```python
a,b=10,20
def display():
    global a,b  #a=450, b=740
    def display2():
        global a,b
        a+=30
        b+=40
        if a<=200:
           display2()
        else:
            a+=100
            b+=200
    display2()
    if a<=400:
        display()
display()
print(a,b)#450 740
```

**example:**

```python
a=1
def display():
    global a
    a=100
    x,y=10,20 #local data
    def display2():
        global b
        nonlocal x,y #x=10, y=20
        b=200
        b*=(a+b) #b=6000
        x+=300 #310
        y+=400 #420
        print(a,b,x,y)#100 60000 310 420
    display2()
display()
```

when we want to change the any enclosed scope data  or when want  
to change the any outer function data inside the it's inner function or  
in inner function , when we want to change the any one of the it's outer  
function , then in python we will a keyword called  " nonlocal"

when we define the any names with "nonlocal", those names must present  
any one of the it's outer function, otherwise we will get an error

the way we use global , in the same way we will use "nonlocal" in python

global is used to change the any global data or to create the any global  
data inside the function  
nonlocal is used to change the only enclosed scope data in Python

**example:**

```python
a=1
def display():
    a=10
    def display2():
        nonlocal a #a=10
        a+=100  #a=110
        def display3():
            nonlocal a #a=110
            a+=200  #a=310
            def display4():
                nonlocal a #a=310
                a+=400  #a=710
            display4()
            print(a)#710
        display3()
        print(a)#710
    display2()
    print(a)#710
display()
```

**example:**

```python
a,b=10,20
x,y=100,200
def display():
    global x,y
    a,b=100,200 #local data
    def display2():
        global x,y #x=200, y=400
        nonlocal a,b #a=600 b=80000
        x+=100
        y+=200
        a,b=x+y,x*y
    display2()
    print(x,y)#200 400
    print(a,b)#600 80000
display()
print(x,y)#200 400
```

**example:**

```python
a,b=10,20
x,y=1,2
def display():
    global x,y
    a,b=10,20 #local
    x+=a  #11
    y+=b  #22
    a,b=a*b,a+b # 200 30
    def display2():
        global x,y #x=11 y=22
        nonlocal a,b #a=200 b=30
        x,y,a,b=a*x,b*y,x*y,x+y # x=2200, y=660 ,a=242,b=33
    display2()
    print(a,b,x,y)#
display()
```

when we are working with  "Scope" ,  we need to understand how python  
will maintain data based on the "Scope" internally means  as a "Name Space"

this name space will be maintained in the form of the "dictionary"

**in Python, based on Scope, the name spaces will divided into 4 types:**

1) Local Name Space  
in Python, all local scope data will be stored in the  "local name space"

2) Enclosed Name Space  
in Python, all enclosed scope data will be stored in the  "enclosed name  
space"

3) Global Name Space  
in Python, all global scope data will be stored in the  "global name space"

4) Built-in Name Space  
in Python, all Built-in scope data will be stored in the  "built-in name space"

in Python,

when we want to access the name space, we will use the following functions:

1) globals()

this will complete the "all names which are used by program , which  
include global, built-in scope data as Name Space"

2) locals()  
this include a same function  data or if the function having any inner  
function and same function data , will given as result in the form of Name  
space"

**example:**

```python
def display():
    a=10
    b=20
    c=30
    def display2():
        x,y,z=10,20,30
        print(locals())
    display2()
    print(locals())
display()
print(globals())
```

---

## Modules and Packages

**Module:**

Module means "python file"  
in Python, when we create a file with data and functions, can be re-used  
in another python file  with help of module  
Modules will allow the "re-useability of the code of one file in another file"  
when we want to create the module in python we will use the following

**steps:**

step-1:  
create a python file with data and functions  
save the file with some\_name.py  
run the python file  
here the name of the file is "module name"  
step-2:  
create the  another python file with some name.py , here we can able  
to access the all module data and methods using a keyword called "import"  
when we want to use any module in python, we need to import the module  
using  a keyword called "import"

syntax:

```python
                              import module_name
```

when we want to access the any module data or functions after importing  
we will use following syntax:

module\_name.data\_name  
or  
module\_name.function \_name(val,val2,val3,.....valn)

when we create the module, inside the module what data or functions we  
have can be known using " a function called dir()"

syntax:

```python
                       dir(module_name)
```

here module name means "file name"

when we access the module using "import" keyword , then we will able to  
get the all module data and functions we can able to access using  module  
name before name of the data or function

when we want to access the "only particular data or functions" only from  
the module , we will use "from" keyword

syntax:

```python
from module_name  import data1, data2,...datan, function1,..........function
```

when we access the module data or functions  using "from" keyword, then  
we can able to access the data  or functions directly using name of the  
data or function

when we are importing the module using "import" keyword, we can able  
to give the alias name using a keyword called "as"

syntax:

import module\_name as alias\_name, module\_name2 as alias\_name,......

**example:**

```python
from mymodule import a,b,c,add,mul,div
print(a)
print(b)
print(c)
add(10,20)
mul(10,20)
div(20,10)
```

**example:**

```python
from mymodule import *
print(a)
print(b)
print(c)
add(10,20)
mul(10,20)
div(20,10)
```

**example:**

**mymodule.py:**

```python
"""data"""
a=10
b=20
c=30
"""methods"""
def add(a,b):
    print(a+b)
def sub(a,b):
    print(a-b)
def mul(a,b):
    print(a*b)
def div(a,b):
    print(a/b)
```

**mymodule2.py:**

```python
def square(x):
    return x**2
def cube(x):
    return x**3
def sqrt(x):
    return x**(1/2)
def cbrt(x):
    return x**(1/3)
```

**test.py:**

```python
import mymodule
mymodule.div(10,20)
mymodule.add(10,20)
mymodule.sub(100,20)
mymodule.mul(10,20)
print(mymodule.a)
print(mymodule.b)
print(mymodule.c)
```

**example:**

```python
import mymodule as m1,mymodule2 as m2
print(m1.a)
print(m1.b)
print(m1.c)
m1.add(10,20)
m1.sub(20,10)
m1.div(10,20)
print(m2.sqrt(4))
print(m2.cbrt(27))
```

**working with packages:**

package means "a folder of python files or modules"

when we want to create the python package, we will use the following

**steps:**

**step-1:**

create a folder with some name  
here the name of the folder is act as "package name"

**step-2:**

after creating the folder with some name, then inside the folder  
we need to create the a file with name "\_\_init\_\_.py" , this file must be  
empty file , after creating it , run the file

**step-3:**

after creating the  "\_\_init\_\_.py", we need to create the all modules inside  
the python package

**step-4:**

once we create the modules inside the python package, we can able to  
access the all package modules using some another python file , where this always outside the folder

when we want to access the any python package module data or functions,  
we will always used following ways:

**using  "import" keyword:**

```python
import package_name.module_name as aliasname,......................
```

when we import any python package module like above, we can able to  
access the all package module data and functions

**example:**

```python
import mypackage.mymodule as mm,mypackage.mymodule2 as mm2
print(mm.a)
print(mm.b)
print(mm2.sqrt(16))
```

**using from  keyword:**

when we want to only specific data or functions from the python package  
module, we will use this keyword  
syntax:

```python
from package_name.module_name  import data1,...datan,fun1,....funn
```

**example:**

```python
from mypackage.mymodule import a,b
print(a)
print(b)
from mypackage.mymodule2 import sqrt,cbrt
print(sqrt(16))
print(cbrt(27))
```

**working with sub-packages:**

in package , we can able to create the another sub-package or package,  
in python, when we want to create the any sub-package, we will use the  
same steps what we use package

**example:**

```python
import mypackage2.mysubpackage.mysubpackagemodule as mmm
print(mmm.a1)
print(mmm.b1)
print(mmm.c1)
```

when we are working with modules and packages , we will may get an  
issue called "circular imports"

circular import , if module1 will mort module2, module2 will import  
module1, then both modules still importing, due to this the modules  
not completely imported, due to this we will this issue

**mymodule::**

```python
from mymodule2 import display2
def display1():
    print("this is from module-1")
```

**mymodule2:**

```python
from mymodule import display1
def display2():
    print("this is display2!")
```

when we run above any one of the modules we will get the following error:

error:

mportError: cannot import name 'display1' from partially initialized module 'mymodule' (most likely due to a circular import) (D:\\training\\360digrii\\2026\\Python Fp-7\\Python\\mymodule.py)

to avoid this , we will use the following solution

**mymodule.py:**

```python
def display1():
    from mymodule2 import display2
    print("this is from module-1")
```

**mymodule-2:**

```python
def display2():
    from mymodule import display1
    print("this is display2!")
```

---

## OOPS: Classes and Objects

**classes and objects:**

**class:**

class is "class is a representation of object"

class can contain "attributes and behaviour of the object"

attributes / properties means "data of the object"

behaviour / actions means "methods of the object"

**what is data  of the class:**

data of the class means :

variable , list, tuple, set, string, dictionary,...........................

**what is method of the class:**

method refers "function"  
when we define the function inside the "class", then function is called as  
"method"

when we want to create the class inside the program, we will use a keyword called "class"

syntax:

```python
class class_name:

         #data
         #methods
```

**generally, inside the python class, we will have the following members:**

1) data  
2) method  
3) constructor  
4) inner classes

the above all are called as "Members of the class"

**types of data in python class:**

**python class can have two types of data:**

1) class data or class variable or class-bound data  
2) instance data or instance variable or instance/object-bound data

**class data:**

when we define the data directly inside the class and we create the data  
directly without using any "Constructor" , then the data is called as "class  
data or class variables"

when we define the "class data" inside the class, when we want to access the class data, we can not access the class data directly outside the class

**when we wany to access any class data outside the class, we will use following ways in Python:**

1) using class name  
2) using object of the class

**when we want to change the class data outside the class, we can change using following ways:**

1) using class name  
2) using object of the class

when we want to access the any  "class data", outside the class, we can  
able to access the class data using following syntax:

class\_name.class\_data\_name

or

object\_name.class\_data\_name

when we want to change the any  "class data", outside the class, we can  
able to change the class data using following syntax:

```python
                             class_name.class_data_name=value

                                          or

                             object_name.class_data_name=value
```

**instance data:**

when we define the "data inside the class only using constructor", then the  
data is called as "instance data or instance method"

**when we want to access the instance data of the class outside the class, we will use the following ways:**

1) using object of the class only

to access the  instance data using object , we will use the following syntax:

object\_name.instance\_data\_name

**when we want to change the instance data of the class outside the class, we will use the following ways:**

1) using object of the class only

**to change the instance data of the class we will use following syntax:**

```python
                            object_name.instance_data_name=value
```

**2.methods of the class:**

**in python class, we will have the following type of methods:**

1)  class method  
2)  static method  
3)  instance method

**class method:**

class method is a method and which is created inside the class using "@classmethod" decorator

class method will contain "default one argument called cls"

the name of "cls", can be  "programmer choice"

in Python, we can able to define the any number of class methods using  
"@classmethod" decorator inside the class

when we want to access the class method outside the class , in python

**we will use the following ways:**

1) using class name  
2) using object of the class

when we are defining the class method inside the class , then the class  
method will have  an argument called "cls", using this name, we can able

**do the following in python:**

1) using cls, we can able to access the "Class data" inside the same class  
"class method"  
2) using cls, we can able to access the "Class method" inside the same  
class    "class method and static method"

**static method:**

static method is a method and which is created inside the class using "@staticmethod" decorator

static method will  not contain "default argument called cls or self"

when we want to access the static method outside the class , in python

**we will use the following ways:**

1) using class name  
2) using object of the class

static method can able access the same class,  "class data inside the static  
method using class name"

static method can able to access the same class,  "class method or static method  inside the static method using class name"

**instance method:**

instance method is a method and which is created inside the class directly

instance method will contain "default one argument called self"

the name of "self", can be  "programmer choice"

when we want to access the instance method outside the class , in python

**we will use the following ways:**

1) using object of the class

when we are defining the instance method inside the class , then the class  
method will have  an argument called "self", using this name, we can able

**do the following in python:**

1) using self, we can able to access the "Class data and instance data" inside the same class   "instance method"  
2) using self, we can able to access the "Class method or static method or instance method" inside the same  class    "instance method"

type                  class method            static method            instance method  
class data             yes                                   yes                               yes  
( using cls)                     (using class name)       (using self)

class method       yes                                   yes                            yes

( using cls)                     (using class name)       (using self)

static method      yes                                 yes                           yes

( using cls)                     (using class name)       (using self)

instance method   no                               no                             yes

( using cls)                     (using class name)       (using self)

in python class, we can define the following

data

**class data**

class data  (the data what we create inside the class is called as class  
data and which is created not created using constructor, this can  be  
accessed outside the class using "class name" and using  "object  
name"

**instance data**

instance data is created inside the class using "constructor" and this  
data can be accessed outside the class using "object" of the class

**methods**

class method  
static method  
instance method

---

## Constructors

constructor is a method  
constructor is a "instance method"  
in python, we will use constructor to initialize the "data of object of the class"  or "create the instance data of the object"

when we create the constructor inside the class, then the constructor is  
called  automatically, when we create the object to the class

in Python, when we want to create the constructor, we will use a name  
called "\_\_init\_\_()"

**in Python, we can able to create the two types of constructors:**

**1) Default constructor :**

when we create the constructor with "no arguments" , then the constructor is called as "default constructor"

**2) Parameterized constructor**

when we create the constructor with "arguments" , then the constructor is called as "parameterized constructor"

**syntax of the constructor in the class:**

```python
def __init__(self,arg1,arg2,arg3,.......argn):
         #write the logic here
```

constructor is automatically called by object, when we create the object  
to the class  
constructor can be called  by object , this is not recommended in python  
constructor will never return any result  
in a class , we can able to create  only one "either Default or parameterized" constructor

```python
class(Data(class, instance)+ methods (class, static, instance)+ constructor( default or parameterized))
```

**working with inner classes or nested classes:**

**object:**

object is a "class type variable"  
when we create the  "any name using class", then the name can hold object  of the  class

for a class, we can able to create any number of  objects

**to create the object, we will use the following syntax:**

```python
                       object_name=class_name()
```

**with help of object, we can able to do the following:**

1) we can able access the "Class data"  
2) we can able to access the "Instance data"  
3) we can able to access the "Class method"  
4) we can able to access the "Static method"  
5) we can able to access the "Instance method"  
6) we can able to access the "inner class"

when we want to access the any member of the class, we will use the following syntax:

object\_name.data\_member\_name \<=== data  
or

```python
                  object_name.method_name(val1,val2,........valn)
```

**example:**

```python
class Sample: #class name
    #class data (this is created without constructor , inside the class directly)
    a,b,c=10,20,30
```

"""Access the class data using class name"""

```python
print(Sample.a,Sample.b,Sample.c)
```

"""Acess the class data using object of the class"""

```python
s1=Sample() #here s1 is object of the class
print(s1.a,s1.b,s1.c)
```

when we want to change the any class data outside the class, then we will

**use the following ways:**

1) using class name  
syntax:

```python
                              class_name.data_name=value
```

2) using object  
syntax:

```python
                              object_name.data_name=value
```

**example:**

```python
class Sample: #class name
    #class data (this is created without constructor , inside the class directly)
    a,b,c=10,20,30
print(Sample.a,Sample.b,Sample.c)
```

"""change the class data using class name"""

```python
Sample.a=1
Sample.b=2
Sample.c=3
print(Sample.a,Sample.b,Sample.c)
"""create the object to the class"""
s1=Sample()
"""change the class data using object"""
s1.a,s1.b,s1.c=111,222,333
print(s1.a,s1.b,s1.c)
```

**example:**

```python
class Sample: #class name
    #class data (this is created without constructor , inside the class directly)
    a,b,c=10,20,30
print(Sample.a,Sample.b,Sample.c)
```

"""change the class data using class name"""

```python
Sample.a=1
Sample.b=2
Sample.c=3
print(Sample.a,Sample.b,Sample.c)
"""create the object to the class"""
s1=Sample()
"""change the class data using object"""
s1.a,s1.b,s1.c=111,222,333
print(s1.a,s1.b,s1.c)
```

when we want to create the instance data, to create instance data, we will use "constructor"

**example:**

```python
class Sample: #class name:Sample
   def __init__(self):
       print("This is default constrcutor from Sample!")
class Sample2: #class name:Sample2
    def __init__(self):
        print("This is defautl constrcutor from Sample2!")
s1=Sample()
s2=Sample2()
```

**example:**

```python
class Sample: #class name:Sample
   #default constructor
   def __init__(self):
         self.a=100
         self.b=200
         self.c=300
s1=Sample()
"""access the instance data"""
print(s1.a,s1.b,s1.c)
"""to change the instance data"""
s1.a,s1.b,s1.c=11,12,13
print(s1.a,s1.b,s1.c)
```

**example:**

```python
"""access the instance data"""
print(s1.a,s1.b,s1.c)
"""to change the instance data"""
s1.a,s1.b,s1.c=11,12,13
print(s1.a,s1.b,s1.c)
```

when we want to access the "class data and instance data" ,when we  
want to change the "class data and instance data", when we want to remove the "class data and instance data", we will following built-in

**functions:**

1) getattr() (to read the data of the class)  
using this function , we can able to access the data of the class, the data  
can be class data or instance data

**example:**

```python
class Sample:
    """class data"""
    a=10
    b=20
    c=30
#access the class data using class name
print(Sample.a,Sample.b,Sample.c)
s1=Sample()
#access the class data using object
print(s1.a,s1.b,s1.c)
#access the class data using class name with getattr()
print(getattr(Sample,"a"))
print(getattr(Sample,"b"))
print(getattr(Sample,"c"))
#access the class data using object name with getattr()
print(getattr(s1,"a"))
print(getattr(s1,"b"))
print(getattr(s1,"c"))
```

**example:**

```python
class Sample:
   #constrcutor
   def __init__(self):
       """instance data"""
       self.a=10
       self.b=20
       self.c=30
s1=Sample()
#access the class data using object
print(s1.a,s1.b,s1.c)
#access the class data using object name with getattr()
print(getattr(s1,"a"))
print(getattr(s1,"b"))
print(getattr(s1,"c"))
```

2) setattr() (to write the data of the class)  
using this function , we can able to change the data of the class, the data  
can be class data or instance data

**example:**

```python
class Sample:
    """class data"""
    a=10
    b=20
    c=30
#change the class data using class name
Sample.a,Sample.b,Sample.c=11,12,13
#access the class data using class name
print(Sample.a,Sample.b,Sample.c)
s1=Sample()
#change the class data using object
s1.a,s1.b,s1.c=100,200,300
#access the class data using object
print(s1.a,s1.b,s1.c)
#change the class data using setattr() using class name
setattr(Sample,"a",1)
setattr(Sample,"b",11)
setattr(Sample,"c",111)
#access the class data using object
print(Sample.a,Sample.b,Sample.c)
#change the class data using setattr() using object name
setattr(s1,"a",1000)
setattr(s1,"b",2000)
setattr(s1,"c",3000)
#access the class data using object
print(s1.a,s1.b,s1.c)
```

**note:**

when we try to change the class data using "setattr()" , using class name,  
the changes can be seen when we access the class data using class name ,  
otherwise we can not  see any changes, when the already the data which available in the class as instance data, can be seen only using object of  
the class

in python,

**we can able to create the class data in ways:**

1) we can create the class data directly  inside the class  
2) we can create the class data using "setattr()" outside the class  
with help of class name  
3) using class name we can able create , outside the class

**example:**

```python
class Sample:
    #create inside the class
    x,y=100,200
print(dir(Sample))
#create using setattr()
setattr(Sample,"a",100)
setattr(Sample,"b",200)
print(dir(Sample))
#create using class name
Sample.a1=11
Sample.b1=22
print(dir(Sample))
#access using class data using class name
print(Sample.a,Sample.b,Sample.x,Sample.y)
print(Sample.a1,Sample.b1)
s1=Sample()
#access the class data using object
print(s1.a1,s1.b1,s1.a,s1.b,s1.x,s1.y)
```

in python,

**we can able to create the instance data in ways:**

1) we can create the instance data using constrcutor  inside the class  
2) we can create the instance data using "setattr()" outside the class,  
wit help of "object name"  
3)we can create the instance data outside the class using object name  
directly

**example:**

```python
class Sample:
    #create the instance data using constrcutor
    def __init__(self):
        self.x,self.y=1,2
s1=Sample()
#create the new instance data using object outisde the class
s1.a=100
s1.b=200
s1.c=300
#create the instance data using setattr
setattr(s1,"a1",100)
print(dir(s1))
print(s1.a,s1.b,s1.c,s1.x,s1.y,s1.a1)
```

in Python, we can able to create the class data and instance data with  
same names , when we give the same names to class data and instance  
data, then both can be accessed using "class data" with "class name" and "instance data" using object name

**example:**

```python
class Sample:
    pass
Sample.a=100
Sample.b=200
Sample.c=300
s1=Sample()
print(dir(Sample))
print(Sample.a,Sample.b,Sample.c)
print(s1.a,s1.b,s1.c)
```

when we want to see the all class data of the class, we will use a function  
called "dir()"  
syntax:

```python
dir(class_name)
```

when we want to see the all instance data of the class, we will use a function called "dir()"  
syntax:

```python
dir(object_name)
```

**example:**

```python
class Sample:
    pass
setattr(Sample,"a",10)
setattr(Sample,"b",20)
setattr(Sample,"c",30)
print(dir(Sample))
print(Sample.a,Sample.b)
print(Sample.c)
```

**example:**

```python
class Sample:
    pass
s1=Sample()
setattr(s1,"a",10)
setattr(s1,"b",20)
setattr(s1,"c",30)
print(dir(s1))
```

**example:**

```python
class Sample:
    pass
s1=Sample()
#class data
setattr(Sample,"a",100)
#instance data
setattr(s1,"a",10)
print(s1.a)
s1.a=1000
print(s1.a)
Sample.a=10000
print(Sample.a)
```

3) delattr()  (to delete the data of the class)  
using this function , we can able to delete the data of the class, the data  
can be class data or instance data

**in a class, we create the following methods:**

1) class method  (need to create always with @classmethod decorator and  
an argument called 'cls')  
this can be accessed using "class name or object of the class outside the  
class "  
2) static method (need to create always with @staticmethod decorator  
and this method will not take any argument like class  
method)  
this can be accessed using "class name or object of the class outside the  
class "  
3)instance method(this method will be created directly inside the class and this method will have an argument "self")  
this method can be accessed only using "object of the class"

in python, when we want to access the class method of a same class  inside the another class method in same class , we can use "cls"  
in Python, when we want to access the class data of the class inside the  
same class  "class method" , we can use  "cls"  
in Python, when we want to change the class data of the class inside the  
same class  "class method", we can use "cls"

**example:**

```python
class Sample:
    x,y=100, 200 #class data
    """class method"""
    @classmethod
    def display1(cls):
        print(cls.x,cls.y)
    @classmethod
    def display2(cls):
        cls.display1()

s1=Sample()
Sample.display2()
s1.display2()
```

**example:**

```python
class Sample:
    x,y=100, 200 #class data
    """class method"""
    @classmethod
    def display1(cls):
        print(cls.x,cls.y)
    @classmethod
    def display2(cls):
        cls.display1()
        cls.x,cls.y=111,222

print(Sample.x,Sample.y)
s1=Sample()
Sample.display2()
s1.display2()
print(Sample.x,Sample.y)
```

**example:**

```python
class Sample:
    """class method"""
    @classmethod
    def display1(cls):
        print("this is from the class method!")
    """static method"""
    @staticmethod
    def display2():
        print("this is from the static method!")
    """instance method"""
    def display3(self):
        print("this is from the instance method!")
Sample.display1()
Sample.display2()
s1=Sample()
s1.display1()
s1.display2()
s1.display3()
```

in Python, when we want to access the "class data" inside the same class  
"static method" , we can use "class name"

in Python, when we want to access the "class method or static method"  
inside the same class "static method", we can use "class name"

in Python, when we want to change the any class data inside the same class static method, we will use "Class name"

**example:**

```python
class Sample:
    x,y=100, 200 #class data
    """class method"""
    @staticmethod
    def display1():
        print(Sample.x,Sample.y)
        Sample.display2()
        Sample.display3()
    @classmethod
    def display2(cls):
        print("this is class method!")
    @staticmethod
    def display3():
        print("This is static method!")
print(Sample.x,Sample.y)
s1=Sample()
Sample.display1()
```

**example:**

```python
class Sample:
    x,y=100, 200 #class data
    """class method"""
    @staticmethod
    def display1():
        print(Sample.x,Sample.y)
        Sample.display2()
        Sample.display3()
    @classmethod
    def display2(cls):
        cls.x,cls.y=11,12
        print("this is class method!")
    @staticmethod
    def display3():
        print("This is static method!")
        Sample.x,Sample.y=111,222
print(Sample.x,Sample.y)
s1=Sample()
Sample.display1()
Sample.display2()
print(Sample.x,Sample.y)
Sample.display3()
print(Sample.x,Sample.y)
```

In python,  
when we want to access or change the same class data inside the same  
class "instance method", then we will use "self"

when we want access the "Class method or static method or instance  method" inside the same class , then in python we will use "self" , self  
keyword can able to access the class data, instance data, class method,  
instance method, static method" only with in the class, due to this  
"self" is called as "current class object"

**example:**

```python
class Sample:
    a,b=10,20  #class data
    def __init__(self): #default constructor
      self.x,self.y,self.z=1,2,3 #instance data
    def display(self):#instance method
        print(self.a)
        print(self.b)
        print(self.x,self.y,self.z)
s1=Sample()
s1.display()
```

**class data**

inside the same class, we can able to access class data in the following methods:  
1) class method  
access using "cls"  
2) static method  
access using "class name"  
3) instance method  
access using "self"  
outside the class, we can able to access the class data using following  
ways :  
1) class name  
2) class name using getattr()  
3)object name

**instance data:**

inside the same class, we can able to access instance data in the following methods:  
1) instance method  
access using "self"  
outside the class, we can able to access the instance data using following  
ways :  
1) object name  
2) object name using getattr()

in python ,

class method  can access inside the same class, in the following methods :  
1) class method (access using 'cls')  
2) static method (access using class name)  
3) instance method (access using self)

class method  can access outside , in the following ways :  
1) class name  
2) using object

in Python,  
static method  can access inside the same class, in the following methods :  
1) class method (access using 'cls')  
2) static method (access using class name)  
3) instance method (access using self)

static method  can access outside , in the following ways :  
1) class name  
2) using object

in python,  
instance method  can access inside the same class, in the following methods :  
1) instance method (access using self)

instance method  can access outside , in the following ways :  
2) using object

in a class , we can able to create the another class , the class what we create inside the another class is called as "inner class or nested class"

**nested class or inner class can have the following members:**

1) data  (class data or instance data)  
2) methods (class method, instance method, static method)  
3) inner class or nested class (again it can another class as inner class, and  
also both data and methods)

when we create the inner class, then the inner is become "member" to  
"outer class", inner class can able to access the outer class members, but  
not vice versa

when we want to create the object to inner classes, we can able to create  
the inner class object, we will use the following ways:  
1) we can create the object inside the outer class  
2) we can create the object outside the outer class using outer class object  
when we create the object of the inner class, outside outer class, then we will use outer class object  to object of the object of the inner class

**example:**

```python
class Sample:
    class Inner1:
        a,b=10,20
    class Inner2:
        x,y=100,200
    class Inner3:
        a1,b1=11,12
print(Sample.Inner1.a)
print(Sample.Inner1.b)
print(Sample.Inner2.x)
print(Sample.Inner2.y)
print(Sample.Inner3.a1)
print(Sample.Inner3.b1)
```

**example:**

```python
class Sample:
    class Inner1:
        a,b=10,20
        @classmethod
        def display1(cls):
            print("this is class method!")
        @staticmethod
        def display2():
             print("this is static method!")
        def display3(self):
             print("this is instance method!")
Sample.Inner1.display1()
Sample.Inner1.display2()
s1=Sample()#object for Outer class
i1=s1.Inner1() #create the object for inner class
i1.display1()
i1.display2()
i1.display3()
```

**example:**

```python
class Sample:
    x,y,z=1,2,3 #class data
    class Inner1:
        """data"""
        a,b,c=10,20,30
        """methods"""
        @classmethod
        def display1(cls):
            print(cls.a,cls.b,cls.c)
            print(Sample.x,Sample.y,Sample.z)
        @staticmethod
        def display2():
            print(Sample.Inner1.a,Sample.Inner1.b,Sample.Inner1.c)
            print(Sample.x,Sample.y,Sample.z)
        def display3():
            print()
Sample.Inner1.display1()
Sample.Inner1.display2()
```

**example:**

```python
class Sample:
    x,y,z=1,2,3 #class data
    class Inner1:
        """data"""
        a,b,c=10,20,30
        """methods"""
        @classmethod
        def display1(cls):
            print(cls.a,cls.b,cls.c)
        def display3(self):
            print("this is inner1 instance method!")
            print(self.a,self.b,self.c)
    #create the object to inner class inside the Sample
    i1=Inner1()
    i1.display3()
    i1.display1()
```

**example:**

```python
class Sample:
    x,y,z=1,2,3 #class data
    class Inner1:
        """data"""
        a,b,c=10,20,30
        """methods"""
        @classmethod
        def display1(cls):
            print(cls.a,cls.b,cls.c)
            print(Sample.x,Sample.y,Sample.z)
        @staticmethod
        def display2():
          print(Sample.Inner1.a,Sample.Inner1.b,Sample.Inner1.c)
        def display3(self):
            print("this is inner1 instance method!")
s1=Sample()
i1=s1.Inner1()
i1.display1()
i1.display2()
i1.display3()
```

**example:**

```python
class Sample:
    class Inner1:
        def __init__(self):
            self.a=10
            self.b=20
            self.c=30
s1=Sample()
#create the object for inner class using outer class object
i1=s1.Inner1()
print(i1.a)
print(i1.b)
print(i1.c)
```

**how to access class members with the anonymous object:**

**code:**

```python
class Sample:
  """data"""
  x,y,z=10,20,30
  """methods"""
  def display1(self):
      print("this is display method!")
s1=Sample()
s1.display1()
print(Sample().x+Sample().y)
Sample().display1()
```

---

## Built-in Classes

the classes what we are creating using "class" keyword are called as "user-defined classes"  
the classes what are given by Python are called as "built-in classes"

**in python, we will have the following built-in classes:**

1) int  
2)float  
3)str  
4)list  
5)tuple  
6)range  
7)dict  
8)set  
9)complex ....................................

---

## Inheritance

inheritance make the class can able to take the properties (members) from the another class  
the class which will give the members to another class , then class is called "Super class or Base class"  
the class which will take the members from the another class", then the  
class is called as "Sub class or Derived class"

**we will have following types of inheritance:**

1) Single inheritance  
2) Multiple Inheritance  
3) Multi-level Inheritance

python supports above all three inheritances

in Single inheritance, only two classes are involved in inheritance , one is  
super class and another is sub class

in Multiple inheritance, two or more super classes will give the members  
to one sub class

in Multi-level inheritance, one super class will give the members to  one  
sub class, again sub class will give to another sub class and so on

in Python, we can able to make a class able to have "any number of  
super classes" , due to python supports "Multiple Inheritance"

in order to give the super class classes or in order to implement the inheritance in python, we will use following syntax:

```python
class sub_class_name(super_class_1,........................):
       pass
```

when we are working with inheritance, we will always use "sub class or  
derived class object to access the both super class and sub class members" . because when we give any class as  "Super Class" to any class  
, then  Super class entire copy will come to Sub class", it means  sub class  
will have "both  super class and sub class" members

with help of super class object , we can access only "super class members"

in python, every class what we create using "class" keyword, then every  
class, by default gets a super class called "object"

**example:**

```python
class Sample: #super class to Sample2
    #class data
    x,y,z=10,20,30
class Sample2(Sample): #sub class to Sample
    #class data
    a,b,c=100,200,300
print(dir(Sample2))
print(Sample2.x)
print(Sample2.y)
print(Sample2.a)
```

when we want to know the  class members using "dir()" function with  
class name, it will always gives the following:  
1) class data  
2) class method  
3) static method  
4) instance method

when we want to know the  class members using "dir()" function with

**object name, it will always gives the following:**

1) class data  
2) class method  
3) static method  
4) instance method  
5) instance data

when we want to retrieve the only "instance data" from the class, we will  
use vars() with object name , this will return result as "dictionary" form

**example:**

```python
class Sample: #super class to Sample2
    #class data
    x,y,z=10,20,30
    def __init__(self,a1,b1):
        self.a1=a1
        self.b1=b1
    #class method
    @classmethod
    def display1(cls):print("class method")
    #static method
    @staticmethod
    def display2():print("static method")
    #instance method
    def display3(self):print("instance method")
class Sample2(Sample): #sub class to Sample
    #class data
    a,b,c=100,200,300
s1=Sample2(1,2)
print(dir(s1))
```

**example:**

```python
class Sample: #super class to Sample2
    #class data
    x,y,z=10,20,30
    def __init__(self,a1,b1):
        self.a1=a1
        self.b1=b1
    #class method
    @classmethod
    def display1(cls):print("class method")
    #static method
    @staticmethod
    def display2():print("static method")
    #instance method
    def display3(self):print("instance method")
class Sample2(Sample): #sub class to Sample
    #class data
    a,b,c=100,200,300
s1=Sample2(1,2)
print(vars(s1))
```

**example:**

```python
class Sample:
    a,b,c=1,2,3
class Sample2:
    x,y,z=10,20,30
#multiple inheritance
class Sample3(Sample,Sample2):
    a1,b1=100,200
s3=Sample3()
print(dir(Sample3))
```

**example:**

```python
#multi-level inheritance
class Sample:
    a,b,c=1,2,3
class Sample2(Sample): #Sample+Sample2
    x,y,z=10,20,30
class Sample3(Sample2):  #sample+Sample2+Sample3
    a1,b1,c1=11,12,13
s3=Sample3()
print(dir(s3))
print(s3.a,s3.b,s3.c,s3.x,s3.y,s3.z)
print(s3.a1,s3.b1,s3.c1)
```

**example:**

```python
#multiple-inheritance
class Sample:
    a,b,c=10,20,30
class Sample2:
    a,x,y=100,200,300
class Sample3(Sample,Sample2):
    a1,b1,c=11,12,400
s3=Sample3()
print(s3.a) #10
print(s3.c) #400
```

**example:**

```python
#multiple-inheritance
class Sample:
    a,b,c=10,20,30
class Sample2:
    a,x,y,b=100,200,300,400
class Sample3(Sample2,Sample):
    a1,b1,c=11,12,400
s3=Sample3()
print(s3.b) #400
print(s3.y) #300
print(s3.a) #100
```

**example:**

```python
class Sample:
    a,b,c=10,20,30
class Sample2(Sample):
    a,b,c=100,200,300
class Sample3(Sample2):
    x,y,z=1,2,3
class Sample4(Sample3):
    a1,b1,c,d=11,12,13,14
s4=Sample4()
print(s4.a)#100
print(s4.b)#200
print(s4.x)#1
print(s4.y)#2
print(s4.d)#14
```

**example:**

```python
class Sample:
    x,y,z,a=10,20,30,100
#self refers current class object
class Sample2(Sample):
    x,y,z=100,200,300
    def display(self):
        print(super().z,super().x,super().y)
        print(self.x,self.y,self.z,self.a)
s2=Sample2()
s2.display()
```

**example:**

```python
class Sample:
    a,b,c=10,20,30
class Sample2:
    x,y,z=1,2,3
class Sample3(Sample2,Sample):
    a,b,c,x,y,z=100,200,300,400,500,600
    def display(self):
        print(super().a)
        print(super().x)
        print(self.a,self.b,self.c)
s3=Sample3()
s3.display()
```

**example:**

```python
class Sample:
    def display(self):
        print("this is display1")
class Sample2:
    def display2(self):
        print("this is display2")
class Sample3(Sample,Sample2):
    def display3(self):
        super().display()
        super().display2()
        print("this is display3")
s3=Sample3()
s3.display3()
```

**example:**

```python
class Sample:
    a,b,c=10,20,30
class Sample2:
    a1,b1,c1,a=1,2,3,11
class Sample3(Sample2,Sample):
    x,y,z,a=101,102,103,0
    def display(self):
        print(super().a+self.x) #11+101 =112
s3=Sample3()
s3.display()
```

in python, when we are working with inheritance, python will use a concept  
called "MRO"

MRO stands for "Method Resolution Order" , when we are working with  
Multiple inheritance , the two ore more super classes may have the data  
with similar name, when we try to access the data using sub class object ,  
then sub class object will access the data using "MRO" in Python

MRO always searches the any data or method from the starting  from the  
same class and then from  all remaining super classes,  all super class searched  which are given  in the order of "left to right " direction , for this order MRO uses an algorithm internally called "C3 linearization"

MRO of the any class is always from "given class to object class"

when we want to know the mro of the class, we will use the following ways:  
1) class\_name.\_\_mro\_\_  
2) class\_name.mro()

**example:**

```python
class Sample:
    a,b,c=10,20,30
class Sample2:
    a1,b1,c1,a=1,2,3,11
class Sample3(Sample2,Sample):
    x,y,z,a=101,102,103,0
    def display(self):
        print(super().a+self.x) #11+101 =112
print(Sample3.__mro__)
print(Sample3.mro())
```

**example:**

```python
class Sample:
    a,b,c=1,2,3
class Sample2(Sample):
    x,y,z=10,20,30
class Sample3(Sample2):
    x1,y1,z1=11,12,13
print(Sample.mro())
print(Sample2.mro())
print(Sample3.mro())
```

**example:**

```python
class Sample:
    pass
class Sample2(Sample):
    pass
class Sample3(Sample2,Sample):
    pass
class Sample4(Sample3,Sample2):
    pass
print(Sample.mro())
print(Sample2.mro())
print(Sample3.mro())
print(Sample4.mro())
```

**example:**

```python
class Sample:
    pass
class Sample2(Sample):
    pass
class Sample3(Sample2,Sample):
    pass
class Sample4(Sample3,Sample2):
    pass
print(Sample4.mro())
```

**example:**

```python
class Sample:
    pass
class Sample2(Sample):
    pass
class Sample3(Sample2,Sample):
    pass
class Sample4(Sample2,Sample3):
    pass
print(Sample4.mro())
#output:
```

TypeError: Cannot create a consistent method resolution  
order (MRO) for bases Sample2, Sample3

**example:**

```python
class Sample:
    pass
class Sample2(Sample):
    pass
class Sample3(Sample2,Sample):
    pass
class Sample4(Sample2):
    pass
print(Sample4.mro())
```

**example:**

```python
class Sample:
    pass
class Sample2(Sample):
    pass
class Sample3(Sample2,Sample):
    pass
class Sample4(Sample3):
    pass
print(Sample4.mro())
```

**example:**

```python
class Sample:
    pass
class Sample2(Sample):
    pass
class Sample3(Sample,Sample2):
    pass
class Sample4(Sample3):
    pass
print(Sample4.mro())
```

**example:**

```python
class Sample:
    pass
class Sample2(Sample):
    pass
class Sample3(Sample2,Sample):
    pass
class Sample4:
    pass
class Sample5(Sample3,Sample):
    pass
print(Sample5.mro())
```

**example:**

```python
class Sample:
    pass
class Sample2(Sample):
    pass
class Sample3(Sample2):
    pass
class Sample4(Sample2):
    pass
class Sample5(Sample3,Sample2):
    pass
print(Sample5.mro())
```

**example:**

```python
class Sample:
    pass
class Sample2(Sample):
    pass
class Sample3(Sample2):
    pass
class Sample4(Sample3,Sample2):
    pass
class Sample5(Sample4,Sample3,Sample2,Sample):
    pass
print(Sample5.mro())
```

**when we are working with MRO, we need to remember the following:**

1) once the class is visited by PVM, it will never going to visit again by  
PVM via MRO  
2) all super classes of the  sub class ends with  "Same super class", then  
MRO will be the same  
3) while MRO of the sub class, it will having multiple different paths while  
visiting, it will throw the "Type Error"

---

## Data Abstraction

Abstraction refers "hiding the member of the class"  
when we give any class as super class to another class, then class will get  
all members of the super class, now we want to make the subclass can  
not able to get  all members of the class via inheritance, then we can  
apply the "abstraction"

**how we can implement the abstraction:**

we can provide the abstraction to class members, we will use access modifiers or access specifiers in Python

**in Python, we will have two access specifiers:**

1) public  
in python, by default all class members are "public"  
no need to specify any member of the class as  "public"  
when the member of the class as "public", the member can able to access  
any where in the program, it means we can able to access outside the  
class or any sub class

**2) private :**

in python, when we want to create the any member of the class as private,  
in python we are going to specify "double underscore" to the "name of the member" of the class  
when the member of the class as "private", the member can able to access  
only with in the class, it means we can not able to access outside the  
class or any sub class

when  we want to access the any data or method of the class any where in the program , then we need define the data or methods as public

when we want to restrict the any data or methods access of any class, then we need to define the data or methods as private

in a class, both "data and methods" can be defined as "private" , when the  
any member of the class defined as private, then private data or private  
methods of the class will not be get by it's sub classes

when we are working with access modifiers inside the class, we will need to

**remember the following:**

1) we can not define the all members of the class as "private", when we  
define the all members of the class as private, then no class members can  
not able to access outside the class and it's sub class , when the class  
contains all members as "private", then the class is called as "Sealed class", this is not recommended

2) we can always need to define the at least one member of the class as  
private

3)  when we define the data of the class as private , in order to access or  
change the any private data outside the class or by it's sub class , we  
will always  need to use the following ways:  
1) using getters or setters  
2) using @property decorator

any private data need to access outside the class or need to change outside the class, we always use "getters" and "setters"

getters are used to access the data  
setters are used to change the data

each data member will have one "getter" and one "setter"

both getter and setters are always need to define as "public"

when we want to create the getters or setters in python, we will always  
recommend to create the "getters and setters" using "@property"  
decorator

when we create the "getters and setters" using "@property" decorator,  
then the data can be accessed using name, like how we call any data using  
object in the same way we can able to access and change the data using  
property decorator

**example:**

```python
class Sample:
    __a,__b,__c=10,20,30
    """getters"""
    def a(self):
        return self.__a
    def b(self):
        return self.__b
    def c(self):
        return self.__c
    """setters"""
    def set_a(self,a):
        self.__a=a
    def set_b(self,b):
        self.__b=b
    def set_c(self,c):
        self.__c=c
s1=Sample()
s1.set_a(100)
s1.set_b(200)
s1.set_c(300)
print(s1.a())
print(s1.b())
print(s1.c())
```

**example:**

```python
class Sample:
    __a,__b,__c=10,20,30
    """getters"""
    @property
    def a(self):
        return self.__a
    @property
    def b(self):
        return self.__b
    @property
    def c(self):
        return self.__c
    """setters"""
    @a.setter
    def a(self,a):
        self.__a=a
    @b.setter
    def b(self,b):
        self.__b=b
    @c.setter
    def c(self,c):
        self.__c=c
s1=Sample()
print(s1.a,s1.b,s1.c)
s1.a,s1.b,s1.c=110,220,330
print(s1.a,s1.b,s1.c)
```

**example:**

```python
class Sample:
    __a,__b=10,20 #private class data
    c,d=30,40 #public class data
    def display(self):#public instance method
        print(self.__a,self.__b)
class Sample2(Sample):
    pass
print(dir(Sample2))
print(Sample2.c,Sample2.d)
s2=Sample2()
s2.display()
```

**example:**

```python
class Sample:
   #constrcutor
   def __init__(self):
       #private instance data
       self.__a=10
       self.__b=20
       #public instance data
       self.c=300
       self.d=400
   def display(self):
       print(self.__a,self.__b)
class Sample2(Sample):
    pass
s2=Sample2()
print(dir(s2))
print(s2.c,s2.d)
s2.display()
```

---

## Data Encapsulation

Encapsulation means "allow the programmer or developer can able to  
define the data and methods at one place, there is it class"

Class is a typical example for "Encapsulation", with help of encapsulating  
the both methods and data as single unit, we are going to use the "classes"

with help of encapsulation, we are creating the both "attributes and  
behaviour of the object" as single unit, by creating inside the class

Data encapsulation means "wrapping the all data into a class, where at least one data member as private "

encapsulated class  means "when the class have at least  one private data member, then the class is called as encapsulated class"

fully-encapsulated  class means  "when the class have all data as  private, then the class is called as fully-encapsulated class"

---

## Abstract Classes

Abstract class is a class, when we say any class is Abstract class in Python,

**the class must have the following:**

1) class must have "ABC" as Base Class  
2) class must have at least one abstract method

"ABC" is "Abstract Base Class"  and it is super class for all "abstract classes" in python

when we want to make any method as "abstract method" , the method always need to define with "@abstractmethod" decorator

**if we say any method is abstract method in python, then the method must need to follow below conditions:**

1) method need to create using "@abstractmethod"  decorator  
2) method need to empty or method does not contain any implementation

**in a class, the following methods can be act as "abstract method"**

1) class method  
2) static method  
3) instance method

in a class, we can able to define any number of "Abstract methods"  
in a program, we can able to create any number of classes as "Abstract  
classes"  
in python, for abstract class, we can not able to create the object or  
abstract class can not be instantiated in Python

when the class can not able to get an object means , the class contain  
the following:  
1) class has "ABC" as super class  
2) class can have "at least one abstract method"

when the class is abstract class, all abstract methods of the class will get  
the implementation by it's sub classes , if sub classes are fail to implement the abstract method of the super class , then sub class also become abstract class and sub class also can not able to get an object

the class which is implementing the "abstract method", then the class is  
called as "implementation class" to the abstract class, always implantation class is  " sub class" to abstract class

when we want to implement the abstract classes in python, we will use  
a module called "abc" , this module will provide the below:  
1) ABC  
2) @abstractmethod

**Abstract Class Coding  Template:**

```python
class Abstract_class_name(ABC):
       #data
       #methods
       #abstract methods
       @abstractmethod
        def method_name(self):
                   pass
```

**why we need abstract classes in Python:**

when we create the class, some times the method implementation is  
"un-known" , due to the method implementation is always depends on  
object  
if we know the object, then the implementation of the method can be given as per the object, then the we will make the method as abstract in the class

**example:**

```python
from abc import ABC,abstractmethod
class FixedDeposit(ABC):
    def __init__(self,amount):
        self.amount=amount
    @abstractmethod
    def interest_amount(self):
        pass
class Minor(FixedDeposit):
    def interest_amount(self):
        return self.amount+self.amount*0.1
class Individual(FixedDeposit):
    def interest_amount(self):
        return self.amount+self.amount*0.2
class GovtEmployee(FixedDeposit):
    def interest_amount(self):
        return self.amount+self.amount*0.3
class SeniorCitezen(FixedDeposit):
    def interest_amount(self):
        return self.amount+self.amount*0.35
m1=Minor(150000)
print(m1.interest_amount())
i1=Individual(200000)
print(i1.interest_amount())
g1=GovtEmployee(200000)
print(g1.interest_amount())
s1=SeniorCitezen(200000)
print(s1.interest_amount())
```

**concrete class:**

concrete  class is a class and which contain all methods with implementation

**Non-concrete class:**

Non-concrete  class is a class and which contain at least one non-concrete method or at least  one method without  implementation, then the class is called as "Non-Concrete Class"

Abstract class is a "Non-Concrete class"

**concrete method:**

concrete method is a method  and which is contains implementation

**Non-concrete method:**

non-concrete method is a method and which is does not contains any  
implementation

abstract method is a  "Non-concrete" method

**example:**

```python
#Non-Concreate Class
class Sample:
    """non-concreate methods"""
    @classmethod
    def display1(cls):
        pass
    @staticmethod
    def display2():
        pass
    def display3(self):
        pass
s1=Sample()
```

**example:**

```python
from abc import ABC, abstractmethod
#abstract class
class Sample(ABC):
    @classmethod
    @abstractmethod
    def display1(cls):#abstract class method
        pass
    @staticmethod
    @abstractmethod
    def display2():#abstract static method
        pass
    @abstractmethod
    def display3(self):#abstract instance method
        pass
s1=Sample()
```

**example:**

```python
from abc import ABC, abstractmethod
#abstract class
class Sample(ABC):
    @classmethod
    @abstractmethod
    def display1(cls):#abstract class method
        pass
    @staticmethod
    @abstractmethod
    def display2():#abstract static method
        pass
    @abstractmethod
    def display3(self):#abstract instance method
        pass
class Sample2(Sample):
    @classmethod
    def display1(cls):
        print("this abstract class method implemented!")
    @staticmethod
    def display2():
         print("this abstract static method implemented!")
    def display3(self):
        print("this is abstract instance method implemented!")
s2=Sample2()
s2.display1()
s2.display2()
s2.display3()
```

---

## Polymorphism

Polymorphism means "Many Forms"  
using this  we can able to make the same "method or operator or function" can act differently based on the given object or data

**example-1:**

```python
#Polymorphism using Operators
print(10+20)#numbers with +
print("hello"+"world")#strings with +
print([1,2,3]+[3,4,5])#lists with +
print((10,20,30)+(30,40,50))#tuples with +
```

**example-2:**

```python
#Polymorphism using functions
def sum(a=10,b=20,c=30):
    return a+b+c
print(sum())#a=10,b=20,c=30
print(sum(100,200))#a=100,b=200
print(sum(1,2,3))#a=1,b=2,c=3
print(sum(c=2000))
```

**example-3:**

```python
#Polymorphism with methods
class Sample:
    def sum(self,a=10,b=20,c=30):
        return a+b+c
s1=Sample()
print(s1.sum())
print(s1.sum(100))
print(s1.sum(100,200))
```

**example:**

```python
#Polymorphism with constructor
class Sample:
    def __init__(self,a=10,b=20,c=30):
       self.a,self.b,self.c=a,b,c
s1=Sample()
print(s1.a,s1.b,s1.c)
s1=Sample(100)
print(s1.a,s1.b,s1.c)
s1=Sample(c=2000)
print(s1.a,s1.b,s1.c)
s1=Sample(b=200)
print(s1.a,s1.b,s1.c)
```

**in general, polymorphism is two types:**

**1) static polymorphism or compile-time polymorphism**

this polymorphism will exhibited at the time of the compile-time, this  
not  available in Python  
example: method overloading

**2) run-time polymorphism or Dynamic Polymorphism**

this polymorphism will exhibited at the time of the run-time, this  
only available in Python  
example:  Operator overloading , Method Overriding

**how many ways, we can implement the Polymorphism in Python**

**1) Duck Typing:**

this one of the way of implementing polymorphism in Python, here the method does not check the given object is what type, it checks the object  
class contain the method or not

**example:**

```python
class Duck:
    def sound(self):
        print("Quack Quack!")
class Snake:
    def  sound(self):
        print("Buss buss!")
class Frog:
    def  sound(self):
        print("beck beck!")
class Human:
    def  sound(self):
        print("human can make sound!")
def duck_method(obj):
    obj.sound()
d1=Duck()
s1=Snake()
f1=Frog()
h1=Human()
duck_method(h1)
```

**2) Method overriding**

method overriding means "define the same method in the super class and  
sub class with the same name", the sub class method will override the  
super class method  
when we want to implement the "method overriding", we will use the  
"inheritance"

method overriding is also called as "Polymorphism through inheritance"

**example:**

```python
class Sample:
    def display(self):
        print("this method is from the Sample class")
class Sample2(Sample):
    def display(self):
        print("this method is from the Sample2 class")
s2=Sample2()
s2.display()
```

**example:**

```python
class Polygon:
    def __init__(self,base,height):
        self.base,self.height=base,height
    def area(self):
        print(self.base)
        print(self.height)
class Triangle(Polygon):
    def area(self):
        print(self.base)
        print(self.height)
        print(f'area:{0.5*self.base*self.height}')
class Square(Polygon):
    def area(self):
        print(self.base)
        print(self.height)
        print(f'area:{self.base*self.height}')
t1=Triangle(10,20)
t1.area()
s1=Square(10,10)
s1.area()
```

**example:**

```python
class Polygon:
    def __init__(self,base,height):
        self.base,self.height=base,height
    def area(self):
        print(self.base)
        print(self.height)
class Triangle(Polygon):
    def area(self):
        print(self.base)
        print(self.height)
        print(f'area:{0.5*self.base*self.height}')
class Square(Polygon):
    def area(self):
        print(self.base)
        print(self.height)
        print(f'area:{self.base*self.height}')
objects=[Polygon(10, 20),Triangle(1,2),Square(1,1)]
for obj in objects:
    obj.area()
```

**3) functional Polymorphism**

in python, we do not have "method overloading"  
method overloading means "define the method with same name, but change in number of arguments or number of type of arguments"  
python does not implement "method overloading" directly  like other language like C++, Java  
in python, when we want to implement method overloading , we will always define the method with default arguments , it is not a direct  
implementation, it is indirect  implementation and the behaviour of the  
will different, how we call the method with object

**example:**

```python
class Sample:
    def display(self,a=10,b=20,c=30):
        print(a,b,c)
s1=Sample()
s1.display()#10 20 30
s1.display(1,2)
s1.display(c=200,b=200,a=100)
def display(a=1,b=2,c=3):
    print(a,b,c)
display()#1 2 3
display(10,20)#10 20 3
display(b=200, a=100, c=200)
```

**4) constructor Polymorphism**

in a class , we can define  only one either "default or parameterized constructor", we can not define both constructor as a part of the class  
in python, we can not implement the constructor overloading , but we  
can able to call the same constructor with different number of arguments  
while creating the object to the class, for this we need to define the constructor with default arguments

**example:**

```python
class Sample:
    def __init__(self,a=1,b=2,c=30):
        self.a,self.b,self.c=a,b,c
        print(self.a,self.b,self.c)
s1=Sample()
s2=Sample(10)
s3=Sample(c=300)
s4=Sample(b=200)
class Sample2:
    def __init__(self):
        self.a,self.b,self.c=1,2,3
        print(self.a,self.b,self.c)
s1=Sample2()
```

**5) Operator overloading**

if same operator will work with different operands and perform different  
operation, then the operator is called "overloaded operator"

**example for overloaded operators:**

1. "+" ===\> addition of two numbers, concatenation of lists, strings,tuples  
2."-"  ===\> subtraction of two numbers, difference of two sets  
3."\*" ===\> product of the two numbers, un-packing, repetition  
4."\|" ===\> bitwise or on numbers, sets union, dictionary merge  
5."^" ===\> bitwise exclusive or on numbers, symmetric difference of sets  
6."&" ==\> bitwise and on numbers, intersection of the two sets ..........

**example:**

```python
#overloaded operators
print(12+13)
print("a"+"b")
print([1,2,3]+[4,5,6])
print((10,20,30)+(30,40))
print(10|20)
print({1,2,3}|{2,3,4})
print({1:2}|{2:3})
print(10-20)
print({1,2}-{2,1})
print({1,2}^{2,3})
```

in Python, we can able to implement the operator overloading  
when we want to implement the operator overloading in python we will  
use "dunder or magic methods" in python  
magic method is a method, which can be called automatically in python for  
every operation what we do on the objects, it means, in python every operation is always carried by magic methods or dunder methods  
these methods are we need to call manually like normal method, these  
methods are called automatically based on the operation what we do  
on objects  
magic method are also called as "dunder methods"  
this method name always "starts and ends with double underscore"  
example:  \_\_init\_\_, \_\_add\_\_,\_\_mul\_\_,\_\_gt\_\_,\_\_str\_\_,\_\_rper\_\_,\_\_new\_\_,  
\_\_name\_\_, ......................

**example:**

```python
class Sample:
    def __init__(self,name):
        self.name=name
    def __str__(self):
        return f"this is {self.name} object of Sample class"

s1=Sample("s1")
s2=Sample("s2")
print(s1)
print(s2)
```

**example-2:**

```python
class Sample:
    def __init__(self,a,b,c):
        self.a,self.b,self.c=a,b,c
    def __call__(self):
        return f"a:{self.a},b:{self.b},c:{self.c}"
s1=Sample(1,2,3)
print(s1())
```

**example:**

```python
class Sample:
    #constrcutor
    def __init__(self,a,b,c):
        self.a,self.b,self.c=a,b,c
    #destrcutor (remove the object and it's resources)
    def __del__(self):
        print("the object is removed!")
s1=Sample(1,2,3)
```

del s1 #it will call the destrcutor (\_\_del\_\_)

**example:**

```python
class Sample:
    #constrcutor
    def __init__(self):
        self.mylist=[10,20,30,40]
    #to access the data
    def __getitem__(self,index):
        return self.mylist[index]
    #to change the any data
    def __setitem__(self,index,value):
        self.mylist[index]=value

s1=Sample()
s1[0]=100#it will call the __setitem__(0,100)
```

print(s1\[0\])#it will call the \_\_getitem\_\_(0)  
s1\[-1\]=1000#it will call the \_\_setitem\_\_(-1,1000)  
print(s1\[-1\])#it will call the \_\_getitem\_\_(-1)

operator overloading means "giving the new behaviour to the same operator, based on the data, it will  different operation"  
when we want to implement the operator overloading we will use "magic  
methods"

**Operator overloading in Python means    "operator + magic method "**

\+   ===\> \_\_add\_\_  
\-  ===\> \_\_sub\_\_  
\*  ===\>\_\_mul\_\_  
\> ===\> \_\_gt\_\_  
\< ===\> \_\_lt\_\_  
\==  ===\> \_\_eq\_\_

**example:**

```python
print(10+20)
a,b=10,20
print(a.__add__(b))
print(a-b)
print(a.__sub__(b))
print(a>b)
print(a.__gt__(b))
print(a<b)
print(a.__lt__(b))
print(a==b)
print(a.__eq__(b))
print(a*b)
print(a.__mul__(b))
print(a.__truediv__(b))
```

when we are working with operator overloading, we will always need  
implement via classes, because it will applied always on objects

**Operator overloading with "+"**

**example:**

```python
class Sample:
    def __init__(self,a,b):
        self.a,self.b=a,b
    def __add__(self,other):
        return self.a+other.a+self.b+other.b
s1=Sample(10,20)
s2=Sample(100,200)
print(s1+s2)
```

**example:**

```python
class Sample:
    def __init__(self,a,b):
        self.a,self.b=a,b
    def __add__(self,other):
        return self.a+other.a,self.b+other.b
s1=Sample(10,20)
s2=Sample(100,200)
print(s1+s2)
```

**Operator overloading with "-"**

**example:**

```python
class Sample:
    def __init__(self,a,b):
        self.a,self.b=a,b
    def __sub__(self,other):
        return self.a-other.a,self.b-other.b
s1=Sample(10,20)
s2=Sample(100,200)
print(s1-s2)
```

**Operator overloading with "\*"**

**example:**

```python
class Sample:
    def __init__(self,a,b):
        self.a,self.b=a,b
    def __mul__(self,other):
        return self.a*other.a,self.b*other.b
s1=Sample(10,20)
s2=Sample(100,200)
print(s1*s2)
```

**Operator overloading with "\>"**

**example:**

```python
class Sample:
    def __init__(self,a,b):
        self.a,self.b=a,b
    def __gt__(self,other):
        return self.a>other.a,self.b>other.b
s1=Sample(10,20)
s2=Sample(100,200)
print(s1>s2)
```

**Operator overloading with "\<"**

**example:**

```python
class Sample:
    def __init__(self,a,b):
        self.a,self.b=a,b
    def __lt__(self,other):
        return self.a<other.a,self.b<other.b
s1=Sample(10,20)
s2=Sample(100,200)
print(s1<s2)
```

**Operator overloading with "=="**

**example:**

```python
class Sample:
    def __init__(self,a,b):
        self.a,self.b=a,b
    def __eq__(self,other):
        return self.a==other.a,self.b==other.b
s1=Sample(10,20)
s2=Sample(100,200)
print(s1==s2)
```

**example:**

```python
class Sample:
    def __init__(self,a,b):
        self.a,self.b=a,b
    def __eq__(self,value):
        return self.a==value,self.b==value
s1=Sample(10,20)
print(s1==s1) #(10,20)
```

**the following are important magic methods in python need to know:**

1) \_\_init\_\_() \<=== it is constructor  
2) \_\_call\_\_() \<=== it will make the object to call like a method  
3) \_\_getitem\_\_() \<=== it make the object to access the data directly  
4) \_\_setitem\_\_() \<== it make the object to change the data directly  
5) \_\_new\_\_() \<=== it call while creation of the class  
6) \_\_str\_\_() \<=== it will make the object can a message  thorough the  
object  
7) \_\_del\_\_() \<=== it is called as "Destructor" and it will called when we  
remove the object using "del"

**difference between "\_\_new\_\_"  and "\_\_init\_\_":**

\_\_new\_\_ and  \_\_init\_\_ are magic methods

\_\_new\_\_ is a class method

\_\_init\_\_ is a instance method

\_\_new \_\_ and \_\_init\_\_ , if both are present inside the class ,  first always  
\_\_new\_\_ will called , later \_\_init\_\_ will be called . \_\_new \_\_ will called  at the time of  object creation, after the execution, it will called the \_\_init\_\_

if we have any constructor inside the class, it will always executed during the object creation

in python , constructor is used to "initialized the data of the object",  
the constructor always called for "initialization of the data of the object"

**example:**

```python
class Sample:
    def __new__(cls): #1
        cls.a,cls.b,cls.c=1,2,3
        print("object is creating!")
        return super().__new__(cls)
    def __init__(self): #2
        print("constructor is called")
        self.a1,self.b1,self.c1=10,20,30
s1=Sample()
print(s1.a1,s1.b1)
```

---

## Singleton Class

singleton class  is a "design pattern"  of the OOPS  
single class can able to  have only one instance or object always , it will  
never make the class can have "multiple" objects , it may have multiple different references (names), but all are reside at same memory location

**example:**

```python
class Sample:
    a=10
    b=20
    c=30
    def __init__(self,a,b):
        self.a1,self.b1=a,b
    def display(self):
        print(self.a,self.b,self.c,self.a1,self.b1)
s1=Sample(1, 2)
s2=Sample(11, 12)
print(id(s1))
print(id(s2))
```

**example:**

```python
class Singleton:
    _instance=None
    def __new__(cls):
        if cls._instance is None:
            cls._instance=super().__new__(cls)
            return cls._instance
        else:
            return cls._instance
s1=Singleton()
s2=Singleton()
print(id(s1))
print(id(s2))
```

**example:**

```python
class Singleton:
    _instance=None
    def __new__(cls,a,b):
        cls.a,cls.b=a,b
        if cls._instance is None:
            cls._instance=super().__new__(cls)
            return cls._instance
        else:
            return cls._instance
s1=Singleton(10,20)
print(s1.a,s1.b)
s2=Singleton(s1.a,s1.b)
print(id(s1))
print(id(s2))
print(s1.a,s1.b)
```

when we are working with "\_\_new\_\_" method, always the must return  
super class \_\_new\_\_ method, otherwise the \_\_new\_\_ will return always  
"None" as result, when we create the object , here the super class is  
"object" class

in general, when we create the object to the class, every class will have  
"object" as super class and that will have "\_\_new\_\_()", this is will able  
to make the object to the class, when we actually create the object to  
the class

---

## Meta Classes

Meta class is a class , which is used to create the another class  
using meta classes , we can able to give the default behaviour and data  
to the class while creating the class itself  
generally, any class we create the "data and methods", we will specify  
inside the class  
when we want to create the class by using another class, then in python  
we will use "meta classes"

when we create the a class using "Meta class", the class gets default the  
following :  
1) data  
2) methods  
3) super classes

when we want to create the meta class in python, we will use the following  
steps:

**step-1:**

create the class with some name and the class must take a super class  
called  as "type"  
this class will act as "Meta class"

when we want to make the  meta class need to give any default data or  
methods or bases classes to class which is created by meta class, we need  
to create a method called "\_\_new\_\_()" inside the meta class with following structure:

```python
          def  __new__(cls,name,bases,dct):
               #write the logic here
```

name refers "the name of the class which is created by meta class"  
bases refers "the bases classes which are gets by the class which is  created by Meta class"  
bases is a "Tuple"  
dct refers "the data and methods" of the class which is created by Meta  
class  
dct is a "dictionary"

at the end, this method always return "super" class \_\_new\_\_() method  
step-2:  
create the class using Meta class , when we want to create the class using  
meta class, we will use the following syntax:

```python
  class class_name(metaclass=Meta_class_name):
```

write the logic here

**example:**

```python
class MyMetaClass(type):
    pass
class Sample(metaclass=MyMetaClass):
     pass
print(type(Sample))
print(type(type(Sample)))
```

**example:**

```python
class MyMetaClass(type):
    def __new__(cls,name,bases,dct):
        print(f"name of the class:{name}")
        return super().__new__(cls,name,bases,dct)
class Sample(metaclass=MyMetaClass):
    pass
class Sample2(metaclass=MyMetaClass):
    pass
```

**example:**

```python
class MyMetaClass(type):
    def __new__(cls,name,bases,dct):
        print(f"name of the class:{name}")
        #define the data
        dct['a']=100
        dct['b']=200
        dct['c']=300
        @classmethod
        def display(cls):print("Class method")
        @staticmethod
        def display2():print("static method")
        def display3(self):print("instance method")
        dct['display']=display
        dct['display2']=display2
        dct['mydisplay3']=display3
        return super().__new__(cls,name,bases,dct)
class Sample(metaclass=MyMetaClass):
    pass
class Sample2(metaclass=MyMetaClass):
    pass
print(dir(Sample))
print(dir(Sample2))
```

**example:**

```python
class super1:
    a,b,c=10,20,30
class super2:
    x,y,z=1,2,3
class super3:
    a1,b1,c1=100,200,300
class MyMetaClass(type):
    def __new__(cls,name,bases,dct):
        print(f"name of the class:{name}")
        bases=(super1,super2,super3)
        return super().__new__(cls,name,bases,dct)
class Sample(metaclass=MyMetaClass):
    pass
class Sample2(metaclass=MyMetaClass):
    pass
print(dir(Sample))
print(dir(Sample2))
```

**create a class in python, without using class keyword:**

we create the class without using class keyword, we can create the class  
using  "meta class"  
when we want to create the class without  using meta class, we will use

**following ways:**

1) using a built-in meta class called "type"  
2) using a user defined meta class

**example:**

```python
a=10
b=20
c=30
def display():
    print("this is the method from the display")
Sample=type("Sample",(),{'a':a,'b':b,'c':c,'display':display})
s1=Sample()
print(s1.a)
print(s1.b)
print(s1.c)
```

**example:**

```python
class MyMetaClass(type):
    def __new__(cls,name,bases,dct):
        print(f"name of the class:{name}")
        return super().__new__(cls,name,bases,dct)
s1=MyMetaClass("Sample",(),{'a':100,'b':200})
print(type(s1))
print(type(type(s1)))
print(s1.a)
print(s1.b)
print(s1)
```

---

## Data Classes

in python we can able to create a class using "data classes", when we want  
create the class using  "dataclass" decorator, in python we will use a module called "dataclasses"  
when we create the class using "@dataclass" decorator, the class will create the constructor automatically with given data  
when we want to define the data in the class which is created using "@dataclass" decorator, we will use the following syntax:

```python
@dataclass
class class_name:
     data_name1:type
     data_name2:type
     data_name3:type
```

.  
.  
data\_namen:type

when we create the class using  "@dataclass" decorator , the class automatically gets the following methods:  
1) \_\_init\_\_  
2) \_\_eq\_\_  
3) \_\_repr\_\_

when we want to create the data with default values, we can able to  
create the data with value, while creating the class using "@dataclass"  
constructor

when we create the class using "@dataclass"  decorator,  we can specify the class data without type hinting, we can specify the instance data using  
type hinting

when we create the class using "@dataclass" decorator, the class can be  
as following types:  
1) mutable class  
2) immutable  class

by default , when we create the class using "@dataclass" decorator , the  
class is always "mutable class"

when we want to make the class which is created using "@dataclass" decorator as  "immutable", the class must define with "frozen" as True

when we want to compare the objects using "\>,\<,\>=,\<=" operators, then  
we can define the class using "@dataclass" decorator, by taking an argument called "order=True"

when we give the "@dataclass(order=True)", it will create the following  
magic methods inside the class, with this we can compare the objects using \>,\<,\>=,\<=,==,!=:

```python
__lt__(),__gt__(),__lte__(),__gte__(),__ne__()
```

**example:**

```python
from dataclasses import dataclass
@dataclass
class Sample:
    """the following data taken by
    constructor as arguments"""
    a:int
    b:int
    c:int
    d:int
    """
    def __init__(self,a,b,c):
        self.a,self.b,self.c=a,b,c
    """
s1=Sample(10,20,30,40)
print(s1.a,s1.b,s1.c,s1.d)
```

**example:**

```python
from dataclasses import dataclass
@dataclass
class Sample:
    """the following data taken by
    constructor as arguments"""
    a:int
    b:int
    c:int
    d:int
    """
    def __init__(self,a,b,c):
        self.a,self.b,self.c=a,b,c
    """
s1=Sample(10,20,30,40)
s2=Sample(10,20,30,40)
print(s1) #__repr__
print(s1==s2)
```

**example:**

```python
from dataclasses import dataclass
@dataclass
class Sample:
    """the following data taken by
    constructor as arguments"""
    a:int=10
    b:int=20
    c:int=30
    d:int=40
    """
    def __init__(self,a,b,c):
        self.a,self.b,self.c=a,b,c
    """
s1=Sample()#a=10,b=20,c=30,d=40
s2=Sample(100,200,300,400)#a=100,b=200,c=300,d=400
print(s2) #__repr__
print(s1==s2)
```

**example:**

```python
from dataclasses import dataclass
@dataclass
class Sample:
    """class data"""
    a=10
    b=20
    c=30
    """instance data"""
    a1:int=100
    b1:int=200
s1=Sample()
print(s1)
print(Sample.a)
print(Sample.b)
print(s1.a1,s1.b1)
```

**example:**

```python
from dataclasses import dataclass
@dataclass
class Sample: #mutable class
    a:int=10
    b:int=20
    c:int=30
s1=Sample()
print(s1.a,s1.b,s1.c)
s1.a,s1.b,s1.c=100,200,300
print(s1.a,s1.b,s1.c)
```

**example:**

```python
from dataclasses import dataclass
@dataclass(frozen=True)
class Sample: #Immutable class
    a:int=10
    b:int=20
    c:int=30
s1=Sample()
print(s1.a,s1.b,s1.c)
#s1.a,s1.b,s1.c=100,200,300
print(s1.a,s1.b,s1.c)
```

**example:**

```python
from dataclasses import dataclass
@dataclass(frozen=True,order=True)
class Sample: #Immutable class
    a:int=10
    b:int=20
    c:int=30
s1=Sample()
s2=Sample(100,2,3)
print(s1==s2)
print(s1>s2)#__gt__
print(s1<s2)#__lt__
print(s1>=s2)#__gte__
print(s1<=s2)#__lte__
print(s1!=s2)
```

**example:**

```python
from dataclasses import dataclass
@dataclass(frozen=True,order=True)
class Sample: #Immutable class
    a:int=None
    b:int=None
    c:int=None
s1=Sample()
print(s1)
s2=Sample(10)
print(s2)
s3=Sample(10,20)
print(s3)
s4=Sample(b=400)
print(s4)
```

**example:**

```python
from dataclasses import dataclass
from typing import Optional
@dataclass(frozen=True,order=True)
class Sample: #Immutable class
    a:Optional[int]=None
    b:Optional[int]=None
    c:Optional[int]=None
s1=Sample()
print(s1)
s2=Sample(10)
print(s2)
s3=Sample(10,20)
print(s3)
s4=Sample(b=400)
print(s4)
```

**example:**

```python
from dataclasses import dataclass
@dataclass
class Sample: #Immutable class
   a:int
   b:int
   l1:list[int]
s1=Sample(10,20,[1,2,3])
print(s1)
s2=Sample(11,12,[10,20,30])
print(s2)
s3=s1 #both refer same memory location
print(id(s3))
print(id(s1))
s4=s2
s1.l1.append(100)
print(s3)
print(s1)
```

when we are working with "class" which is created using "@dataclass"  
decorator, we will use a method called  "field" and which is also from  
dataclasses module

**example:**

```python
from dataclasses import dataclass,field
@dataclass
class Sample:
    a:int=field(init=True)
    b:int=field(init=True)
    c:int
s1=Sample(100,200,300)
print(s1)
print(s1.c)
```

**example:**

```python
from dataclasses import dataclass,field
@dataclass
class Sample:
    a:int=field(init=True,default=10)
    b:int=field(init=True,default=20)
    c:int=field(init=True,default=30)
s1=Sample(100,200,300)
print(s1)
s2=Sample()
print(s2)
s3=Sample(c=3000)
print(s3)
```

**example:**

```python
from dataclasses import dataclass,field
@dataclass(order=True)
class Sample:
    a:int=field(init=True,default=10,compare=False)
    b:int=field(init=True,default=20,compare=False)
    c:int=field(init=True,default=30,compare=False)
s1=Sample()
print(s1)
s2=Sample(1,2,3)
print(s2)
print(s1==s2)#True
print(s1>s2)#False
print(s1<s2)#False
print(s1>=s2)
print(s1<=s2)
```

**example:**

```python
from dataclasses import dataclass,field
@dataclass(order=True)
class Sample:
    a:int=field(init=True,default=10,compare=False)
    b:int=field(init=True,default=20,compare=False)
    c:int=field(init=True,default=30,compare=False)
s1=Sample() #====> ()
print(s1)
s2=Sample(1,2,3)
print(s2) # ===> ()
print(s1==s2)#True () ===()
print(s1>s2)#False () > ()
print(s1<s2)#False () < ()
print(s1>=s2) #True () >= ()
print(s1<=s2)#False () <= ()
```

**example:**

```python
from dataclasses import dataclass,field
@dataclass(order=True)
class Sample:
    a:int=field(init=True,default=10,compare=False)
    b:int=field(init=True,default=20,compare=True)
    c:int=field(init=True,default=30,compare=True)
s1=Sample() #====> (20,30)
print(s1)
s2=Sample(1,2,3)
print(s2) # ===> (2,3)
print(s1==s2)#True (20,30) ===(2,3)
print(s1>s2)#False (20,30) > (2,3)
print(s1<s2)#False (20,30) < (2,3)
print(s1>=s2) #True (20,30) >= (2,3)
print(s1<=s2)#False (20,30) <= (2,3)
```

**example:**

```python
from dataclasses import dataclass,field
@dataclass(order=True)
class Sample:
    a:int=field(init=True,repr=False)
    b:int=field(init=True,repr=False)
    c:int=field(init=True,repr=False)
s1=Sample(1,2,3)
print(s1)
```

**example:**

```python
from dataclasses import dataclass,field
@dataclass(order=True)
class Sample:
    a:int=field(init=True,repr=True)
    b:int=field(init=True,repr=True)
    c:int=field(init=True,repr=True)
s1=Sample(1,2,3)
print(s1)
```

**use of Data classes in Python:**

\===\> we can create the instance data with type hinting  
\===\> we can create the class data without type hinting  
\===\> using data classes we can able to give the right data to the instance  
data of the class, with this we can able to achieve the data validation  
here the data validation can done through the "Annotations" of the data  
syntax:  
class\_name.\_\_annotations\_\_  
because of this reason,  
we can these classes in  
API development  
while working with databases  
compare the data of the objects  
because data classes also allow the programmers or developers can able to compare the objects using "\>,\<,\>=,\<=,==,!="

**example:**

```python
from dataclasses import dataclass,field
@dataclass(order=True)
class Sample:
    a:int=field(init=True,repr=True)
    b:int=field(init=True,repr=True)
    c:int=field(init=True,repr=True)
print(Sample.__annotations__)
```

---

## OOPS Relationships

**Association:**

Association means "uses or work with" relation in OOPS  
when give the relation called "Association", between two classes will works or uses together, but both are independent with each other

**example:**

```python
class Teacher:
    @classmethod
    def create_data(cls):
        cls.id=int(input("id:"))
        cls.name=input("name:")
    def display(self,stu_name,stu_id):
        print("from the teacher class")
        print(f"id of the teacher:{self.id}")
        print(f'name of the teacher:{self.name}')
        print(f"name of the student:{stu_name}")
        print(f"id of the student:{stu_id}")
class Student:
    @classmethod
    def create_data(cls):
        cls.id=int(input("id:"))
        cls.name=input("name:")

    def display(self):
        print("from the strudent class")
t1=Teacher()
s1=Student()
s1.create_data()
t1.create_data()
t1.display(s1.name,s1.id)
```

in above example, teacher class object can able to share the data of the  
student using display method, the relation between the teacher class  
and student class is "Association"

**Aggregation :**

Aggregation is also called as "Has-a" relation  
Aggregation makes a class can be part of the another class, then the class  
what contained by another class, the contained can exit independently ,  
this relation is a "Weak relation"  
Aggregation can allow "one class can be part of the another class", contained class can exists indepently

**example:**

```python
class Employee:
    def __init__(self):
        self.id=int(input("id:"))
        self.name=input("name:")
        self.designation=input("name:")
    def display(self):
        print(self.id)
        print(self.name)
        print(self.designation)
class Department:
    def __init__(self,stu_obj):
        self.stu_obj=stu_obj
    def display(self):
        print("this is from the Department class")
        print(self.stu_obj.id)
        print(self.stu_obj.name)
        print(self.stu_obj.designation)
e1=Employee()
d1=Department(e1)
d1.display()
e1.display()
```

**Composition**

composition is also called as "has-a" relationship  
in the composition, the class is  part of the another class , because of this  
reason , this relation is also called "has-a with strong relationship"

**example:**

```python
class Engine:
    def start(self):
        print("Engine is started!")
    def stop(self):
        print("Engine is stoped!")
class Car:
    def __init__(self):
        self.e1=Engine()
    def display(self):
        self.e1.start()
c1=Car()
c1.display()
```

**IS-a Relationship**

in OOPS, is-a relationship means "Inheritance"  
is-a relationship means "one class derives another class"

**example:**

```python
class Vehicle:
    def __init__(self):
        self.type=input("type:")
        self.no_of_tyres=int(input("tyres:"))
        self.brand=input("brand:")
        self.model=input("model_name:")
        self.color=input("color:")
class Bike(Vehicle):
    pass
class Car(Vehicle):
    pass
class Bus(Vehicle):
    pass
```

**5.Dependency:**

when the class uses another class temporarily for some specific operation,  
the relationship between the class is "Dependency"

**example:**

```python
class Teacher:
    def __init__(self):
        self.id,self.name=100,"abc"
    def course(self,obj):
        print(f"{self.name} teaches Python")
        print(f"the student is leanring:{obj.name}")
class Student:
    def __init__(self):
        self.id,self.name=1,'p'
t1=Teacher()
s1=Student()
t1.course(s1)
```

**write a python program to swap the given two numbers:**

code:

```python
a=int(input("a:"))
b=int(input("b:"))
a,b=b,a
print(a,b)
```

---

## Exception Handling

Exception means "run-time error"  
Exception is not a "syntax error"  
when we have Exceptions in the code, the complete code or program will  
not execute, due to this we unable to get the output, due to  this we will  
employ the a process called  "Exception handling"  
exception handling is a process of handling exceptions using exception  
handlers

**in python, we will have the following exception handlers:**

1.try  
try is used to write the code which may cause the exception or which may  
give the exception

2.except  
except is used to write code which may give the details about the  
exception or which may handle the exception

3.raise  
raise is used by the programmer or developer  to raise any built-in exception or user-defined exception explicitly in the program

4.finally  
finally is used to execute any code in the program always when there is  
exception or when there is no exception

5.assert  
assert is used to check the every line of the program or when we want  
to de-bug the every line of the program, we are going to "assert"

**exception handling code template:**

```python
try:
     #here we will write the code which may cause the exception or
     which may give the exception
except exception_name1:#optional
except exception_name2:
except exception_name3:
.
.
.
except:
else:#optional
      #here we will write the code, this code will execute only when there
      is no exception in the try
finally:#optional
      #here we will write the code, this code will execute when there is
```

exception or when there is no exception

**example:**

```python
try:
  a=int(input("a:"))
  b=int(input("b:"))
except:
    print("check a and b value!")
else:
    a,b=b,a
    print(a,b)
```

**example:**

```python
def swap():
    try:
      a=int(input("a:"))
      b=int(input("b:"))
    except:
        print("check a and b value!")
        swap()
    else:
        a,b=b,a
        print(a,b)
swap()
```

**example:**

```python
#check the given number is prime or not
def prime():
    try:
        a=int(input("a:"))
    except:
        print("please give valid integer for a")
        prime()
    else:
        l1=[fact for fact in range(1,a+1) if a%fact==0]
        if l1==[1,a]:
            print("prime")
        else:
            print("not prime")
prime()
```

**example:**

write a python program to create list with given size, where every number

**must be even , otherwise do not add the number into list:**

**code:**

```python
l1=[]
def create_list():
    global l1,size
    try:
        num=int(input("num:"))
        if num%2!=0 and size!=0:
            create_list()
        else:
            l1+=[num]
            size-=1
            if size!=0:
              create_list()
    except:
        print("please give valid integer")
try:
    size=int(input("size:"))
except:
    print("please take right size")
else:
    create_list()
    print(l1)
```

**in Python, we will have two types of exceptions:**

**1) Built-in exceptions :**

these exceptions are given by Python  
these exception are called or raised for a specific in the program

**the following important built-in exceptions:**

**1) TypeError :**

when we perform any wrong operation on the data or when we use wrong  
operator on the data for operation or when we call the function with wrong number of arguments, python will raise this exception

**example:**

```python
def swap(a,b):
    a,b=b,a
    return a,b
try:
    a=int(input("a:"))
    b=int(input("b:"))
    a,b=swap(a,b)
    print(a+"b"+b)
except ValueError as e:
    print(e)
except TypeError as e:
    """this except block will execute only
    exception is realted to type Error"""
    print("from Type Error block")
    print(e)
except:
    print("please check the logic once!")
else:
    print(a,b)
```

**2) IndexError:**

when we try access data from the "list or string or range() or tuple" with  
wrong index, we will get this exception

**example:**

```python
l1=[1,2,3,4,5,6]
t1=(10,20,30,40,50)
s1="hello"
try:
  print(s1[40])
except IndexError as e:
    print(e)
except:
    print("please check the logic once!")
```

**3)KeyError**

when we try to access the dictionary data with wrong key, we will get this  
exception

**example:**

```python
d1={1:2,3:4,5:6,7:8,9:10}
try:
  print(d1[1])
except KeyError as e:
    print("Key Error:",end=" ")
    print(e,end=" ")
    print("is not avaliable in the Dictionary!")
except:
    print("please check the logic once!")
```

**4)AttributeError:**

when we try access any method/data from the class using object , if the method or data is not available in the class, we will get this exception

**example:**

```python
class Sample:
    a=10
    b=20
    def display(self):print("method from Sample!")
try:
  s1=Sample()
  print(s1.a)
  s1.display()
except AttributeError as e:
    print(e)
except:
    print("please check the logic once!")
```

**5)ValueError:**

when we try take any wrong data for type conversion, when we try to  
remove the data from the set, we will get this error

**example:**

```python
s1={1,2,3,4,5,6,7,8,9,10}
s2=[1,2,3,4,5]
try:
  s1.remove(100)
  s2.remove(100)
except ValueError as e:
    print(e)
except KeyError as e:
    print("Key Error: ",end="")
    print(e)
    print("100 is not there in the set")
except:
    print("please check the logic once!")
```

**6)NameError :**

this exception will occurred when we use any name which is not defined  
in the program or code or class  
code:

```python
try:
    class Sample:
        def display(self):
            self.a=x
    s1=Sample()
    s1.display()
except NameError as e:
    print(e)
except:
    print("please check the logic once!")
```

**7)ModuleNotFoundError**

when we try to import a module which is not present, we will get this exception

**example:**

```python
try:
   import abcd
   print(abcd.a)
except ModuleNotFoundError as e:
    print(e)
except:
    print("please check the logic once!")
```

**8.RecursionError:**

when we unable to give the condition to stop the recursion, then Function will keep on calling itself, then we will get "RecusrionError"

**example:**

```python
try:
  def sample():
      sample()
  sample()
except RecursionError as e:
    print(e)
except:
    print("please check the logic once!")
```

**9.MemoryError:**

when the memory is unavailable to store the data we will get this  
exception

**10.OverflowError:**

when the result is too high to compute or to high to store we will get this  
exception

```python
try:
  print([1,2,3,4,5,6,7]*(10**2**20))
except MemoryError as e:
    print(e)
except OverflowError as e:
    print(e)
```

**11.FileNotFoundError:**

when the given file is not available in the given path

**example:**

```python
try:
  fp=open("sample12345.txt","r")
except FileNotFoundError as e:
    print(e)
except:
    print("plese check the logic")
```

**12.StopIteration:**

when we are try to read the data from the iterator using next() function , where the data is not available in the iterator, we will an exception  
called "StopIteration"

**example:**

```python
l1=[1,2]
i1=iter(l1)
try:
    print(next(i1))
    print(next(i1))
    print(next(i1))
except StopIteration:
    print("No data is avaliable in the Iterator")
except:
    print("plese check the logic")
```

**2) User-defined exceptions**

in python we can able to create the "user-defined exception"  
these exceptions are created by the programmer or developer, when we  
want to create the user-defined exception, in python we will use a class  
called "Exception"  
in Python "Exception" is a super class for all built-in Exceptions in python

when we want to work with user-defined exceptions in python, we will use  
the following steps:

**step-1:**

create a user-exception as a  class with "class" keyword and this class will  
take "super class" called "Exception"  
in Python, every exception name must ends with "Error"  
user-defined exception class always empty

**step-2:**

when we want to use or raise the "user-defined exception", we will ways  
use a keyword called "raise" keyword  
syntax:

```python
        raise User_defined_exception_name()
```

**working with user-defined exceptions:**

print the given number, if the number is 0 or negative number, we need  
raise an exception called "ZeroOrNgativeError" , otherwise we need to  
print the number as result

**example:**

```python
class ZeroOrNegativeError(Exception):
    pass
try:
  number=int(input("Number:"))
  if number<=0:
      raise ZeroOrNegativeError
except ValueError as e:
    print(e)
except ZeroOrNegativeError:
    print("number never zero or negative!")
else:
    print(number)
```

**handle the exception:**

code:

```python
class ZeroOrNegativeError(Exception):
    pass
def take_number():
    try:
      number=int(input("Number:"))
      if number<=0:
          raise ZeroOrNegativeError
    except ValueError as e:
        print(e)
        take_number()
    except ZeroOrNegativeError:
        print("number never zero or negative!")
        take_number()
    else:
        print(number)
take_number()
```

check given number is prime or not ,write the code using user-defined

**exceptions:**

**code:**

```python
class NumberIsEvenError(Exception):
    pass
def take_number():
    try:
      number=int(input("Number:"))
      if number<=0:number=-number
      if number!=2 and number%2==0:
          raise NumberIsEvenError
    except ValueError as e:
        print(e)
        take_number()
    except NumberIsEvenError :
        print("number is not a prime number")

    else:
        if number==2:
            print("Number is Prime")
        factors=[fact for fact in range(1,number+1)
                 if number%fact==0]
        if factors==[1,number]:
            print("Number is prime number")
        else:
            print("number is a not a Prime number")
take_number()
```

create a list with given size, where the list element must satisfy the following conditions:

1) number must be positive, otherwise we need to raise exception "NumberNegativeError"

2) number must be in the range of "0 to 10000" , otherwise we need to  
raise an exception called "NumberOutOfRangeError"

3) number must be divisible by 3,5,7 only, otherwise we need to raise  
an exception called "NumberDivisibeError"

**code:**

```python
class NumberNegativeError(Exception):
    pass
class NumberOutOfRangeError(Exception):
    pass
class NumberDivisibleError(Exception):
    pass
def create_list():
    global l1,size
    try:
        number=int(input("number:"))
        if number<0:
            raise NumberNegativeError
        elif number%3!=0 and number%5!=0 and number%7!=0:
            raise NumberDivisibleError
        elif number>10000:
            raise NumberOutOfRangeError
    except NumberDivisibleError:
        print("number must divide by 3 or 5 or 7!")
        create_list()
    except NumberOutOfRangeError:
        print("number must be 0 to 10000!")
        create_list()
    except NumberNegativeError:
        print("number always positive!")
        create_list()
    else:
        l1+=[number]
        size-=1
        if size!=0:
              create_list()
        else:
            return
l1=[]
try:
    size=int(input("size:"))
except ValueError:
    print("please give the valid number")
else:
    create_list()
    print(l1)
l1=[]
try:
    size=int(input("Number:"))
except ValueError:
    print("please give the valid number")
else:
    create_list()
```

create a class with following methods:  
1) deposit  
2) withdraw  
3) balance  
4) display\_information  
make all methods as instance methods  
initial amount in the account is "10000"  
per transaction we can able to deposit only maximum only 100000 and  
minimum is 1000  
if we give less than 1000 while deposit, it will give  "InvalidAmountError"  
if we give more than 100000 while deposit, it will give an exception called  
"MaximumDepositError"  
we can able to withdraw minimum 10000 and maximum 50000  
if we withdraw less than 10000, it will give an exception called "InvalidAmountError"  
if we give more than 50000, then we will raise an error called "MaximumWithdrawError"  
if give an amount while deposit or withdraw, any negative number, we  
need to an exception called "NegativeNumberError"

**code:**

```python
class InvalidAmountError(Exception):
    pass
class MaximumDepositError(Exception):
    pass
class MaximumWithdrawError(Exception):
    pass
class NumberNegativeError(Exception):
    pass
class Account:
    def __init__(self,name,branch,account_num):
        self.name=name
        self.branch=branch
        self.account_num=account_num
        self.amount=10000
    def deposit(self,amount):
        try:
            if amount<1000:
                raise InvalidAmountError
            elif amount>100000:
                raise MaximumDepositError
        except InvalidAmountError:
            print("Invalid amount for deposit")
        except MaximumDepositError:
            print("your given deposit amount which more than maximum amount")
        else:
            self.amount+=amount

    def withdraw(self,amount):
        try:
            if amount<10000:
                raise InvalidAmountError
            elif amount>50000:
                raise MaximumWithdrawError
        except InvalidAmountError:
            print("Invalid amount for deposit")
        except MaximumWithdrawError:
            print("your given withdraw amount which more than maximum amount")
        else:
            self.amount-=amount
    def balance(self):
        return self.amount
    def display_information(self):
        print(f"Name:{self.name}")
        print(f"Branch:{self.branch}")
        print(f"Account no:{self.account_num}")
a1=Account("pavan",'sompet','123456')
a1.display_information()
print(a1.balance())
def get_amount():
    try:
        amount=int(input("amount:"))
        if amount<0:
            raise NumberNegativeError
    except NumberNegativeError:
        print("where amount always +ve")
        get_amount()
    else:
        return amount
amount=get_amount()
a1.deposit(amount)
print(a1.balance())
amount=get_amount()
a1.withdraw(amount)
print(a1.balance())
```

---

## Asynchronous Functions

**in python, we will have two types of functions:**

**1) synchronous functions :**

synchronous function is a function and which is executed one and another  
function , it means if any synchronous function is executing, another function will wait until  synchronous function complete it's execution  
synchronous function is also called as "blocked function"

**example:**

```python
import time as t
start=t.perf_counter()
def f1():
    print("this is executing from f1")
    t.sleep(3)
def f2():
    print("this is executing from f2")
    t.sleep(3)
def f3():
    print("this is executing from f3")
    t.sleep(3)
f2()
f3()
f1()
end=t.perf_counter()
print(f"total_time:{end-start}")
```

**2) asynchronous functions:**

when we want to make any function can execute along with another function in python, in python we need to make the function as "Asynchronous"  
when the functions are "Asynchronous", all functions can able to execute  
with another function , it means all functions can execute concurrently.

when we want to work with asynchronous functions in python we will use  
a module called "asyncio"

when we want to work with  "Asynchronous  Functions", in Python we will  
use the following steps:

step-1:  
create the all functions with a keyword called "async"  
any function we define with "async" keyword, then the function is called  
as "asynchronous function"

**step-2:**

once we create the all asynchronous functions, we need to call all  
Asynchronous functions using another function called "main()", this  
function also need to create with "async" keyword  
inside the main() function, we will call all asynchronous functions using a  
function called "gather()", this gather() function is from  "asyncio" module

**step-3:**

once we call the all asynchronous functions using "main()", we need to call  
main() using a function called run(), where the run() function from the  asyncio module

**example:**

```python
import time as t
import asyncio
start=t.perf_counter()
async def f1():
    print("this is executing from f1")
    await asyncio.sleep(3)
async def f2():
    print("this is executing from f2")
    await asyncio.sleep(5)
async def f3():
    print("this is executing from f3")
    await asyncio.sleep(3)
async def main():
    await asyncio.gather(f1(),f2(),f3())
asyncio.run(main())
end=t.perf_counter()
print(f"total_time:{end-start}")
```

**example:**

```python
import time as t
import asyncio
start=t.perf_counter()
async def f1():
    print("this is executing from f1")
async def f2():
    print("this is executing from f2")
    await asyncio.sleep(5)
async def f3():
    print("this is executing from f3")
async def main():
    await asyncio.gather(f1(),f2(),f3())
asyncio.run(main())
end=t.perf_counter()
print(f"total_time:{end-start}")
```

**example:**

```python
import time as t
start=t.perf_counter()
prime1,even1,odd1=[],[],[]
def prime():
    global prime1
    end=int(input("end:"))
    for num in range(1,end):
         for fact in range(2,num):
             if num%fact==0:break
         else:
             if num!=1:prime1+=[num]
def even():
    global even1
    for num in range(1,1000):
         if num%2==0:even1+=[num]
def odd():
    global odd1
    for num in range(1,1000):
         if num%2!=0:odd1+=[num]
prime()
even()
odd()
print(prime1)
print(even1)
print(odd1)
end=t.perf_counter()
print(f"total_time:{end-start}")
```

**example:**

```python
import time as t
import asyncio
start=t.perf_counter()
prime1,even1,odd1=[],[],[]
async def prime():
    await asyncio.sleep(3)
    print("now i called from prime ")
    global prime1
    for num in range(1,1000):
         for fact in range(2,num):
             if num%fact==0:break
         else:
             if num!=1:prime1+=[num]

async def even():
    global even1
    print("from the even")
    for num in range(1,10):
         if num%2==0:even1+=[num]
    print(even1)
async def odd():
    global odd1
    print("from the odd")
    for num in range(1,10):
         if num%2!=0:odd1+=[num]
    print(odd1)
async def main():
    await asyncio.gather(prime(),even(),odd())
asyncio.run(main())
end=t.perf_counter()
print(f"total_time:{end-start}")
```

when we are working with Asynchronous functions, the all asynchronous  
functions will be executed by python using a concept called "Event Loop"

Event Loop is act as execution Engine to all asynchronous functions In  
Python

when the program consists "asynchronous functions" , PVM will automatically create the "Event Loop" for the Asynchronous functions  
execution

Event Loop is able to "process and completes asynchronous functions which are created inside the  python program"

any python program can have exactly one Event Loop, when the program  
executes, if the program consists "Asynchronous functions" then PVM  
will create the Event loop, keep the all Asynchronous functions inside the  
Event loop

**example:**

```python
import asyncio
import nest_asyncio
import time as t
start=t.perf_counter()
nest_asyncio.apply()
"""
this will allow the exisiting
even loop can use by all asynchronous
functions
"""
async def f1():
    print("this is from f1")
async def f2():
    print("this is from f1")
async def f3():
    print("this is from f1")
async def main():
    asyncio.gather(f1(),f2(),f3())
def run():
    loop=asyncio.get_event_loop()
    loop.run_until_complete(main())
run()
end=t.perf_counter()
print(f'total_time:{end-start}')
```

above code for "spyder", to avoid new event loop, use the exisitin  
event loop

**example:**

```python
import asyncio
import nest_asyncio
import time as t
start=t.perf_counter()
flag=False
async def f1():
    print("this is from f1")
async def f2():
    print("this is from f1")
async def f3():
    print("this is from f1")
async def main():
    asyncio.gather(f1(),f2(),f3())
asyncio.run(main())
end=t.perf_counter()
print(f'total_time:{end-start}')
```

when we want to work with following, we will use asynchronous functions:  
when we are working API's calls  
when we are working Database queries  
when we are network operations

---

## Multi-threading

process means "program under execution"

when we run the any program , first the program will move to "RAM",

in computer "RAM" is also called  as "Execution Area", when we run

the any program, the program will move into "RAM" by OS , when it

moves by OS, OS consider as " Process"

whatever the program we open in the computer, are all called as

"Process"

every process will created and managed by OS with help of "PCB"

PCB stands for "process control block"

in computer, all process are will share the different memory space  and

all process will independent with each other

when we want to run with all processes in same time of interval, all

can managed by  "OS" with help of "CPU"

if we are able execute the "multiple programs in the same time of

interval, then is called as multi-programming"

if we are able to execute the "multiple programs using multiple

processors , then we can say it is multi-processing"

again in computer, we can able to divide the entire process into

multiple threads, where each thread will represent  line of execution

and each thread will perform a specified task in the process, all threads

are  related to process, all threads will share the common memory

space

thread is a "light-weight process and which part of some process

and  which will do a specific job and using common memory space"

multi-threading means "executing the multiple threads in the  a given  
interval of time"

in python, we can implement  "multi-threading"  using a module called  
"threading" module

Multi-threading is a process "executing the multiple threads in a same process concurrently"

in python, thread is a object of the class called "Thread" class

in python all threads are objects of  "Thread" class, in python thread can  
made using :

1) as a function

2)  as a method inside the class

in python, every program is itself a thread called  "main thread"

when we are working with multi-threading, we will use the following  
ways:  
\=========================================================1)  create the thread as function using threading module  
2)  create the thread as method by extending "Thread" class from  
threading module  
3) create the thread as method without extending the "Thread" class and using thread module

when we are working with threads in python, we need to know the

**following functions:**

1) start()

2)join()

**1)  create the thread as function using threading module**

**step-1:**

when we want to create the thread as a function , we will use the

threading module

we will import the threading as follows

```python
                           import threading as th
```

**step-2:**

create the all threads as functions

**step-3:**

create the object for each thread using "Thread" class of the

threading module

**step-4:**

we need to start the each thread using "start()" method of the thread

object , when we start the thread, it automatically execute the thread

, when we call the start() method using thread object, internally it

will call "run()" method

when we are executing the multiple threads, but at a time "only one

thread  can be executed, in that time other threads has to wait, until the

thread has complete it's execution, to make other thread has to

execute we will use a method called join()"

**example:**

```python
import threading as th
import time as t
start_time=t.perf_counter()
def thread1():
    for i in range(1,6):
        print("thread-1")
        t.sleep(1)
def thread2():
    for i in range(1,6):
        print("thread-2")
        t.sleep(1)
def thread3():
    for i in range(1,6):
        print("thread-3")
        t.sleep(1)
```

"""create the objects for threads using Thread class"""

```python
"""create the objects for the threads, we are making the thread with
function by giving as target"""

t1=th.Thread(target=thread1)
t2=th.Thread(target=thread2)
t3=th.Thread(target=thread3)
#start and execute the threads
t1.start()
t2.start()
t3.start()
#main thread wait when other all threads are executing
t1.join()
t2.join()
t3.join()
#code for main thread
for i in range(1,6):
    print("Main Thread")
end_time=t.perf_counter()
print(F"total time taken:{end_time-start_time}")
```

create the thread as  "method" inside the a class  extending Thread

**class:**

**step-1:**

when we want to create the thread as a method inside the class , we

will use the threading module

we will import the threading as follows

```python
                           import threading as th
```

**step-2:**

create the all threads as methods using classes, each class must take

threading.Thread as super class or base class

each class is going to have the thread with code as a method

create the thread  as run inside the class which is extending the

Thread class of threading module

**step-3:**

create the object for each thread  class

**step-4:**

we need to start the each thread using "start()" method of the thread

object , when we start the thread, it automatically execute the thread

, when we call the start() method using thread object, internally it

will call "run()" method

when we are executing the multiple threads, but at a time "only one

thread  can be executed, in that time other threads has to wait, until the

thread has complete it's execution, to make other thread has to

execute we will use a method called join()"

when we are "extend" the "Thread" class of "threading" module,

all data and methods of "Thread" class will taken the "class which is

extending the Thread class" , Thread class will have the  "start()"

method, this method will have the calling of "run()" method  ,

that is the reason, we can just need to call the start() method using

"thread" object to execute the thread, no need to call explicitly  any

run()  method, if we call any run() method explicitly python will call the

run() method like a normal method not like a thread

**example:**

```python
import threading as th
import time as t
start_time=t.perf_counter()
class Thread1(th.Thread):
    #create the thread
    pass
class Thread2(th.Thread):
    #create the thread
    pass
class Thread3(th.Thread):
    #create the thread
    pass
#create the objects for all Thread classes
t1=Thread1()
t2=Thread2()
t3=Thread3()

#code for main thread
for i in range(1,6):
    print("Main Thread")
end_time=t.perf_counter()
print(F"total time taken:{end_time-start_time}")
```

**example:**

```python
import threading as th
import time as t
class Thread1(th.Thread):
    #create the thread
    def run(self):
        for i in range(1,6):
            print("This is thread-1")
            t.sleep(1)
class Thread2(th.Thread):
    #create the thread
    def run(self):
        for i in range(1,6):
            print("This is thread-2")
            t.sleep(1)
class Thread3(th.Thread):
    #create the thread
    def run(self):
        for i in range(1,6):
            print("This is thread-3")
            t.sleep(1)
t1=Thread1()
t2=Thread2()
t3=Thread3()
#start the thread
t1.start()
t2.start()
t3.start()
```

**example:**

```python
import threading as th
import time as t
start_time=t.perf_counter()
class Thread1(th.Thread):
    #create the thread
    def run(self):
        for i in range(1,6):
            print("This is thread-1")
            t.sleep(1)
class Thread2(th.Thread):
    #create the thread
    def run(self):
        for i in range(1,6):
            print("This is thread-2")
            t.sleep(1)
class Thread3(th.Thread):
    #create the thread
    def run(self):
        for i in range(1,6):
            print("This is thread-3")
            t.sleep(1)
t1=Thread1()
t2=Thread2()
t3=Thread3()
#start the thread
t1.start()
t2.start()
t3.start()
#notify the main thread execute after all threads excution
t1.join()
t2.join()
t3.join()
end_time=t.perf_counter()
print(f"total:{end_time-start_time}")
```

**example:**

```python
import threading as th
import time as t
start_time=t.perf_counter()
class Thread1(th.Thread):
    #create the thread
    def run(self):
        for i in range(1,6):
            print("This is thread-1")
            t.sleep(1)
class Thread2(th.Thread):
    #create the thread
    def run(self):
        for i in range(1,6):
            print("This is thread-2")
            t.sleep(1)
class Thread3(th.Thread):
    #create the thread
    def run(self):
        for i in range(1,6):
            print("This is thread-3")
            t.sleep(1)
t1=Thread1()
t2=Thread2()
t3=Thread3()
t1.start()
t2.start()
t3.start()
t1.join()
t2.join()
t3.join()

end_time=t.perf_counter()
print(f"total:{end_time-start_time}")
```

**create the Thread as a method without extending the Thread class:**

**step-1:**

```python
import the threading module

import the time module
```

step-2:

create the each thread inside the each class with name "run()"

step-3:

create the object for each class

create the thread object using "thread class", where in the target

using class object , we need to call the "run()" method

**example:**

```python
import threading as th
import time as t
start_time=t.perf_counter()
class Thread1():
    #create the thread
    def run(self):
        for i in range(1,6):
            print("This is thread-1")
            t.sleep(1)
class Thread2():
    #create the thread
    def abc(self):
        for i in range(1,6):
            print("This is thread-2")
            t.sleep(1)
class Thread3():
    #create the thread
    def xyz(self):
        for i in range(1,6):
            print("This is thread-3")
            t.sleep(1)
t11=Thread1()
t22=Thread2()
t33=Thread3()
t1=th.Thread(target=t11.run)
t2=th.Thread(target=t22.abc)
t3=th.Thread(target=t33.xyz)
t1.start()
t2.start()
t3.start()
t1.join()
t2.join()
t3.join()

end_time=t.perf_counter()
print(f"total:{end_time-start_time}")
```

write a python program  create the  given number of  threads

**dynamically  based on the given user "n" value:**

**code**

```python
import threading as th
import time as t
start_time=t.perf_counter()
n=int(input("n:")) # where n value represents "number of threads"
#create the thread
def mythread(num):
    print(f"my thread {num} is execution started!")
    t.sleep(1)
    print(f"my thread {num} is execution completed!")
threads=[]
for i in range(1,n+1):
    thread=th.Thread(target=mythread,args=(i,))
    threads.append(thread)
    thread.start()
print(threads)
#to notify the main thread, execute after executing the all threads
for thread in threads:
    thread.join()

end_time=t.perf_counter()
print(f"total:{end_time-start_time}")
```

**how to get the thread name:**

to get the "thread" name in python, we will use the following syntax:

threading.current\_thread().name

this thread name is given  by "operating system"

**example:**

```python
import threading as th
import time as t
start_time=t.perf_counter()
class Thread1(th.Thread):
    #create the thread
    def run(self):
        #get the thread name
        print(th.current_thread().name)
        for i in range(1,6):
            print("This is thread-1")
            t.sleep(1)
class Thread2(th.Thread):
    #create the thread
    def run(self):
        #get the thread name
        print(th.current_thread().name)
        for i in range(1,6):
            print("This is thread-2")
            t.sleep(1)
class Thread3(th.Thread):
    #create the thread
    #get the thread name
    print(th.current_thread().name)
    def run(self):
        #get the thread name
        print(th.current_thread().name)
        for i in range(1,6):
            print("This is thread-3")
            t.sleep(1)
t1=Thread1()
t2=Thread2()
t3=Thread3()
t1.start()
t2.start()
t3.start()
t1.join()
t2.join()

end_time=t.perf_counter()
print(f"total:{end_time-start_time}")
```

**how to set the thread name by programmer or developer in python:**

to set the thread name by programmer or developer in python, we will

use  following syntax:

threading.current\_thread().name="thread\_name"

**example:**

```python
import threading as th
import time as t
start_time=t.perf_counter()
class Thread1(th.Thread):
    #create the thread
    def run(self):
        #set the name of the thread
        th.current_thread().name="thread-1"
        #get the thread name
        print(th.current_thread().name)
        for i in range(1,6):
            print("This is thread-1")
            t.sleep(1)
class Thread2(th.Thread):
    #create the thread
    def run(self):
        #set the name of the thread
        th.current_thread().name="thread-2"
        #get the thread name
        print(th.current_thread().name)
        for i in range(1,6):
            print("This is thread-2")
            t.sleep(1)
class Thread3(th.Thread):
    #set the name of the thread
    th.current_thread().name="thread-3"
    #create the thread
    #get the thread name
    print(th.current_thread().name)
    def run(self):
        #get the thread name
        print(th.current_thread().name)
        for i in range(1,6):
            print("This is thread-3")
            t.sleep(1)
t1=Thread1()
t2=Thread2()
t3=Thread3()
t1.start()
t2.start()
t3.start()
t1.join()
t2.join()

end_time=t.perf_counter()
print(f"total:{end_time-start_time}")
```

**how many threads are running in the program:**

to get the number of threads are running in the program using

**following syntax:**

```python
                              threading.active_count()

import threading as th
import time as t
start_time=t.perf_counter()
def f1():
    print("this is thread-1")
    t.sleep(2)
    print("thread-1 execution Done!")
def f2():
    print("this is thread-1")
    t.sleep(2)
    print("thread-1 execution Done!")
def f3():
    print("this is thread-1")
    t.sleep(2)
    print("thread-1 execution Done!")
print(f"total threads running:{th.active_count()}")
t1=th.Thread(target=f1)
t2=th.Thread(target=f2)
t3=th.Thread(target=f3)
t1.start()
t2.start()
t3.start()
print(f"total threads running:{th.active_count()}")
t1.join()
t2.join()
t3.join()
print(f"total threads running:{th.active_count()}")
end_time=t.perf_counter()
print(f"total threads running:{th.active_count()}")
```

**in python, threads are two types:**

1)  Daemon Thread  
when we say any thread is "Daemon" thread , the thread will execute  
until the main thread execution complete and these threads  will  
execute in the background . if demon threads killed automatically once  
main thread done it's execution, even daemon thread not done their  
execution

**2)  Non-Daemon Thread**

when we say any thread is "Non-Daemon" thread , the thread will  
executes along with main thread  and  main thread will wait until all  
non-daemon threads  complete their execution and these threads  will  
execute in the foreground.  
in python by default every thread is "Non-Daemon" , in order to check  
the thread is "Daemon or Non-Daemon" we will use the following

syntax:

thread\_object\_name.daemon

the above will return the value in Boolean

if we got "true" as result, then the thread is "Daemon"

if we got "false" as result, then the thread id called "Non-Daemon"

in order to make the thread as "Daemon", we will use the following

syntax:

```python
             thread_object_name.daemon=True
```

this need to be done "before start the thread"

**example:**

```python
import threading as th
import time as t
start_time=t.perf_counter()
def f1():
    print("this is thread-1")
    t.sleep(2)
    print("thread-2 execution Done!")
def f2():
    print("this is thread-2")
    t.sleep(2)
    print("thread-2 execution Done!")
def f3():
    print("this is thread-3")
    t.sleep(2)
    print("thread-3 execution Done!")
t1=th.Thread(target=f1)
t2=th.Thread(target=f2)
t3=th.Thread(target=f3)
#check the thread is daemon or not
t1.daemon=True
t2.daemon=True
t3.daemon=True
print(t1.daemon)
print(t2.daemon)
print(t3.daemon)
t1.start()
t2.start()
t3.start()
```

**example:**

```python
import threading as th
import time as t
start_time=t.perf_counter()
def f1():
    print("this is thread-1")
    t.sleep(2)
    print("thread-2 execution Done!")
def f2():
    print("this is thread-2")
    t.sleep(2)
    print("thread-2 execution Done!")
def f3():
    print("this is thread-3")
    t.sleep(2)
    print("thread-3 execution Done!")
t1=th.Thread(target=f1)
t2=th.Thread(target=f2)
t3=th.Thread(target=f3)
#check the thread is daemon or not
t1.daemon=True
t2.daemon=True
t3.daemon=True
t1.start()
t2.start()
t3.start()
print(t1.daemon)
print(t2.daemon)
print(t3.daemon)
```

**example:**

```python
import threading as th
import time as t
def f1():
    while True:
        print("Daemon thread started")
        t.sleep(0.1)
t1=th.Thread(target=f1)
t1.daemon=True
t1.start()
print("main thread is started it's execution")
t.sleep(5)
print("main thread is done it's execution")
```

**example:**

```python
import threading as th
import time as t
data=1
def f1():
    global data
    for _ in range(1,10000):#9999
        data+=1
t1=th.Thread(target=f1)
t2=th.Thread(target=f1)
t1.start()
t2.start()
t1.join()
t2.join()
print(data)
```

while working with Threading, we will need to know the concept  
called "Mutex"  
Mutex is also called as  "Lock"  
when multiple threads are running under the "critical section", they  
may share the common data , but in python we will have default  
locking mechanism  called "GIL"

GIL is also called as "Global Interpreter lock", which makes  python  
can able to execute only one thread at a time , when thread is  
executing an it's data is automatically locked, no other can not able  
to access it, until thread done it's execution

when we want to implement the any locking mechanism in python,  
we will use a class called "Lock" from the "threading" module  
Lock class is used  "to give the lock for any resource".

in multi-threading multiple threads are executing and they share the  
common data, in this there may be chance of "data manipulation"

when multiple threads can try to change the data, but in python  
by default we will have a  "lock" called "GIL".

**in the Lock class, we will have the following methods:**

1)  acquire()  
when we call this function , this will apply the "lock on resource"

2)  release()  
when we can use this function , this will release the lock on the  
resource

when we give the "lock" to the resource using "acquire()", the resource  
will get lock, any other need to access the lock again, the thread need  
to release the lock , when we use acquire() method, we also need to  
write "release()" for it, otherwise threads or in the waiting state, to  
avoid this we will give and take lock on the resource using "with"  
keyword

when we give the  lock using "With", the lock automatically give for  
resource after executing the code of the  with, it automatically  release  
the lock, we no need to use the "acquire() and release()"  
syntax:

```python
with lock_object_name:
 #write the code
```

it automatically releases  lock

when we give the "lock.acquire(blocking=True)", other thread has to  
wait until the thread has to until release the lock

when we give the "lock.acquire(blocking=False)", other thread never  
has to  wait until the thread has to until release the lock

Dead Lock  means "two or more threads waiting forever , no threads  
is never to finish the execution"

Dead lock makes the "thread to wait for longer time, even time is  
does not know "

this dead lock can be handled using "locking mechanism"

even locking also can not avoid the dead lock directly , we need apply  
some mechanism with locking called  "timeout"

when we are working with "locks", there may chance getting "dead  
lock due to waiting ", for this when we give the any lock on the  
resource we will give the "timeout", to make the lock free after the  
timeout , with threads can not able to  wait forever, dead lock problem  
will be  resolved

when we are using "timeout" , the lock must be  "blocked" , otherwise  
for non-blocking , we can not able to  apply the waiting, python we will  
give exceptions for non-blocking locks

**example:**

```python
import threading  as th
import time as t
#resource (data)
x=1
#create the object for Lock class
lock1=th.Lock()
lock2=th.Lock()
#create the thread
def mythread():
    print("my thread1 is starts it's execution!")
    t.sleep(2)
    print("mythread1 is looking for lock!")
    lock1.acquire()
    print("mythread1 gets lock 1!")
    print("mythread1 is looking for lock2!")
    lock2.acquire()
    print("mythread1 is waiting")
def mythread2():
        print("my thread2 is starts it's execution!")
        t.sleep(2)
        print("mythread2 is looking for lock2!")
        lock2.acquire()
        print("mythread gets lock2!")
        print("mythread2 is looking for lock1!")
        lock1.acquire()
        print("mythread2 is waiting")
t1=th.Thread(target=mythread)
t2=th.Thread(target=mythread2)
t1.start()
t2.start()
t1.join()
t2.join()
print("Done!")
```

**example:**

```python
import threading  as th
import time as t
#resource (data)
x=1
#create the object for Lock class
lock1=th.Lock()
lock2=th.Lock()
#create the thread
def mythread():
    print("my thread1 is starts it's execution!")
    t.sleep(2)
    print("mythread1 is looking for lock!")
    lock1.acquire(timeout=3)
    print("mythread1 gets lock 1!")
    print("mythread1 is looking for lock2!")
    lock2.acquire(timeout=3)
    print("mythread1 is waiting")
def mythread2():
        print("my thread2 is starts it's execution!")
        t.sleep(2)
        print("mythread2 is looking for lock2!")
        lock2.acquire(timeout=3)
        print("mythread gets lock2!")
        print("mythread2 is looking for lock1!")
        lock1.acquire(timeout=3)
        print("mythread2 is waiting")
t1=th.Thread(target=mythread)
t2=th.Thread(target=mythread2)
t1.start()
t2.start()
t1.join()
t2.join()
print("Done!")
```

**example:**

```python
import threading  as th
import time as t
#resource (data)
x=1
#create the object for Lock class
lock1=th.Lock()
lock2=th.Lock()
#create the thread
def mythread():
    print("my thread1 is starts it's execution!")
    t.sleep(2)
    print("mythread1 is looking for lock!")
    lock1.acquire(blocking=False,timeout=3)
    print("mythread1 gets lock 1!")
    print("mythread1 is looking for lock2!")
    lock2.acquire(blocking=False,timeout=3)
    print("mythread1 is waiting")
def mythread2():
        print("my thread2 is starts it's execution!")
        t.sleep(2)
        print("mythread2 is looking for lock2!")
        lock2.acquire(blocking=False,timeout=3)
        print("mythread gets lock2!")
        print("mythread2 is looking for lock1!")
        lock1.acquire(blocking=False,timeout=3)
        print("mythread2 is waiting")
t1=th.Thread(target=mythread)
t2=th.Thread(target=mythread2)
t1.start()
t2.start()
t1.join()
t2.join()
print("Done!")
```

**example:**

```python
import threading as th
import time as t
data=1
def f1():
    global data
    print("starting:",data)
    for _ in range(1,10000):#9999
        data+=1
    print("after:",data)
t1=th.Thread(target=f1)
t2=th.Thread(target=f1)
t1.start()
t2.start()
t1.join()
t2.join()
```

**example:**

```python
import threading  as th
#resource (data)
x=1
#create the object for Lock class
lock=th.Lock()
#create the thread
def mythread():
    #resource x
    global x
    for _ in range(1,10000):
        lock.acquire() #make the lock on x
        x+=1
        lock.release() #release the lock on x
#create the object for thread using Thread class
t1=th.Thread(target=mythread)
t2=th.Thread(target=mythread)
t1.start()
t2.start()
print(x)
```

**example:**

```python
 import threading  as th
#resource (data)
x=1
#create the object for Lock class
lock=th.Lock()
#create the thread
def mythread():
    #resource x
    global x
    for _ in range(1,10000):
       with lock:# here lock.acquire() is called
           x+=1#after this lock.release() is called
#create the object for thread using Thread class
t1=th.Thread(target=mythread)
t2=th.Thread(target=mythread)
t1.start()
t2.start()
print(x)
```

**example:**

```python
import threading  as th
#resource (data)
x=1
#create the object for Lock class
lock=th.Lock()
#create the thread
def mythread():
    #resource x
    global x
    for _ in range(1,10000):
        lock.acquire(blocking=False) #make the lock on x
        x+=1
        lock.release()

#create the object for thread using Thread class
t1=th.Thread(target=mythread)
t2=th.Thread(target=mythread)
t1.start()
t2.start()
print(x)
```

---

## Relational Databases

Database is used to work with "store the all application users data"  
based on the how we can store the data inside the database, the databases are classified into two types:

**1) relational database :**

in this database, the data always store in the form tables, then the database is called as "relational database"  
where the table can have data the in the form "rows and columns"  
rows are also called as "records or tuples"  
columns are also called as "fields or attributes"

**2)non-relational database**

any database store the data not in the form  of the "Table", then the  
database is called as "Non-relational" database

when we want to store the any data in the relational database and when  
want to perform any operation on the relational database, then we will  
use a language called "SQL"

when we want to use any sql , the sql code can be processed a software  
called "DBMS"

SQL ====\> DBMS ===\> it will performs the operation Database

whenever we want to work with Relational database, we will always need  
to use the following :  
1) SQL as a language  
2) DBMS as a software and which is used to process the SQL  
code  
the DBMS which uses to "run the operations on the Database", then Database is called as "RDBMS"  
example :  
MySQL  
Oracle  
Sql Server  
Postgres SQL ............

---

## Working with MySQL

**SQL will have the following sub languages:**

1) DDL (create, alter, drop, rename, truncate)  
2) DML (Insert, Update, Delete)  
3) DQL (Select)  
4) TCL (Savepoint, rollback, commit)  
5) DCL(grant, revoke)

with help of create command  
we can able to create the "Database, table, view, index, stored  
procedure, function , trigger......"

with help of Drop command  
we can able to drop the "Database, table, view, index, stored  
procedure, function , trigger......"

with help of truncate command  
we can able to  "Remove the all rows of the table, after this, table  
become empty"

with help of the rename, we can able to rename the "Table" in the Database

**with help of  the alter command , we can able to do the following:**

1) we can able to add the new columns in the exiting tables  
2) we can able to modify the column data type in the existing tables  
3) we can able to change the name of the columns of the existing table  
4) we can able to rename the existing table  
5) we can able to remove the any column from the existing table

when we perform alter, truncate, drop, create operation in the database,  
those operations never be "rollback"

with help of the insert command, we can insert one or more rows into  the  
table

with help of update command , we can update the one or more rows in the  
table , when are performing update operation, we always need to give condition, otherwise all rows in the table will be update  
update with condition ===\> only specific rows of the table will be updated based on the condition  
update without condition ===\> all rows of the table will be updated

with help of delete command , we can delete the one or more rows from  
the table  
delete with condition ===\> only specific rows of the table will be deleted based on the condition  
delete without condition ===\> all rows of the table will be deleted  
truncate and delete without condition are the same

insert, delete, update operations can be "rollback" , when we run the  
these queries in the Transaction mode

with help of select command, we can able to retrieve the data from the  
database table  
using this command,  
we can retrieve all rows from the table  
we can retrieve the rows from the table based on the condition  
we can retrieve the specific number of rows from the table

with help of savepoint, we can create execute n number of sql queires  
under one name , with help of this all we can able to commit at once and  
with help of this all we can able to rollback

with help of commit, we can able to save the sql operation permanently on  
the Database

with help of rollback, we can able to undo the SQL operation, what we  
done previously

**how to create the database in the MySQL:**

syntax:

```sql
           create database datbase_name;
example:
create database  employee_fp7_2026;
create database student_fp7_2026;
create database hr_fp7_2026;
```

**how to show the all available databases in the MySQL:**

syntax:  
show databases

**how to use any database, to create or work with any table in Mysql:**

syntax:

```sql
                     use database_name;
example:
             use employee_fp7_2026;
```

**how to check the current database in the MySQL:**

syntax:  
select database()

**example:**

```sql
create database employee_fp7_2026;
show databases;
select database();
use employee_fp7_2026;
select * from employee;
```

---

## Tables and Constraints

syntax:  
create table table\_name(col1 type constraint check default,  
col2 type constraint check default,  
col3 type constraint check default,...........................................)  
while defining the columns,  
type is always we have give  
constraint or check or default is optional

**in MySQL, we will have Data types:**

```python
for numerical type:
      integer: int, bigint
      float type:
                  for precision:
                               float
                               double
                 for fixed point decimal:
                            numeric, decimal
for character type:
                      char or varchar
for date  type:
                             date
for  both date and time:
               datetime
for year:
```

year  
for storing one value among the multiple values:  
Enum  
for storing the multiple values under one name:  
set

```python
for binary information (like image, any other):
                        blob
for multi-line text:
```

text

working with constraints:

**in MySQL, we will two types of constraints:**

1) integrity constraints:  
1) not null  
2)unique  
3) primary key  
4) check  
5) default  
2) referential integrity constraints  
1) foreign key

not null:  
which is used to avoid the null values in the table column  
this constraint will be used for  more than one column or in the table,  
we can this constraint for one or more columns  
unique:  
which is used to avoid the duplicate values in the table column  
this constraint will be used for  more than one column or in the table,  
we can this constraint for one or more columns

**primary key:**

which is used to  avoid the both null values and duplicates values in the  
column of the table  
in a table, only one column can act like "primary key"  
when we want to make the more than one column act like primary key we  
can able to define the columns with "both unique and not null" constraint

NULL                        Duplicate  
not null                             not allow                    allow  
unique                               allow                         not allow  
primary key                     not allow                    not allow  
not null + Unique           not allow                     not allow

**Composite Primary key:**

in MySQL, we can able to create the two or more columns with primary  
key, when the primary is acting two or more columns, then the primary key is  
called as "composite primary key"

**example:**

```sql
drop table sample;
```

create table sample(id int,cid int,  
primary key(id,cid));

```sql
insert into sample values(100,112);
insert into sample values(100,113);
insert into sample values(101,112);
insert into sample values(100,114);
select * from sample;
```

**Composite Unique key:**

in MySQL, we can able to create the two or more columns with unique  
key, when the unique key is acting two or more columns, then the unique key is called as "composite unique key"

**example:**

```sql
drop table sample;
```

create table sample(id int,cid int,  
unique key(id,cid));

```sql
insert into sample values(100,112);
insert into sample values(100,113);
insert into sample values(101,112);
insert into sample values(100,null);
select * from sample;
```

**auto\_increment:**

when we apply the auto\_increment to the column, the column will  
always takes the new value in the column as "previous\_value+1"

when we apply the "auto\_increment" to the column, the column will  
must define with the key, it means the column must define with "unique  
or primary key"

when we define the "auto\_increment" for the column which is having  
"unique" as constraint, then the column allow the "NULL"

when we define the column with "auto\_increment" , the default value  
of the auto\_increment is "1", we can reset this value using "alter"

**example:**

```sql
use employee_fp7_2026;
```

create table sample(id int unique  
auto\_increment);

```sql
insert into sample values(null);

select * from sample;

truncate table sample;
```

create table sample2(id int primary key  
auto\_increment);

```sql
insert into sample2 values(null);
select * from sample2;
```

**example:**

-- change the auto\_increment column

```sql
alter table sample auto_increment=100000;
insert into sample values();
select * from sample;
```

**check constraint:**

check constraint is used to "validate the given data for the column" as per the condition, if the given value not as per the condition, it will give an error  
check constraint will never bother about "null or duplicate" values

**example:**

create table sample(age int not null  
check(age\>=0 and age\<=100));

```sql
insert into sample values(10);
insert into sample values(100);
select * from sample;
insert into sample values(-10);
insert into sample values(1000);
```

**default constraint:**

while inserting the data into the column, if we want to avoid the null values and we want to some default data instead of null value, then we  
define the some default to the column while creating the table using  
a constraint called "default"

**example:**

```sql
drop table sample;
create table sample(id int default 1000);
insert into sample values(1);
insert into sample values(2);
insert into sample values(3);
insert into sample values();
select * from sample;
```

**create the table with name "employee":**

**employee table:**

create table employee(  
id int primary key,  
firstname varchar(100) not null,  
lastname varchar(100) not null,  
email varchar(200) not null unique,  
deptid int not null,  
deptname varchar(100) not null,  
location varchar(100) not null,  
zipcode int not null,  
mobileno bigint not null unique,  
dob date not null,  
joining\_date date not null,  
gender varchar(10) not null,  
blood\_group varchar(10) not null,  
salary float not null)

when we want to insert the data into table, we will use a "insert" command  
syntax:  
insert into table\_name(col1,col2,col3,col4,.....coln)

```python
values(val1,val2,val3,val4,.....valn)
```

or  
insert into table\_name values(val1,val2,val3,val4,..........)

**example:**

insert into employee  
values(100,'kiran','A','kiran@gmail.com',  
1000,'development','hyderabad',500047,  
9876543210,'1992-3-3','2015-3-17',  
'male','B+ve',15000);

or

insert into employee  
values(101,'kumar','D','kumar@gmail.com',  
1000,'development','hyderabad',500047,  
876543210,'1990-3-3','2014-11-17',  
'male','A+ve',25000),  
(102,'rajat','P','rajat@gmail.com',  
1001,'Testing','chennai',500123,  
7876543210,'1996-3-3','2020-12-29',  
'male','B+ve',35000);

```sql
select * from employee;
```

when we want to retrieve the data from the MySQL table, we will use  
a command called "select"

syntax:  
select \* from table\_name; \<== get the all rows from the table

when we want to get the specific rows from the table , we will use  
following syntax with select :

```sql
select col1, col2,col3,col4,........coln from table_name;
```

**example:**

```sql
select * from employee;
```

select id,firstname,lastname from  
employee;

when we are retrieving the data from the MySQL table using "select", we  
can give the alias name for the columns using  "as"  
syntax:  
select col1 as column\_name,col2 as column\_name,................  
coln as column\_name from table\_name

**example:**

select id as "employee id" from  
employee;  
select id as "employee id",firstname as  
employee\_first\_name from employee;

when we want to update the any column value, in MySQL we will use a  
clause called "update"  
syntax:  
update table\_name set col1=value,col2=value,col3=value,............

```python
coln=value where condition;
```

when we want to delete the any row from the MySQL table, we will use  
a command called "delete"  
syntax:

```sql
delete from table_name where condition;
```

---

## SQL Clauses

**in MySQL we will have the following clauses:**

**1.where:**

using this we can able to give the condition for any query, for filtering  
the data based on the condition while retrieving the data from the MySQL  
table  
syntax:

```sql
select * from table_name where condition;
```

or  
select col1,col2,col3,....coln from table\_name where  
condition;

**when we are using this query, we will use the following operators:**

relational operators: \>,\<,\>=,\<=,=,!=/\<\>  
arithmetic operators: +,-,\*,/,%

**example:**

**get the employee details whose salary is more than 100000**

select \* from employee  
where  
salary\>100000;  
select id,firstname,salary from  
employee where salary\>100000;

**get the employee details whose salary is less than 100000:**

select \* from employee  
where  
salary\<100000;

**get the employee details whose salary is not equal to 100000:**

select \* from employee  
where  
salary\<\>100000;  
select \* from employee  
where  
salary!=100000;

**get the employee details whose location is equal to "Hyderabad":**

select \* from employee  
where location='hyderabad';

**update the salary of all employees in the employee by adding 10000:**

**code:**

```sql
select * from employee;
```

update employee set

```python
salary=salary+10000;
```

update the employee salaries of employees, only who are working in

**hyderabad location, salary will be added by 10000:**

update employee set salary=salary+10000  
where

```python
location='hyderabad';
```

**2.order by**

when we want to sort the data while retrieving data from the table, in MySQL  we will use a clause called "order by"

**order by will sort the data in following ways:**

1)asc (ascending order)  
2)desc (descending order)

order by always sort the data by default in "Ascending order"  
in order to mention the sorting order to the order by clause we will use  
"asc" or "desc"  
order by column\_name asc or order by column\_name;  
order by column\_name desc;

**sort the salary column in the ascending order:**

select salary from  
employee  
order by salary;  
select salary from employee  
order by salary desc;

while using order by clause, we can also can use "numbering"  
the numbering can be order of columns in the table or the numbering  
can order of the columns in the "Select" query

**example:**

select salary from employee  
order by 1  desc;  
select id,firstname,salary from  
employee order by 3 desc;  
select id,firstname,salary from  
employee order by 2 desc;  
select id,firstname,salary from  
employee order by 1  desc;  
select \* from employee order by 15 desc;

when the select query is having both "where and order by clause", then  
order always as follows  
where  (1)  order by (2)  
select col1,col2,col3,.........coln from table\_name  
where condition  
order by column\_name asc \|desc;

**example:**

select id,firstname,lastname,salary

```python
from employee
```

where  
salary\>=100000  
order by salary desc;

**3.limit**

using this clause, we can able to get the specific numbers of rows in the  
result  
syntax:  
limit row\_number,number\_of\_rows\_need\_to\_be\_print;

in MySQL, row number always starts with "0"

example:  
limit 5; \<=== total limit has to print 5 rows  
limit 10;\<=== total limit has to print 10 rows  
limit 2,20; \<=== from the row number 2, we need to print 20 rows  
limit 5,6 \<== from the row number 5, we need to print 6 rows

**example:**

select id,firstname,salary from  
employee limit 5;  
select id,firstname,salary from  
employee limit 1,3;  
select id,firstname,salary from  
employee limit 3,2;  
select id,firstname,salary from  
employee limit 10;

when we are using limit query along with "where and order by clause", we

**will always keep in the following order:**

limit with where:  
where (1) limit(2)  
limit with order by:  
order by (1) limit(2)

**limit with where + order by:**

where(1)  order by (2)  limit(3)

select col1, col2,col3,col4,.........coln from table\_name  
where cond  
order column\_name asc\|desc  
limit num1,num2;

query execution order:

```python
from(1) ===>  where (2) ===> order by(3) ===>select (4) ===> limit(5)
```

**example:**

select id,firstname,salary from  
employee  
where salary\>=200000  
order by salary desc  
limit 5;

**get the employee maximum salary:**

select salary from employee order by salary desc limit 1;

**get the employee 4th maximum salary:**

select salary from employee order by salary desc limit 3,1;

**4.distinct**

using this clause, we can able to get the unique values of the column or  
using this clause, we can able to get the unique rows of the columns from  
the table

when we give this clause to column, it will always return only unique  
values of the column  
syntax:

```sql
select distinct col_name from the table_name;
```

**example:**

```sql
select location from employee;
select distinct location from employee;
```

when we give the this clause for multiple columns it will return the data

```python
from the table, unique row wise
```

syntax:  
select distict col1, col2, col3,.......coln from table\_name;

**example:**

select location,salary from employee  
order by salary desc;  
select distinct location,salary from employee  
order by salary desc;

---

## Aggregate Functions, Group By and Having

1.count()  
this function will give the number of rows in the column or  
number of rows in the tables  
2.sum()  
this function will give the sum of the values of the given column  
3.max()  
this function will give the maximum value of the given column  
4.min()  
this function will give the minimum value of the given column  
5.avg()  
this function will give the average value of the given column values

**example:**

```sql
select count(salary) from employee;
```

-- total rows of the table

```sql
select count(*) from employee;
select sum(salary) from employee;
select max(salary) from employee;
select min(salary) from employee;
select avg(salary) from employee;
```

**example:**

create table sample11(id int,salary float,  
deptid int);

```sql
insert into sample11 values();
select * from sample11;
insert into sample11 values(2,20000,100);
select * from sample11;
select count(salary) from sample11;
select count(*) from sample11;
select sum(salary) from sample11;
select max(salary) from sample11;
select min(salary) from sample11;
select avg(salary) from sample11;
```

when we apply the  aggregate functions on the columns, it will always  
return any value only  which are related to "non-null" values

**5.group by:**

this clause is used to group the data based on the given category  
when we are using this clause, we always combine the this clause using  
aggregate functions  
syntax:  
select group\_column\_name, count(\*)\|sum() \|avg()\|max()\|min()

```python
from
```

table\_name  
group by column\_name

when we are using group by clause, we can give to group by clause  
with column name or  column number  in the query or column number  
in the table

**example:**

select deptid,count(\*) as "employee count"

```python
from employee
```

group by 1  order by 2;

we can group the columns data from the table using group by with  
multiple columns

**example:**

select deptid,location,count(\*) as "employee count"

```python
from employee
```

group by 1,2 order by 1;

select count(\*) from employee  
where location='chennai' and deptid=124;  
select deptid,location,count(\*) as "employee count"

```python
from employee
```

group by deptid,location order by 2;

**example:**

select deptid,count(\*)

```python
from employee
```

group by deptid order by 2;  
select count(\*) from employee  
where deptid=123;

**6.having clause:**

using this clause we can filter the group by clause result or when we want  
write the any condition for group by result , then the condition we can  
give using "having clause"

**example:**

select deptid,location,count(\*) as emp\_count

```python
from employee
```

group by 1,2  
having emp\_count\>=10;

select deptid,location,count(\*) as emp\_count

```python
from employee
```

group by 1,2  
having emp\_count\<=10;

select deptid,location,count(\*) as emp\_count

```python
from employee
```

group by 1,2  
having emp\_count\>=10;

select count(\*) as emp\_count from employee  
where location='chennai' and deptid=124;

**where vs having:**

when we use the both where and having clauses in the query,  
first where clause will be executed , the result of where will taken by  
group by , group by performs operation on where clause result, return  the  
row as per condition given with having (which are matched)

when we give the query with clauses called "from, where, group by,  
having, order by , limit"

```python
from (1) ===> where(2) ==> group by (3) ==> having (4) ===> order by(5) ===> limit (6)
```

**code:**

select deptid,location,count(\*) as emp\_count

```python
from employee
```

where salary\>=100000  
group by 1,2  
having emp\_count\>=10  
order by emp\_count desc  
limit 5;

---

## MySQL Operators (Logical, IN, BETWEEN, LIKE)

**in MySQL, we will have the following logical operators:**

1) or  
2) and  
3) not

**example:**

select id,firstname,lastname,salary,location from  
employee  
where  
salary\>=200000 or location='hyderabad';

select id,firstname,lastname,salary,location from  
employee  
where  
salary\>=200000 and location='hyderabad';

select id,firstname,lastname,salary,location from  
employee  
where not salary\>=200000 or not location='hyderabad';

select id,firstname,lastname,salary,location from  
employee  
where salary\<=200000 and location!='hyderabad';

**working with in operator:**

using this operator, we can able to get the data related to  multiple values

**in can used  for following ways:**

1) in  (it used to get the data  for  given values)  
2) not  in (it is used to get the data for  not given values)

**example:**

select id,firstname,lastname,salary,location from  
employee  
where location  
in ('hyderabad','chennai','delhi') order  
by location;  
select id,firstname,lastname,salary,location from  
employee  
where location='hyderabad' or location='chennai'  
or location='delhi'  
order by location;

**example:**

select id,firstname,lastname,salary,location from  
employee  
where location  
not in ('hyderabad','chennai','delhi') order  
by location;  
select id,firstname,lastname,salary,location from  
employee  
where not location='hyderabad' or not location='chennai'  
or not location='delhi'  
order by location;

**working with between Operator:**

when we want to get the data from the table for specific range, in MySQL  
we will use "Between" operator

**between can be used in MySQL in the following ways:**

1) between  
between looks  for "with in the given range, where both start and  
end values" are inclusive  
2) not between  
not between looks  for "not  with in the given range, where both start  
and end values" are inclusive

**example:**

select id,salary from employee  
where  
salary between 80000 and 148000;

select id,salary from employee  
where  
salary \>=80000 and salary\<=148000;

select id,salary from employee  
where  
salary not between 80000 and 148000 order by 2;

select id,salary from employee  
where  
salary \<=80000 or salary\>=148000 order by 2;

**working with  like operator:**

like operator is used for "pattern matching"  
when we are working with like operator, we will use the following  
characters, those are also called  as "wildcard- characters"

those are:  
1)\_  ===\> exactly  one character  
2)%  ===\> zero or more characters

**example:**

a%  (starts with a)===\> a, aa, abcd,abcdef,.....................  
%a (ends with a) ===\> a, ba, cba, dcba,..................  
a%a(starts with a and ends with a) ===\> aa, aba, abba,...................  
%a%(contains a)  ===\> a, aa, ba, bcdade  
a\_ ===\> ab, ac, aa,  
\_a ===\> ba,ca,da, ea,..........................................

**example:**

select id,firstname from employee  
where firstname like 'a%' limit 5;

select id,firstname from employee  
where firstname like '%a' limit 5;

select id,firstname from employee  
where firstname like 'a%a' limit 5;

select id,firstname from employee  
where firstname like '%a%' limit 5;

select id,firstname from employee  
where firstname like '\_' limit 5;

select id,firstname from employee  
where firstname like 'a\_\_\_' limit 5;

select id,firstname from employee  
where firstname like '\_\_\_\_\_' limit 5;

select id,firstname from employee  
where firstname like '\_\_\_\_a' limit 5;

select id,firstname,salary from employee  
where salary like '%89%' limit 5;

select id,firstname,salary from employee  
where salary like '%89%' limit 5;

select id,firstname,salary from employee  
where salary like '%16%' limit 5;

how to create the duplicate table and how to copy the data of one into

**another:**

when we want to create the duplicate table like another table, in MySQL  
we will use the following ways:  
1)like  
when we create the duplicate table using "like", it will just the create  
duplicate table with structure, data will not copied, later we will copy the  
data using "select"  
2)select  
when we create the duplicate table using "select", it will create the  
table with both structure and data

**example:**

```sql
create table employee7 like employee;
desc employee;
desc employee7;
select * from employee;
select * from employee7;
```

insert into employee7 select \* from employee;

**example:**

create table employee77 select \* from employee;

```sql
desc employee;
desc employee77;
select * from employee77;
```

create a table with name sample123 with columns  id,firstname,lastname,email,salary,location from the  
employee table , where salary\>=150000 and employees from the  
Hyderabad, Chennai, bangalore, delhi locations  
code:  
create table sample123  
select id,firstname,lastname,email,salary,  
location from  
employee  
where salary\>=150000 and location  
in ('hyderabad','chennai','bangalore','delhi');

```sql
select * from sample123;
```

**how to create the temporary tables:**

when we create  a table which need to be present until we close the  
MySQL session , for this we need to create the table using a keyword  
called "temporary" along with create  command  
these tables are also called as "session tables"

**syntax:**

create temporary table table\_name(col1 type constraint..................)

**example:**

create temporary table sample124 select \* from employee limit 10;

```sql
select * from sample124;
```

---

## Alter Command

**1.adding the new columns into the table using alter command:**

syntax:  
alter table table\_name add column1\_name type constraint,  
add column2\_name type constraint,........................  
add columnn\_name type constraint;

when we are working with "alter"  for adding new column, the new column  
always add at end of the table

when we want to add the new column into the table using  at particular  
position in the table, we will use the following keywords to tell alter  
command where to add the new column , those are :  
1) first  ===\> this will always add the new column at starting of the table  
2) after  ====\> this will always add the new column at particular position  
of the table

**example:**

```sql
create table sample124(id int);

desc sample124;
```

alter table sample124 add firstname varchar(100),  
add lastname varchar(100);

```sql
desc sample124;
```

alter table sample124

add sno int primary key auto\_increment  
first;

alter table sample124  
add midname varchar(100) after firstname;

**changing the data type of the columns using alter command:**

when we want to change the data type of the column, we will use keyword  
with alter command called "modify"

**syntax:**

alter table table\_name modify col1 datatype constraint, modify col2 datatype constraint,............................................................................

**example:**

```sql
desc sample124;
```

alter table sample124 modify firstname  
varchar(200) not null;  
alter table sample124 modify lastname

```python
varchar(200) not null,modify midname varchar(50)
```

not null;  
alter table sample124 modify  
id int not null unique key;

**when we remove the any column from the table using alter:**

when we want to remove the any column the from table using alter, we  
can remove using  a flag called "drop"  
syntax:  
alter table table\_name drop column1\_name, drop column1\_name,...........

**example:**

```sql
desc  sample123;
alter table sample123 drop id;
alter table sample123 drop location,drop lastname;
```

**when we want to change the name of the column in the table using alter:**

when we want to change the name of the column in the table using alter,  
with alter will use a flag called "change column"  
syntax:  
alter table table\_name change column original column new column\_name  
datatype constraint,.........................................................

**example:**

```sql
desc  sample123;
```

alter table sample123 change column  
email emp\_email varchar(100);  
alter table sample123 change column  
firstname name varchar(100),change column  
emp\_email email varchar(100);

we can also can change the name of the table using alter with following  
syntax:

```sql
alter table table_name rename to new_table_name;
```

**example:**

```sql
desc sample123;
alter table sample123 rename to  sample1234;
desc sample1234;
```

alter + add \<=== add the new column into table  
alter + drop \<=== remove the column from the table  
alter +modify \<== change the data type of the column in the table  
alter + change column \<== rename of the column of the table  
alter+ rename \<=== rename the table into new name

**example:**

```sql
desc sample1234;
truncate table sample1234;
```

alter table sample1234 add id int,  
add mobileno int,  
drop email, modify salary double,  
change column name firstname varchar(100);  
alter table sample1234 change column mobileno mobile  
bigint not null unique;  
alter table sample1234 modify id int primary key;

```sql
alter table sample1234 drop id;
```

alter table sample1234 add id int primary key;

---

## MySQL with Python

when we want to work with python and MySQL , in python we will use  
a module called "mysql-connector-python"

in order to install, mysql-connector-python, we will use the following  
syntax:  
pip install mysql-connector-python

when we want to work with MySQL and python, we will use the  
following steps:  
step-1:  
import the mysql connector module  
code:

```python
                       import mysql.connector as mysql
step-2:
         create the connection in between mysql and python
                con=mysql.connect(host="",user="",password="")
      when we are working with any table or when we want to create the
      any table, we need to mention the following:
          con=mysql.connect(host="",user="",password="",database="")
step-3:
      create the cursor, to execute the any sql query using connection object
      syntax:
                               cur=con.cursor()
step-4:
        execute the any sql query using "execute()" function with cursor
        object name
       syntax:
                              cur.execute("write the query here")
```

**example:**

```python
              import mysql.connector as mysql
#create the connection
con=mysql.connect(host="localhost",
                  user="root",
                  password="123456789",
                  database="employee_fp7_2026")
#create the cursor
cur=con.cursor()
#execute the sql query
cur.execute("show tables")
#show result
print(list(cur))
#close the cursor
cur.close()
#close the connection
con.close()
```

**example:**

```python
#import the mysql connector
import mysql.connector as mysql
#create the connection
con=mysql.connect(host="localhost",
                  user="root",
                  password="123456789")
#create the cursor using con object
cur=con.cursor()
#execute the sql query using cursor
cur.execute("show databases")
#show the databases
print(list(cur))
#close the cursor()
cur.close()
#close the connection
con.close()
```

**example-2:**

```python
#import the mysql connector
import mysql.connector as mysql
#create the connection
con=mysql.connect(host="localhost",
                  user="root",
                  password="123456789")
#create the cursor using con object
cur=con.cursor()
#execute the sql query using cursor
cur.execute("create database sample_fp7_2026")
cur.execute("show databases")
#show the databases
print(list(cur))
#close the cursor()
cur.close()
#close the connection
con.close()
```

**example:**

```python
#import the mysql connector
import mysql.connector as mysql
#create the connection
con=mysql.connect(host="localhost",
                  user="root",
                  password="123456789",
                  database="sample_fp7_2026")
#create the cursor using con object
cur=con.cursor()
#execute the sql query using cursor
```

cur.execute('''create table sample(id int primary key,  
name varchar(100),email varchar(100),  
salary float)''')

```python
cur.execute("show tables")
#show the databases
print(list(cur))
#close the cursor()
cur.close()
#close the connection
con.close()
```

**example:**

```python
#import the mysql connector
import mysql.connector as mysql
#create the connection
con=mysql.connect(host="localhost",
                  user="root",
                  password="123456789",
                  database="sample_fp7_2026")
#create the cursor using con object
cur=con.cursor()
#execute the sql query using cursor
```

cur.execute('''insert into sample values(1,"ram",  
"ram@gmail.com",10000)''')

```python
#save the operation
con.commit()
#close the cursor()
cur.close()
#close the connection
con.close()
```

**example:**

```python
#import the mysql connector
import mysql.connector as mysql
#create the connection
con=mysql.connect(host="localhost",
                  user="root",
                  password="123456789",
                  database="sample_fp7_2026")
#create the cursor using con object
cur=con.cursor()
#execute the sql query using cursor
```

cur.execute('''insert into sample values(2,"raj",  
"raj@gmail.com",20000),  
(3,"suraj","suraj@gmail.com",30000)''')

```python
#save the operation
con.commit()
#close the cursor()
cur.close()
#close the connection
con.close()
```

when we want to insert the data into MySQL database table, we will always use "parameterized query" instead of "raw query", while inserting  
data into mysql table using python

**example:**

```python
import mysql.connector as mysql
#create the connection
con=mysql.connect(host="localhost",
                  user="root",
                  password="123456789",
                  database="sample_fp7_2026")
#create the cursor
cur=con.cursor()
#execute the insert as parametrized query
query="insert into sample values(%s,%s,%s,%s)"
values=(4,'madan','madan@gmail.com',34567)
cur.execute(query,values)
con.commit()
#close the cursor
cur.close()
#close the connection
con.close()
```

**example:**

```python
import mysql.connector as mysql
#create the connection
con=mysql.connect(host="localhost",
                  user="root",
                  password="123456789",
                  database="sample_fp7_2026")
#create the cursor
cur=con.cursor()
#execute the insert as parametrized query
query="insert into sample values(%s,%s,%s,%s)"
values=[(5,'rajan','rajan@gmail.com',94567),
        (6,'abcd','abcd@mgail,com',50000)]
cur.executemany(query,values)
con.commit()
#close the cursor
cur.close()
#close the connection
con.close()
```

**example:**

```python
import mysql.connector as mysql
#create the connection
con=mysql.connect(host="localhost",
                  user="root",
                  password="123456789",
                  database="sample_fp7_2026")
#create the cursor
cur=con.cursor()
#execute the select query
cur.execute("select * from sample")
#display only one row from thhe result
result=cur.fetchone()
print(result)
```

**example:**

```python
import mysql.connector as mysql
#create the connection
con=mysql.connect(host="localhost",
                  user="root",
                  password="123456789",
                  database="sample_fp7_2026")
#create the cursor
cur=con.cursor()
#execute the select query
cur.execute("select * from sample")
#display only top 3 rows from the result
result=cur.fetchmany(3)
print(result)
```

**example:**

```python
import mysql.connector as mysql
#create the connection
con=mysql.connect(host="localhost",
                  user="root",
                  password="123456789",
                  database="sample_fp7_2026")
#create the cursor
cur=con.cursor()
#execute the select query
cur.execute("select * from sample")
#read the all rows from the table
result=cur.fetchall()
print(result)
cur.close()
con.close()
```

**example:**

```python
import mysql.connector as mysql
#create the connection
con=mysql.connect(host="localhost",
                  user="root",
                  password="123456789",
                  database="sample_fp7_2026")
#create the cursor
cur=con.cursor()
#execute the update query
query="""update sample set salary=salary+20000
where id=%s"""
values=(1,)
cur.execute(query,values)
con.commit()
#execute the select query
cur.execute("select * from sample")
#read the all rows from the table
result=cur.fetchone()
print(result)
```

**example:**

```python
import mysql.connector as mysql
#create the connection
con=mysql.connect(host="localhost",
                  user="root",
                  password="123456789",
                  database="sample_fp7_2026")
#create the cursor
cur=con.cursor()
#execute the update query
query="""update sample set salary=salary+10000"""
values=()
cur.execute(query,values)
con.commit()
#execute the select query
cur.execute("select * from sample")
#read the all rows from the table
result=cur.fetchall()
print(result)
```

**example:**

```python
import mysql.connector as mysql
#create the connection
con=mysql.connect(host="localhost",
                  user="root",
                  password="123456789",
                  database="sample_fp7_2026")
#create the cursor
cur=con.cursor()
#execute the delete query
query="""delete from sample where id=%s"""
values=(6,)
cur.execute(query,values)
con.commit()
#execute the select query
cur.execute("select * from sample")
#read the all rows from the table
result=cur.fetchall()
print(result)
```

**example:**

```python
import mysql.connector as mysql
#create the connection
con=mysql.connect(host="localhost",
                  user="root",
                  password="123456789",
                  database="employee_fp1_2024")
#create the cursor
cur=con.cursor()
#execute the select query
```

cur.execute("""select id,salary,location  
from employee order by salary desc  
limit 5""")

```python
#read the all rows from the table
result=cur.fetchall()
print(result)
```

---

## Null Values and Case Statement

null values means "no value"  
null refers not a zero , null refers not a empty string  
in order to avoid the null values in the columns, we will always use "not null constraint"  
when we perform any operation with null , we will always get the result  
as "null" only

when we want to work with null data, in MySQL we will use the

**following functions:**

1.isnull()  
2.ifnull()  
3.coalesce()

**example:**

```python
#check the value is null or not
```

select isnull(null);-- 1 means True  
select isnull(100); -- 0 means false

```python
#give the value when the value null, otherwise same as result
#to replace the null values
select ifnull(null,"true");
select ifnull(100,"true");

#give the first non-null as a result
select coalesce(1,2,3,4);
select coalesce(null,2,3,4);
select coalesce(null,null,3,null,5,6,7);
```

**working with case statement:**

**example:**

select id,deptid,salary,  
case  
when salary\<=100000 then "low"  
when salary\>=100000 and salary\<=150000 then "medium"  
when salary\>=150000 then "high"  
else "not available"  
end as result,location from employee  
order by salary;

**example:**

select id,deptid,salary,  
case  
when salary\<=100000 then "low"  
when salary\>=100000 and salary\<=150000 then "medium"  
when salary\>=150000 then "high"  
else "not available"  
end as result,location from employee  
order by 4;

---

## MySQL Built-in Functions

**numeric functions or number functions:**

```sql
select pow(2,3);
select power(2,3);
select ceil(1.234);
select floor(1.234);
select truncate(1.234567,2);
select truncate(1.234567,0);
select truncate(1.234567,4);
select sqrt(4);
select ceil(power(27,1/3));
select greatest(1,2,3,4,5);
select least(1,2,3,4,5);
select bin(100);
select oct(100);
select hex(100);
```

select round(1.2345,2); -- 1.23  
select round(1.2345678,3); -- 1.235  
select round(1.23457689,4); -- 1.2346

```sql
select log(10);
select log2(10);
select log2(100);
select log10(100);
select log10(600);
select exp(1);
```

**MySQL String functions:**

```sql
select length("hello");
select character_length("hello");
select ucase("hello");
select lcase("HELLO");
select upper("hello");
select lower("HELLO");
select concat("hello"," ","world");
select concat_ws(" ","hello","world");
select left("hello world",3);
select left("hello world",5);
select right("hello world",3);
select right("hello world",6);
select ltrim("            hello world");
select rtrim("            hello world          ");
select trim("            hello world           ");
select substring("hello world",2,4);
select substring("hello world",5);
select substr("hello world",3,5);
```

-- before delimiter (1) (@)

```sql
select substring_index("ram@gmail.com","@",1);
```

-- after delimiter (-1) (@)

```sql
select substring_index("ram@gmail.com","@",-1);
select replace("hello world","hello","Hello");
select replace("hello world hello","hello","Hello");
select replace("hello world","hello","Hello");
select replace("hello world hello","hello","Hello");
select reverse("hello");
select instr("hello world","h");
select instr("hello world","Hello");
select instr("hello world","p");
select locate("world","hello world");
select replace("hello world","hello","Hello");
select replace("hello world hello","hello","Hello");
select reverse("hello");
select instr("hello world","h");
select instr("hello world","Hello");
select instr("hello world","p");
select locate("world","hello world");
select insert("hello world",3,0,"hello");
select insert("hello world",3,5,"hello");
select insert("hello world",3,8,'');
```

**MySQL Data and time functions:**

-- only today date

```sql
select curdate();
```

-- current time

```sql
select curtime();
```

-- only today date

```sql
select current_date();
```

-- current time

```sql
select current_time();
```

-- both date and time

```sql
select now();
select sysdate();
select current_timestamp();
select dayname(curdate());
select monthname(current_date());
select year(curdate());
select dayname("2005-8-28");
select monthname("2005-8-28");
select year("2005-8-28");

select date_add("2000-3-30",interval 10 day);
select date_add("2000-3-30",interval -10 day);
select date_add("2000-3-30",interval 10 year);
select date_add("2000-3-30",interval -10 year);
select date_add("2000-3-30",interval 10 month);
select date_add("2000-3-30",interval -10 month);
select date_add("2000-3-30",interval -10 hour);

select date_sub("2000-3-30",interval 10 day);
select date_sub("2000-3-30",interval -10 day);
select date_sub("2000-3-30",interval 10 year);
select date_sub("2000-3-30",interval -10 year);

select datediff(curdate(),'2005-8-28');
```

select floor((datediff(curdate(),'2005-8-28'))/365)  
as age;  
select firstname,  
floor((datediff(curdate(),dob))/365) as age  
from employee order by age desc;

```sql
select date_format(curdate(),"%Y");
select date_format(curdate(),"%m");
select date_format(curdate(),"%d");
select date_format(curdate(),"%d-%m-%Y");
```

select date\_format(dob,"%d-%m-%Y")

```python
from employee;
select date_format(current_timestamp(),"%H");
select date_format(current_timestamp(),"%i");
select date_format(current_timestamp(),"%s");
select date_format(current_timestamp(),"%p");
select date_format(current_timestamp(),"%H:%i:%s %p");
```

---

## Window Functions

when we are working with window function , we will use a function called  
over() along with window function

syntax:

```python
    window_function_name() over()
```

**example:**

**1.first\_value():**

select  
id,firstname,lastname,salary,  
first\_value(salary) over(order by  
salary desc) as "first value"

```python
from employee;
```

select  
id,firstname,lastname,salary,  
first\_value(salary) over(order by  
salary) as "first value"

```python
from employee;
```

select  
id,firstname,lastname,salary,  
abs(salary-(first\_value(salary) over(order by  
salary desc))) as "difference"

```python
from employee;
```

select  
id,firstname,lastname,salary,  
abs(salary-(first\_value(salary) over(order by  
salary desc))) as "difference"

```python
from employee;
```

**2.last\_value():**

select  
id,firstname,lastname,salary,  
last\_value(salary) over(order by  
salary desc  
rows between unbounded preceding  
and unbounded following) as "last value"

```python
from employee;
```

**3.rank():**

select id ,salary,rank() over(order by  
salary desc) as "rank"

```python
from employee;
```

**4.dense\_rank():**

select id ,salary,dense\_rank() over(order by  
salary desc) as "dense rank"

```python
from employee;
```

**note:**

**rank() vs dense\_rank()**

```sql
select count(*) from employee;
```

select id ,salary,rank() over(order by  
salary desc) as "rank"

```python
from employee;
```

select id ,salary,dense\_rank() over(order by  
salary desc) as "dense rank"

```python
from employee;
```

**4.dense\_rank():**

```sql
select count(*) from employee;
```

select id ,salary,rank() over(order by  
salary desc) as "rank"

```python
from employee;
```

select id ,salary,dense\_rank() over(order by  
salary desc) as "dense rank"

```python
from employee;
```

**5.rownum()**

select row\_number()  
over(order by salary desc) as rownum,  
salary,location

```python
from employee;
```

select row\_number()  
over(order by salary asc) as rownum,  
salary,location

```python
from employee;
```

**6.ntile():**

select id,firstname,lastname,location,  
ntile(2) over(order by location desc) as "group"

```python
from employee;
```

select id,firstname,lastname,location,  
ntile(3) over(order by location desc) as "group"

```python
from employee;
```

select id,firstname,lastname,location,  
ntile(4) over(order by location desc) as "group"

```python
from employee;
```

**7.lead():**

select id,firstname,lastname,location,salary,  
lead(salary) over(order by salary desc) as "after"

```python
from employee;
```

**8.lag():**

select id,firstname,lastname,location,salary,  
lag(salary) over(order by salary desc) as "before"

```python
from employee;
```

**9.partition by:**

select dense\_rank()

```python
over(partition by location order by salary desc)
```

as "dense rank",  
salary,location

```python
from employee;
```

select rank()  
over(partition by location order by salary desc) as "rank",  
salary,location

```python
from employee;
```

---

## CTEs and Joins

**working with Joins:**

---

## Programming with SQL

in SQL also we can able to create the "variables"  
when we want to create the variables inside the MySQL, we will use  
the following syntax:  
set @variable\_name:=value  
the above variable is also called as "session variable"

**example:**

-- create the variable

```sql
set @a:=10;
set @b:=20;
select @a+@b;
select max(salary) into @maximum from employee;
select @maximum;
select min(salary) into @minimum from employee;
select @minimum;
```

**in MySQL, we will have three types of variables:**

1) session variable  
to create the session variable , we will always use "set" keyword  
the session variable name always starts with "@"  
2) local variable  
these variable will define inside the function or stored procedure  
to create the local variable, we will use a keyword called "declare"  
3) system variable  
to define the any system variable, we will use before the name  
the system variable name always starts with "@@"  
this we can define using "set" keyword

---

## Stored Procedures, Functions and Triggers

**working with triggers:**

---

## Indexes

indexes are  act as "look up" table for  "columns"  
indexes are used to "faster retrieval of data from the columns" while using  
select operation  
indexes will give the high performance for "data retrieval operations" ,  
indexes will give the very poor performance while doing the "insert or  
delete or update operations"

**in MySQL, we will have two types of indexes:**

**1) clustered index**

clustered index is a index , which will make the any one of the column of the table as index of the column , it will never create separate column for index, generally primary key column of the table always act as "clustered  
index"

**2) non-clustered index:**

non-clustered index is a index , which will create the separate column for index column to maintain the index information, it will never use existing  
table column , except primary key index, all are non-clustered indexes

**when we are creating the indexes in MySQL, we will have the following types:**

**1) primary key index**

it is a index, which taken by the column, when we define the column with  
primary key constraint

**2) unique index:**

it is a index , which is created using index with unique or when we create  
the unique constraint to the column , then that also can act as "unique"  
index

**3) regular index:**

when we create the index for any column without any primary key or  
unique  for a table, then the index is called as "regular index"

**4) composite index:**

when we create the index for two or more columns without any primary key or unique  for a table, then the index is called as "composite index"

**5) full text index:**

when we want to create the indexes for "text column", then we will use  
this index

create the indexes using following syntax:  
create index index\_name on table\_name(col1,col2,col3,.........coln)

when we want to show the list of indexes which are created for any table,  
we will use the following syntax:  
show indexes from table\_name

**example:**

```sql
show indexes from employee;
```

-- regular index

```sql
create index i1 on employee(dob);
```

-- composite index

```sql
create index i2 on employee(deptid,zipcode);
```

-- create the fulltext index

```sql
create fulltext index i3 on employee(firstname);

show indexes from employee;
```

-- regular unique index

```sql
create unique index i4 on employee(dob);
```

**when we want to remove the any index from table , we will use the following syntax:**

```sql
drop index index_name on table_name;
```

**example:**

```sql
show indexes from employee;
```

-- drop the indexes

```sql
drop index i1 on employee;
drop index i2 on employee;
drop index i3 on employee;
drop index i4 on employee;
```

---

## Transactions

in MySQL, we can able to execute the "SQL operations" as transaction mode  
when we want to execute the any sql operation as transaction mode, we  
will always use following syntax:

```sql
start transaction;
```

when we execute the  insert  or  update or delete operation as  
"transaction", those operation can be "rollback"

**example:**

```sql
start transaction;
insert into account values(6,'f',45000);
select * from account;
rollback;
```

**example:**

```sql
start transaction;
update account set account=account+5000;
select * from account;
rollback;
```

**example:**

```sql
start transaction;
delete from account;
select * from account;
rollback;
```

when we want to perform rollback for  multiple sql operations at a time while executing sql operation as transaction, we will use the a concept called save point , following syntax:  
save point savepoint\_name;

**when we want to roll back the save point, we will use the following syntax:**

```sql
                   rollback to savepoint_name;
```

**example:**

```sql
start transaction;
savepoint sp1;
insert into account values(7,'r',25000);
select * from account;
update account set account=account+5000;
select * from account;
delete from account where id=1;
select * from account;
rollback to sp1;
```

**example:**

```sql
use employee_fp1_2024;
start transaction;
update account set account=account+5000;
select * from account;
commit;
rollback;
```

---

## AI/ML
