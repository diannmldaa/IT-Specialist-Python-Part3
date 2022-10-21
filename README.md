# IT-Specialist-Python-Part3

## Function ( Definition, Calling, Return) ##

### Definition ###
In mathematics, a function is a process that relates an input (input) and an output (output). In Python, besides these relational functions, functions are also a way to organize code - with the ultimate goal of code reusability.

### Create Function ### 
In Python a function is defined using the `def` keyword:

<img width="350" alt="image1" src="https://user-images.githubusercontent.com/61875831/194754467-a87056d8-fb19-4cb0-9616-aeb1fec2e091.png">

### Calling Function ### 
To call a function, use the function name followed by parenthesis:

<img width="350" alt="image1" src="https://user-images.githubusercontent.com/61875831/194754751-f3e355ed-ff81-44b2-8abd-5418fe46441f.png">

### Return Function ### 

* The return [expression] statement will make program execution exit the current function while returning a specified value.
* The return value of a function can be stored in a variable.

For Example:

<img width="696" alt="image1" src="https://user-images.githubusercontent.com/61875831/194758359-0b2c27d4-1da9-4407-b3e7-31c6d0894857.png">

### Pass by Reference vs Value ### 

* All parameters (arguments) in python are "passed by reference". It means that when we change a variable, the data that refers to it will also change, both inside the function and outside the calling function.
* Except, if using assignment operations that will change the reference parameter.

For Example:

<img width="458" alt="image1" src="https://user-images.githubusercontent.com/61875831/194758604-e8376773-de4c-4bff-afd8-431f5e92d3c1.png">

### Arguments & Parameters ### 

Parameters are defined by the names that appear in a function definition, whereas arguments are the values actually passed to a function when calling it. Parameters define what types of arguments a function can accept. For example, given the function definition:

For Example:

<img width="318" alt="image1" src="https://user-images.githubusercontent.com/61875831/194760262-56de76ba-4776-48aa-88e1-c0d6b529d305.png">

Noted:
* x = Parameters
* 3 = Arguments

## Pydoc ##

### Pydoc ###

How to call pydoc use terminal:

<img width="220" alt="image1" src="https://user-images.githubusercontent.com/61875831/194763173-a6fa825c-d255-4a9f-8482-43eb30555678.png">

## File .txt ( Open, Read, and Close ) ##

### Open ###

If we want to open and read all contents in a file of type 'text-document', use functions `open` and `read`:

<img width="282" alt="image1" src="https://user-images.githubusercontent.com/61875831/194777161-2ebbbabc-deff-40e1-9cd7-3bed31538202.png">

### Read ### 

Read per line a file of type 'text document' use function `open` and `readline` (The readline() function will read per line starting from line 1 then line 2 and then line 3 and other lines):

<img width="299" alt="image1" src="https://user-images.githubusercontent.com/61875831/194777592-96136588-f053-43e4-80c5-e606bd364140.png">

### Close ### 

Close a file of type 'text document' use function `close`:

<img width="250" alt="image1" src="https://user-images.githubusercontent.com/61875831/194778039-9def0fc8-6524-4829-b106-abed5bc319c6.png">

## File .txt ( Write ) ##

### Write ###

Create and add contents file of type 'text document' use function `write` and parameter `w`:

<img width="407" alt="image1" src="https://user-images.githubusercontent.com/61875831/194778513-4a6b5256-95a2-43f4-b98a-223465f02772.png">

## File .txt ( Check Existance ) ##

### Check Existance ###

Will check the existence of a file using the `os` module if there is no file it will create a new file, but if it already exists it will enter the input value into the newly created file.

<img width="543" alt="image1" src="https://user-images.githubusercontent.com/61875831/194781139-f4079aed-b629-4445-9316-09fbff85455f.png">

## File .txt ( Delete ) ##

### Delete ###

Remove file using the `os` module and `os.remove`:

<img width="318" alt="image1" src="https://user-images.githubusercontent.com/61875831/194782270-fd6c6fd2-ff05-4c5e-b071-bad75d1db85d.png">

## The Module Math ##

### Import Module Math ###

Python has a built-in module called `math`, which extends the list of mathematical functions.
To use it, you must import the `math` module:

<img width="200" alt="image1" src="https://user-images.githubusercontent.com/61875831/194783519-3fee0681-651f-47fa-aad9-c7f415622082.png">

### Method in Math Module ###

<img width="662" alt="image1" src="https://user-images.githubusercontent.com/61875831/194785257-dd805c63-009f-4ed1-baa6-1209b71626cb.png">

## The Module Date ##

### Import Module Date ###

A date in Python is not a data type of its own, but we can import a module named `datetime` to work with dates as date objects.

<img width="140" alt="foto1" src="https://user-images.githubusercontent.com/61875831/194806878-c50f978d-5dd9-4aec-97a0-f9a878b83b37.png">

### Method in Date Module ###

<img width="458" alt="foto1" src="https://user-images.githubusercontent.com/61875831/194807031-39890828-4136-45a4-84d7-19a0c46f0e5d.png">

## The Module Input Output ##

### Import Module Input Output ###

Import a module named `io` to work with input and output module.

<img width="120" alt="foto1" src="https://user-images.githubusercontent.com/61875831/194809999-669c5a36-abdc-482b-b147-f7baee1d073f.png">

## The Module Sys ##

### Import Module Sys ###

This module provides access to some variables used or maintained by the interpreter and to functions that interact strongly with the interpreter. It is always available. Import a module named `sys` to work with sys module. For example:

<img width="458" alt="foto1" src="https://user-images.githubusercontent.com/61875831/194818224-8b855bcf-e081-4855-81ac-f0bcf722877d.png">

## The Module Random ##

### Import Module Random ###

This module implements pseudo-random number generators for various distributions. For example:

<img width="320" alt="foto1" src="https://user-images.githubusercontent.com/61875831/194821724-86f2f94a-85f6-429f-930b-ee424600c3a7.png">
