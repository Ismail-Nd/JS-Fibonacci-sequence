                                          # JS-Fibonacci-sequence [Class-Work]
										  
										  

                                                 ## HTML Expalnation


This is a block of HTML code that defines a web page layout with a form for generating a Fibonacci sequence. 

The code contains two main `div` containers with class names of `container` and `gameDiv`. Inside the `gameDiv` container, there is an `h1` heading tag that displays the text "Lets get a Fibonacci Sequence:". Below that, there is a form element with an `input` element that takes a number input from the user. The input element has an `id` of "txtNumber" and a `name` attribute of "txtNumber". The `placeholder` attribute is set to "Enter a number" to provide the user with instructions on what to enter.

Next, there is a button element with a `class` attribute set to "button" and an `onclick` attribute set to "Alert.render()". This button triggers a JavaScript function called `Alert.render()` when it is clicked. 

Finally, there are two more `div` containers with `id` attributes of "dialogoverlay" and "dialogbox". These containers will be used to display a custom dialog box that pops up when the user clicks on the "Generate" button.

Overall, this HTML code provides the basic structure for a web page that allows the user to enter a number and generate a Fibonacci sequence using JavaScript. However, it is incomplete without the JavaScript code that handles the form submission and generates the sequence.

                                                 ## Js Expalanation


The code is a JS function that generates the Fibonacci up to an owner enterd number. And this is what it does:

At first make the value of an input element with the ID "txtNumber" and assigns it to the var = `numberEntered` which has an HTML input element with the ID `txtNumber`.

Next, you initialize two variables, `counter` and `fib`. Where `counter` is set to 1, and `fib` is set as an empty array.

The if-else if statements check if the value entered is 0, 1, or 2. 
If it is 0, it sets the "fib" array to [0]. If it is 1, it sets the `fib` array to [1]. If it is 2, it sets the `fib` array to [1, 1].

 If the number entered is greater than 2, the code enters a while loop that generates the Fibonacci sequence. The loop runs as long as `counter` is <  than the difference between the `numberEntered` and 1. And that it generates Fibonacci numbers up to the `numberEntered`.

Inside the loop, the code uses the `push()` method to add the sum of the last two numbers in the `fib` array to the end of the array.

And at last, the function sets the innerHTML of an element with the ID `dialogboxbody` in the HTML to the `fib` array, which displays the Fibonacci sequence to the user as output.

This code uses if-else if statements and a while loop to generate the Fibonacci up to an input-specified number, and displays it in the HTML element with the ID `dialogboxbody`.


`Thanks :)`

