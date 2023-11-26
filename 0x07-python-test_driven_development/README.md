# 0x07. Python - Test-driven development
## A function that adds intergers
* Prototype: def add_integer(a, b=98):
* a and b must be integers or floats, otherwise raise a TypeError exception with the message a must be an integer or b must be an integer
* a and b must be first casted to integers if they are float
* Returns an integer: the addition of a and b
* You are not allowed to import any module

## A function that divides all elements of a matrix.
* Prototype: def matrix_divided(matrix, div):
* matrix must be a list of lists of integers or floats, otherwise raise a TypeError exception with the message matrix must be a matrix (list of lists) of integers/floats
* Each row of the matrix must be of the same size, otherwise raise a TypeError exception with the message Each row of the matrix must have the same size
* div must be a number (integer or float), otherwise raise a TypeError exception with the message div must be a number
* div can’t be equal to 0, otherwise raise a ZeroDivisionError exception with the message division by zero
* All elements of the matrix should be divided by div, rounded to 2 decimal places
* Returns a new matrix
* You are not allowed to import any module

## A function that prints My name is <first name> <last name>
* Prototype: def say_my_name(first_name, last_name=""):
* first_name and last_name must be strings otherwise, raise a TypeError exception with the message first_name must be a string or last_name must be a string
* You are not allowed to import any module

## A function that prints a square with the character #.
* Prototype: def print_square(size):
* size is the size length of the square
* size must be an integer, otherwise raise a TypeError exception with the message size must be an integer
* if size is less than 0, raise a ValueError exception with the message size must be >= 0
* if size is a float and is less than 0, raise a TypeError exception with the message size must be an integer
* You are not allowed to import any module

## A  function that prints a text with 2 new lines after each of these characters: ., ? and :
* Prototype: def text_indentation(text):
* text must be a string, otherwise raise a TypeError exception with the message text must be a string
* There should be no space at the beginning or at the end of each printed line
* Importing module not allowed

## A unittests for the function def max_integer(list=[]):.
* File should be under tests folder
* Tests will be executed using th command python3 -m unittest tests.6-max_integer_test


## A function that multiplies 2 matrices:
* Prototype: def matrix_mul(m_a, m_b):
* m_a and m_b must be validated with these requirements in this order
* m_a and m_b must be an list of lists of integers or floats:

## A function that multiplies 2 matrices by using the module NumPy
* Installed NumPy using pip3 install numpy==1.15.0
* Prototype: def lazy_matrix_mul(m_a, m_b):
* Test cases should be the same as 100-matrix_mul but with new exception type/message

## A function that prints Python strings.
* Prototype: void print_python_strin
* Only standard C Library is allowed
