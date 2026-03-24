<script src="https://gist.github.com/sakshirathod136/ef13c7d69644dbf30aa8626cbce99406.js"></script># Demonstration of different Python Data Types

# Integer
integer_value = 10
print("Integer value:", integer_value)
print("Type:", type(integer_value))
print()

# Float
float_value = 10.5
print("Float value:", float_value)
print("Type:", type(float_value))
print()

# String
string_value = "Hello Python"
print("String value:", string_value)
print("Type:", type(string_value))
print()

# Boolean
boolean_value = True
print("Boolean value:", boolean_value)
print("Type:", type(boolean_value))
print()

# List
list_value = [1, 2, 3, "Python", 5.5]
print("List value:", list_value)
print("Type:", type(list_value))
print()

# Tuple
tuple_value = (1, 2, 3, "Data")
print("Tuple value:", tuple_value)
print("Type:", type(tuple_value))
print()

# Dictionary
dict_value = {"Name": "Sakshi", "Age": 18, "Course": "Data Science"}
print("Dictionary value:", dict_value)
print("Type:", type(dict_value))
print()

# Set
set_value = {1, 2, 3, 4, 4, 5}
print("Set value:", set_value)
print("Type:",type(set_value))
Integer value: 10
Type: <class 'int'>

Float value: 10.5
Type: <class 'float'>

String value: Hello Python
Type: <class 'str'>

Boolean value: True
Type: <class 'bool'>

List value: [1, 2, 3, 'Python', 5.5]
Type: <class 'list'>

Tuple value: (1, 2, 3, 'Data')
Type: <class 'tuple'>

Dictionary value: {'Name': 'Sakshi', 'Age': 18, 'Course': 'Data Science'}
Type: <class 'dict'>

Set value: {1, 2, 3, 4, 5}
Type: <class 'set'>
 https://www.programiz.com/online-compiler/10m16vJMIU8GV for integer
https://www.programiz.com/online-compiler/4Z2CEe8LwcSqp for float
https://www.programiz.com/online-compiler/0xlVOAn7Trn90 for string
https://www.programiz.com/online-compiler/88MOLjBdqDThE for boolean
https://www.programiz.com/online-compiler/9Rcv2OvTKCMJM for list
https://www.programiz.com/online-compiler/1J8PtTIlC7G2Y for tuple
https://www.programiz.com/online-compiler/85rolhyk0VU24 for dictionary
https://www.programiz.com/online-compiler/0lK40P4LUXHzu for set
 Second assignment 
# Program to add two numbers

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

sum = a + b

print("Sum is:", sum)
1)  a = 5
    b = 5

    c = a + b

    print(c)

output:
10
2)  a = 13
    b = 9.8
    c = "Hello"
    d = True
    e = [1, 3, 7]
    f = (1, 3, 7)
    g = {"Name": "Sakshi", "Age": 20}

    print(type(a))
    print(type(b))
    print(type(c))
    print(type(d))
3)  a = 13
    b = 3.14

    c = int(b)
    d = float(a)
    e = str(a)
    f = bool(a)

    print(type(c))
    print(type(d))
    print(type(e))
    print(type(f))

output:
<class 'int'>
<class 'float'>
<class 'str'>
<class 'bool'>

    print(type(e))
    print(type(f))
    print(type(g))

output:
<class 'int'>
<class 'float'>
<class 'str'>
<class 'bool'>
<class 'list'>
<class 'tuple'>
<class 'dict'>
4)  a = 5
    b = 12
    c = 10

    print(a > b and a == c)
    print(a < b or a != c)
    print(not(a == b))

output:
False
True
True


