# Python Exercises

# 1. Display basic student information.
print("Name: Neha Vithob Nayak")
print("USN: 123456")
print("Branch: Computer Science")
print("CGPA: 9.88")

# 2. Store a string in a variable and print it.
greeting = "Hello, welcome to Python programming!"
print(greeting)

# 3. Display the value/text using a variable.
text = "This is displayed using a variable."
print(text)

# 4. Read and display user input in various formats.
# i. Call input directly
print(input("Enter something: "))

# ii. Assign input to a variable
user_input = input("Enter another thing: ")
print(user_input)

# iii. Pass input as argument to print
print(input("Enter a third thing: "))

# 5. Determine data types using type() function.
print(type(42))           # Integer
print(type("Python"))     # String
print(type(3.14))         # Float
print(type(3.14159265359)) # Double approximation
print(type('c'))          # Char (single character string)
print(type(True))         # Boolean

# 6. Compute string length with and without variable.
string = "Hello, World!"
print(len(string))         # With variable
print(len("Python"))       # Without variable

# 7. Multiline string example.
multiline_string = """An example of a
string that spans
across multiple lines that also preserves whitespaces"""
print(multiline_string)

# 8. Concatenate strings with and without variables.
part1 = "Hello"
part2 = "World"
print(part1 + " " + part2)  # With variables
print("Hello" + " " + "World")  # Without variables

# 9. Read and display student name.
student_name = input("Enter student name: ")
print("Student Name:", student_name)

# 10. Basic arithmetic operations with user input.
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
print("Addition:", num1 + num2)
print("Subtraction:", num1 - num2)
print("Multiplication:", num1 * num2)
print("Division:", num1 / num2)

# 11. String indexing examples.
sample_string = "Python"
print(sample_string[0])        # Character at index 0
# print(sample_string[100])    # Uncomment to see 'String index out of range' error
print(sample_string[-1])       # Character using negative indexing

# 12. Substring extraction and slicing.
main_string = "Hello, World!"
print(main_string[0:5])        # [x : y]
print(main_string[0:5:2])      # [x : y : z]
print(main_string[0:])         # [x :]
print(main_string[:5])         # [: y]
print(main_string[:])          # [:]
print(main_string[-5:-1])      # [-x : -y]
print(main_string[:-1])        # [: -y]
print(main_string[-5:])        # [-x :]

# 13. String case change with and without variable.
string_case = "Python Programming"
print(string_case.upper())        # With variable
print("Python".lower())           # Without variable

# 14. Remove white spaces using rstrip(), lstrip(), and strip().
department_string = "   Department of Computer Science   "
print(department_string.rstrip())
print(department_string.lstrip())
print(department_string.strip())

# 15. Find starting and ending substring using startswith() and endswith().
main_str = "Department of Computer Science"
print(main_str.startswith("Department"))
print(main_str.endswith("Science"))
