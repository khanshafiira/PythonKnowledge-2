# Python for Beginner
If you are curious about Python programming and want to learn more about it, sure, this page may suit you!

This README will provide you a clear grasp of some important fundamental in Python, making your learning experience more enjoyable and straightforward.

Happy growing!

# Function
A function is a unit of code that only executes when invoked. A function may return data as a result. In Python, a function is defined with the `def` keyword.

## 1. Create a Function
Use the `def`keyword

<img src="https://github.com/khanshafiira/PythonKnowledge-2/assets/166186201/589f4629-f076-4c54-ba5b-ab9353a6bea2" width="350" height="80">

## 2. Calling a Function
Use the function name followed by paranthesis

<img src="https://github.com/khanshafiira/PythonKnowledge-2/assets/166186201/68edb000-189c-4ffb-a154-f98c2c9f848e" width="350" height="150">  

## 3. Return Statement
The Python return statement is a special statement that **can be used within a function or method to return the function's results to the caller**.

Characteristics:
- contains the return keyword followed by an optional return value
- Python functions can return any Python object
- might be placed in a variable to distinguish it from a function that does not return a value (also known as a procedure).

Example #1:

<img src="https://github.com/khanshafiira/PythonKnowledge-2/assets/166186201/f7ceca8b-8440-44e0-be13-3e6d425105bf" width="310" height="170">

`

**#Notes** The difference between `print` and `return` :
- `print` is a Python built-in function and **only** displaying output on the console or terminal.
- `return` specifies the value that a function should return when it is called. It performs certain computations or operations before returning the result or a group of data to the calling code.

Example #2:
- Using input() and print() instead of return in functions, which is handy when there are many variables to be shown.

  <img src="https://github.com/khanshafiira/PythonKnowledge-2/assets/166186201/d3989ee8-e1fb-4349-add9-7a77a94d311b" width="450" height="160">

- input the variable
  
  [for example, if you want to search for the result of the square root of 36]
  <img src="https://github.com/khanshafiira/PythonKnowledge-2/assets/166186201/18d93b4c-155d-4932-a621-d8eafedc5716" width="450" height="160">

  [for example, if you want to search for the result of the square root of 169]
  <img src="https://github.com/khanshafiira/PythonKnowledge-2/assets/166186201/e3df173c-3d04-4a23-a238-5d2ca7d54285" width="450" height="160">
  
## 4. Pass by reference vs Value
**What is pass by reference?**
~Pass by Reference~ indicates that you must send the function (reference) to a variable, implying that the variable already exists in memory. The function adds the string "Geeks" to the list supplied to it and prints it. Because lists are changeable data types, any changes made to the list within the function are mirrored outside the function, as shown in the output.

**What is pass by value?**
~Pass by values~ means passing a copy of the function's actual variables as a parameter. As a result, any changes to the function's parameters will not affect the actual variable.


