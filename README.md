# Python for Beginner
If you are curious about Python programming and want to learn more about it, sure, this page may suit you!

This README will provide you a clear grasp of some important fundamental in Python, making your learning experience more enjoyable and straightforward.

Happy growing!

## Function
A function is a unit of code that only executes when invoked. A function may return data as a result. In Python, a function is defined with the `def` keyword.

### 1. Create a Function
Use the `def`keyword

<img src="https://github.com/khanshafiira/PythonKnowledge-2/assets/166186201/589f4629-f076-4c54-ba5b-ab9353a6bea2" width="350" height="80">

### 2. Calling a Function
Use the function name followed by paranthesis

<img src="https://github.com/khanshafiira/PythonKnowledge-2/assets/166186201/68edb000-189c-4ffb-a154-f98c2c9f848e" width="350" height="150">  

### 3. Return Statement
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
  
### 4. Pass by reference vs Value
**What is pass by reference?**

*Pass by Reference* indicates that you must send the function (reference) to a variable, implying that the variable already exists in memory. The function adds the string "Geeks" to the list supplied to it and prints it. Because lists are changeable data types, any changes made to the list within the function are mirrored outside the function, as shown in the output.

Example:

<img src="https://github.com/khanshafiira/PythonKnowledge-2/assets/166186201/729ebeaa-5c67-4789-90e1-89c7d6ca4078" width="460" height="170">

**What is pass by value?**

*Pass by values* means passing a copy of the function's actual variables as a parameter. As a result, any changes to the function's parameters will not affect the actual variable.

Example:

<img src="https://github.com/khanshafiira/PythonKnowledge-2/assets/166186201/8d221e9e-b35a-4089-bb9d-1eef6047ed6a" width="460" height="180">

## NumPy

NumPy is Python's essential scientific computing library. It is **a Python library** that **includes a multidimensional array object, various derived objects** (such as masked arrays and matrices), **and a collection of routines for performing fast array operations**, such as mathematical, logical, shape manipulation, sorting, selecting, I/O, discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation, and much more.

You can use NumPy in Python by import it

Example #1:

<img src="https://github.com/khanshafiira/PythonKnowledge-2/assets/166186201/874929b8-053c-44a7-8a72-f9a49efb84a6" width="180" height="80">

### Dimension
NumPy's primary object is a homogenous multidimensional array. It is a table with elements (typically numbers) of the same type, each indexed by a non-negative integer tuple. In NumPy, **dimensions are referred to as axes**.

#### 0-D array

<img src="https://github.com/khanshafiira/PythonKnowledge-2/assets/166186201/1b435a0d-fe8a-4b3f-8182-671bcc25578a" width="400" height="100">

#### 1-D array

<img src="https://github.com/khanshafiira/PythonKnowledge-2/assets/166186201/128dc9e2-de00-486a-aff8-9b63ad361edd" width="400" height="100">

#### 2-D array

<img src="https://github.com/khanshafiira/PythonKnowledge-2/assets/166186201/2ee00247-d609-419a-863b-cc649ccdd075" width="400" height="100">

#### 3-D array

<img src="https://github.com/khanshafiira/PythonKnowledge-2/assets/166186201/202fd0fa-fc70-47c1-8665-98b6116b9eb0" width="400" height="130">
