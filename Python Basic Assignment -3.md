## Assignment - 3
1. Why are functions advantageous to have in your programs?

Ans: Functions reduce the need for duplicate code. This makes programs shorter, easier to read, and easier to update.2. When does the code in a function run: when it's specified or when it's called?

Ans: The code in a function executes when the function is called, not when the function is defined.3. What statement creates a function?

Ans: def functionName() creates a function4. What is the difference between a function and a function call?

Ans: Function : is a block of code that does a particular operation and returns a result. It usually accepts inputs as 
parameters and returns a result. The parameters are not mandatory.

     Function call : is the code used to pass control to a function.5. How many global scopes are there in a Python program? How many local scopes?

Ans: There is one global scope, and a local scope is created whenever a function is called.6. What happens to variables in a local scope when the function call returns?

ANs: When a function returns, the local scope is destroyed, and all the variables in it are forgotten. we will not be able to access the out side the function.7. What is the concept of a return value? Is it possible to have a return value in an expression?

Ans: A return value is the value that a function calls to evaluate. A return value can be used as a
part of an expression, Like any value.8. If a function does not have a return statement, what is the return value of a call to that function?

Ans: If there is no return statement for a function, its return value is None.9. How do you make a function variable refer to the global variable?

Ans: By representing a variable by global keywaord in the body of a function. For e.g. : global a10. What is the data type of None?

Ans: the data type of None is NoneType.11. What does the sentence import areallyourpetsnamederic do?

Ans: areallyourpetsnamederic ia not a python module. Importing this module will throughs ModuleNotFoundError exception

```python
import areallyourpetsnamederic
```


    ---------------------------------------------------------------------------

    ModuleNotFoundError                       Traceback (most recent call last)

    ~\AppData\Local\Temp/ipykernel_14128/51184242.py in <module>
    ----> 1 import areallyourpetsnamederic
    

    ModuleNotFoundError: No module named 'areallyourpetsnamederic'

12. If you had a bacon() feature in a spam module, what would you call it after importing spam?

Ans: This function can be called with spam.bacon(). like below
    import spam
    spam.bacon()13. What can you do to save a programme from crashing if it encounters an error?

Ans: we can write lines of code in try block. This will not crash the programme. And in except block we can catch the 
exception14. What is the purpose of the try clause? What is the purpose of the except clause?

Ans: Try : The code that could potentially cause an error goes in the try clause.
     except : The code that executes if an error happens goes in the except clause, like print statements about exceptions,
        loggin statements.