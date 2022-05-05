# Section A: Code Review - Option 2: Java Task


## Scores

* **Overall Score: 68.75%**


* **Correctness: 2/4**

    The return keyword in the 'reverse_string' function is calling a function that does not exist. This is due to naming the function incorrectly. When you call the  'reverseString' on line 26, it needs to match the same casing as the 'reverse_string' that you defined on line 18.
    
    The variable 'maxNumber' is being defined twice. Once in the parameter of 'function' on line 28, and then once again as an integer on line 30. This leads to runtime errors due to your computer not knowing how to define the variable.
    
    The 'function' method is not being called, which means the code for it is not being used at all. The print statement inside the 'main' method will need to call the 'function' method in order for it to create the Fibonacci Series.
* **Efficiency: 3/4**

    The 'function' method is not using recursion, and is instead making use of a for-loop. While it is true that for-loops can be very powerful and helpful in our code, a problem like this will be better handled by recusion. This is because recursion allows your code to function more efficiently during complex operations, while also making it more readible.
* **Style: 3/4**

    It is much better practice to separate your 'main' method from your calculation methods in your program. Grouping similar functions together helps you to better read and control changes in your code, especially when you are dealing with large programs.

    The name, 'function' is not good naming practice. When creating a method/ function it is important not to use common programming terms, as this can be confusing to anyone reading your code. Rather go with names that describe what the method will be doing, such as 'fibonacci'.

    When programming, it is important to follow good styling practices. This allows programmers (Including yourself) to easily read and follow your code in order to work more efficiently. Remember to always indent your code correctly and to use declaritive names for your functions and variables. Always doublecheck the naming convention of your current language if you are unsure.
* **Documentation: 3/4**
    
    Comments are clear at indicating what the code does.

    The printed output can be misleading due to the fact that it doesn't call the 'function' method.

## Positive Aspects

Your code is well commented and it is structured neatly. You also showed good understanding of what you need to do in your first function (reverse_string).

## Aspects that could be improved

I would focus on changing your approach for the Fibonacci Series to fit with a recursive method and just fixing the few errors in your code.

## Overall Feedback

Besides the few changes that need to be made, you did really good. 

Every mistake is a step closer to being a better programmer.  :D 
