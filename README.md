# python-practice-
python practice  
Here are the 10 questions:

Create three variables: name, age, and city, and print a formatted sentence using them.

Assign "Red", "Green", and "Blue" to three variables in one line and print them.

Given the string "PythonProgramming", print "Python", the last 6 characters, and the string reversed using slicing.

Convert two strings "Data" and "Engineer" to uppercase and join them with a space.

Check and print the data types of 10, 3.14, "Hello", and True.

Use string formatting to print: "Shantanu scored 92.5 marks in the exam."

Write a program to check if a person is eligible to vote based on age input.

Take two numbers from the user and print their addition, subtraction, multiplication, division, and modulus.

Predict the output of a function that changes a global variable x from 5 to 10.

Print the sentence: Shantanu said, "Learning Python isn't difficult!" using escape characters.



# 🔷 10 Medium-Level Python Questions (Strictly from Your Topics)
 1. Variable Swapping Without Temp Variable
Swap the values of a = 10 and b = 20 without using a third variable. Print before and after values.

2. Extract Info from a Combined String
Given info = "Shantanu-25-Delhi"

Extract name, age, and city using string slicing or methods

Print in the format: Name: Shantanu, Age: 25, City: Delhi

3. Use of Global Variable in a Function

python
Copy
Edit
x = 10

def update():
    # change the global x to 30 inside this function

update()
print(x)  # Should print 30
✅ Write the missing logic using global.

4. Boolean Check with Operators
Take two numbers as input.
Print True if the first number is divisible by 5 and the second is greater than 50. Else print False.

5. Advanced String Slicing
Given message = "LearningPython"

Print every alternate character

Print the string in reverse

Remove "Python" using slicing only

6. Concatenate and Format Strings
Create 3 variables:

python
Copy
Edit
first = "Hello"
second = "Shantanu"
third = "Welcome"
Print: "Hello, Shantanu! Welcome to Python." using string formatting.

7. Use of String Methods
Given text = " Hello World! "

Strip the spaces

Convert it to uppercase

Replace "WORLD" with "Shantanu"
Expected Output: HELLO SHANTANU!

8. Comparison & Logical Operators
Set x = 10, y = 20, z = 10
Write an expression using comparison and logical operators that returns True only if:

x equals z

and y is greater than x

9. String with Escape Characters
Print the following using escape characters in a single line:
Shantanu said, "Python is awesome!"

10. Data Type Check and Conversion
Let num = "100" (string)

Check its data type

Convert it to an integer

Add 50 and print the final value and its type



# 🔴 5 Hard-Level Python Questions

1. Format a Full Table Using Variables
You are given these variables:

python
Copy
Edit
name1 = "Shantanu"
age1 = 25
city1 = "Delhi"

name2 = "Riya"
age2 = 22
city2 = "Mumbai"
Print them in this exactly aligned table format using string formatting:

nginx
Copy
Edit
Name       Age   City
Shantanu   25    Delhi
Riya       22    Mumbai
2. Dynamic Sentence Using Multiple Data Types
Create variables:

python
Copy
Edit
name = "Shantanu"
age = "25"  # string
score = 88.7  # float
Now print a sentence:
"Shantanu is 25 years old and scored 88.7 marks."
But before that:

Convert age to integer

Round the score to 1 decimal place

Use f-string or format() to build the sentence

3. Complex Boolean Expression
Set:

python
Copy
Edit
x = 5
y = 10
z = 15
Write a single line Boolean expression that returns True only if:

x is less than y

z is greater than y

y is not equal to 0

(z minus x) is greater than (y divided by x)

4. Build a Secret Message from a String
Given:

python
Copy
Edit
text = "p#y!t$h@o^n_123"
Use only string slicing and concatenation to extract and print: "python"
(Do not use replace(), loops, or regex)

5. Global Variable Modification via Arithmetic
You have:

python
Copy
Edit
a = 10
b = 5
Write a function that modifies a globally by setting it equal to a * b + 15, and then prints the new value of a.

