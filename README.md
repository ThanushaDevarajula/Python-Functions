# Python_Functions                     
## INTRO TO PYTHON FUNCTIONS                         

  Functions are reusable pieces of programs. They allow you to give a name to a block of statements, allowing you to run that block using the specified name anywhere in your program and any number of times. This is known as calling the function.
 ### Types of FUNCTIONS in PYTHON
1. User defined Functions
2. Bulit_in Functions
3. Lambda Functions
4. Recurtions Functions

#### Defining Function   
Functions are defined using the def keyword. After this keyword comes an identifier name for the function, followed by a pair of parentheses which may enclose some names of variables, and by the final colon that ends the line. Next follows the block of statements that are part of this function.
## USER_DEFINED FUNCTIONS:
#### Creating a Function
-In Python a function is defined using the *def* keyword:

***Example***
````
def my_function():
  print("Hello from a function")
 `````
 #### Calling a Function
-To call a function, use the function name followed by parenthesis:                                                
***Example***
`````
def my_function():
  print("Hello from a function")
  my_function()
>>"Hello from a function"
``````

### Function Parameters:
      A function can take parameters, which are values you supply to the function so that the function can do something utilising those values. These parameters are just like variables except that the values of these variables are defined when we call the function and are already assigned values when the function runs.
 ***Example***
 ````
 def print_max(a, b):
    if a > b:
        print(a, 'is maximum')
    elif a == b:
        print(a, 'is equal to', b)

    else:
        print(b, 'is maximum')
 ``````

*** Here, we define a function called print_max that uses two parameters called a and b. We find out the greater number using a simple if..else statement and then print the bigger number ***
 ## RECURSION FUNCTION
- Python also accepts function recursion, which means a defined function can call itself.
- Recursion is a common mathematical and programming concept. It means that a function calls itself. This has the benefit of meaning that you can loop through data to reach a result.                                                                    
**Example**

````
Recursion Example
def tri_recursion(k):
  if(k>0):
    result = k+tri_recursion(k-1)
    print(result)
  else:
    result = 0
  return result

print("\n\nRecursion Example Results")
tri_recursion(6)
>>Recursion Example Results
1
3
6
10
15
21
`````
## LAMBDA FUNCTION
- Lambda is a tool for building functions, or more precisely, for building function objects.
- A lambda is  function can take any number of arguments, but can only have one expression.

**Syntax**
````
lambda arguments : expression
(The expression is executed and the result is returned)
````
***Example***
````
- A lambda function that adds 10 to the number passed in as an argument, and print the result
x = lambda a : a + 10
print(x(5))
````
````
- A lambda function that multiplies argument a with argument b and print the result:

x = lambda a, b : a * b
print(x(5, 6))
````
`````
- A lambda function that sums argument a, b, and c and print the result:

x = lambda a, b, c : a + b + c
print(x(5, 6, 2))
`````
## BUILT_IN FUNCTIONS
The Python interpreter has a number of functions that are always available for use. These functions are called built-in functions.
- Python has a set of built-in functions                                    
```````
Function                     Description
abs()	             Returns the absolute value of a number
all()	             Returns True if all items in an iterable object are true
any()	             Returns True if any item in an iterable object is true
ascii()	           Returns a readable version of an object. Replaces none-ascii characters with escape character
bin()	             Returns the binary version of a number
bool()	           Returns the boolean value of the specified object
bytearray()        Returns an array of bytes
bytes()	           Returns a bytes object
callable()	       Returns True if the specified object is callable, otherwise False
chr()	             Returns a character from the specified Unicode code.
classmethod()	     Converts a method into a class method
compile()	         Returns the specified source as an object, ready to be executed
complex()	         Returns a complex number
delattr()	         Deletes the specified attribute (property or method) from the specified object
dict()	           Returns a dictionary (Array)
dir()	             Returns a list of the specified object's properties and methods
divmod()	         Returns the quotient and the remainder when argument1 is divided by argument2
enumerate()	       Takes a collection (e.g. a tuple) and returns it as an enumerate object
eval()	           Evaluates and executes an expression
exec()	           Executes the specified code (or object)
filter()	         Use a filter function to exclude items in an iterable object
float()	           Returns a floating point number
``````````
### CONCLUTION:
- In Python, there are many built-in functions. Few are listed above.
- The function concept is probably the most important building block in any programming language),

 

