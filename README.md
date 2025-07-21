# Aim
To write a C++ program that takes user input for various data types (int, float, string, double, char, and bool), displays the entered values, and shows the memory size (in bytes) occupied by each data type using the sizeof() operator.

# Theory
In C++, different data types require different amounts of memory to store their values. Understanding how much memory each type consumes is essential for efficient programming and memory management.

 ## Key Concepts Used:
Data Types:

int: Used for integer values (e.g., 1, 10, -5)

float: Used for decimal values with single precision

double: Used for decimal values with double precision

char: Used for storing a single character

bool: Used for storing boolean values (true/false)

string: Used for sequences of characters (words, text)

sizeof() Operator:

Returns the size (in bytes) that a data type or variable occupies in memory.

## Input/Output:

cin is used for taking input from the user.

cout is used to display output to the console.

# Example


```plaintext
Enter any integer: 123
Integer = 123 And the size is: 4 bytes
Enter any decimal number: 123.33
Decimal = 123.33 And the size is: 4 bytes
Enter any String: hello!
String = hello! And the size is: 32 bytes
Enter any double: 25.776
Double = 25.776 And the size is: 8 bytes
Enter any character: H
Char = H And the size is: 1 byte
Enter boolean: 0
Boolean = 0 And the size is: 1 byte
```
# Conclusion 
The program successfully takes inputs of various data types from the user and uses the sizeof() operator to display their memory usage. This program is a useful demonstration for understanding how different data types are represented and stored in memory in C++. It reinforces the concept of type sizes and helps build foundational knowledge for memory-efficient programming.
