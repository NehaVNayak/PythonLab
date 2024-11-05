
# Python Exercises

## 1. Write a python script to display the following on the interactive document by using the print() function.  
- Name  
- Usn  
- Branch  
- CGPA  

```python
print("Name: Neha Vithob Nayak")
print("USN: 123456")
print("Branch: Computer Science")
print("CGPA: 9.88")
```

## 2. Create a Python script that stores a string in a variable, then prints the string by referencing the variable within the print() function.

```python
greeting = "Hello, welcome to Python programming!"
print(greeting)
```

## 3. Write a Python script to display the value/text on the interactive document using a variable.

```python
text = "This is displayed using a variable."
print(text)
```

## 4. Write a Python script to read user input with the following formats and display it on the web interface document.

### i. Call input built-in function directly to read the input

```python
print(input("Enter something: "))
```

### ii. Use variable to assign the input value to the variable

```python
user_input = input("Enter another thing: ")
print(user_input)
```

### iii. Pass input built-in function as an argument to the print() function to read the input.

```python
print(input("Enter a third thing: "))
```

## 5. Write a Python script to determine the data type for the following using the type() function:
- Number  
- String  
- Float  
- Double  
- Char  
- Boolean  

```python
print(type(42))           # Integer
print(type("Python"))     # String
print(type(3.14))         # Float
print(type(3.14159265359)) # Double approximation
print(type('c'))          # Char (single character string)
print(type(True))         # Boolean
```

## 6. Write a Python script to compute the length of a string using with and without variables.

```python
string = "Hello, World!"
print(len(string))         # With variable
print(len("Python"))       # Without variable
```

## 7. Write a Python script to determine the multiline string for the following and display some text using double quotes.

```python
multiline_string = '''An example of a
string that spans
across multiple lines that also preserves whitespaces'''
print(multiline_string)
```

## 8. Write a Python script to perform concatenation of two strings with and without variables.

```python
part1 = "Hello"
part2 = "World"
print(part1 + " " + part2)  # With variables
print("Hello" + " " + "World")  # Without variables
```

## 9. Write a Python script to read the student name from the keyboard and display the same on the interactive web document.

```python
student_name = input("Enter student name: ")
print("Student Name:", student_name)
```

## 10. Write a Python script to evaluate basic arithmetic operations (addition, subtraction, multiplication, division) using input values and display the result on the interactive document with proper labels for each operation.

```python
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
print("Addition:", num1 + num2)
print("Subtraction:", num1 - num2)
print("Multiplication:", num1 * num2)
print("Division:", num1 / num2)
```

## 11. Write a Python script to display the following:
- Character using string indexing  
- String index out of range  
- Character using negative indexing  

```python
sample_string = "Python"
print(sample_string[0])        # Character at index 0
# print(sample_string[100])    # Uncomment to see 'String index out of range' error
print(sample_string[-1])       # Character using negative indexing
```

## 12. Write a Python script to extract the substring from the main string using indexing, also verify the following string slicing result:
- [x : y] ; [ x:y :z ]  
- [ x : ]  
- [ : y]  
- [ : ]  
- [-x : -y]  
- [ : -y]  
- [-x: ]  

```python
main_string = "Hello, World!"
print(main_string[0:5])        # [x : y]
print(main_string[0:5:2])      # [x : y : z]
print(main_string[0:])         # [x :]
print(main_string[:5])         # [: y]
print(main_string[:])          # [:]
print(main_string[-5:-1])      # [-x : -y]
print(main_string[:-1])        # [: -y]
print(main_string[-5:])        # [-x :]
```

## 13. Write a Python script to demonstrate the use of string built-in functions to change the case of a string, both with and without using a variable.

```python
string_case = "Python Programming"
print(string_case.upper())        # With variable
print("Python".lower())           # Without variable
```

## 14. Write a Python script to remove white spaces using built-in functions: rstrip(), lstrip(), and strip() for the following string: “ Department of Computer Science ”.

```python
department_string = "   Department of Computer Science   "
print(department_string.rstrip())
print(department_string.lstrip())
print(department_string.strip())
```

## 15. Write a Python script to find the starting and ending substring from the main string using built-in functions.

```python
main_str = "Department of Computer Science"
print(main_str.startswith("Department"))
print(main_str.endswith("Science"))
```
