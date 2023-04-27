# JS-Fibonacci-sequence-Expalanation

##Class Work ---



The code is a JS function that generates the Fibonacci up to an owner enterd number. And this is what it does:

At first make the value of an input element with the ID "txtNumber" and assigns it to the var = "numberEntered" which has an HTML input element with the ID "txtNumber".

Next, you initialize two variables, "counter" and "fib". Where "counter" is set to 1, and "fib" is set as an empty array.

The if-else if statements check if the value entered is 0, 1, or 2. 
If it is 0, it sets the "fib" array to [0]. If it is 1, it sets the "fib" array to [1]. If it is 2, it sets the "fib" array to [1, 1].

 If the number entered is greater than 2, the code enters a while loop that generates the Fibonacci sequence. The loop runs as long as "counter" is <  than the difference between the "numberEntered" and 1. And that it generates Fibonacci numbers up to the "numberEntered".

Inside the loop, the code uses the "push()" method to add the sum of the last two numbers in the "fib" array to the end of the array.

And at last, the function sets the innerHTML of an element with the ID "dialogboxbody" in the HTML to the "fib" array, which displays the Fibonacci sequence to the user as output.

This code uses if-else if statements and a while loop to generate the Fibonacci up to an input-specified number, and displays it in the HTML element with the ID "dialogboxbody".


Thanks :)

