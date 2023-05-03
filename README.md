Download Link: https://assignmentchef.com/product/solved-cs1xc3-assignment-2-c-programming-basics
<br>
<strong>Primary Learning Objectives</strong>

<ul>

 <li>Write basic C programs using variables, control structures and functions.</li>

</ul>

<strong> </strong>Requirements<em> </em>

<em>Question 1 – Investment calculator – </em>

Create a program that asks the user for an initial investment amount, a number of years, a return rate, and an additional contribution per year. The program should then output a neatly formatted table of the investment returns from year one until the final year. All dollar figures in the table should output with 2 digits of precision.  The table columns should be: Year, Start Balance, Interest and End Balance.  The year column should be 10 characters in length, the others should be 20 characters in length.  The data in all columns should be left-aligned. Use a for loop to compute and present the table of data.

The results should be the same as the investment calculator that appears on this page when using the “End Result” calculator (the default calculator that shows when the page first loads) and contributions set to each year: <a href="https://www.calculator.net/investment-calculator.html">https://www.calculator.net/investment</a><a href="https://www.calculator.net/investment-calculator.html">–</a><a href="https://www.calculator.net/investment-calculator.html">calculator.html</a><a href="https://www.calculator.net/investment-calculator.html">.</a>  If numbers are somehow off by very small amount like 0.01, that’s fine, don’t worry about that, it’s probably just a small rounding error with the web app.  In the example below the additional contribution is added at the start balance at the beginning of each year, in the web app above they add the contribution to the end balance at the end of each year… either is acceptable.

An example of correctly running the program in terms of input and output:




Your program should work either identical or nearly identical this example.

If the user enters a negative number in the case of any of the dollar figures, or 0 or a negative number in the case of the year, print an appropriate error message and ask the user to input the data again. Do not worry about any other kind of input validation (e.g. checking for int vs float or characters). Implement this input validation using a do-while loop for each input.

Here is an example handling issues with input, your program should behave identical or nearly identical to this:




<em>Question 2 – Geometry application – </em>

Create a program that presents the user with a menu that has options to:

<ol>

 <li>Compute the area of a square</li>

 <li>Compute the volume of a sphere</li>

 <li>Compute the surface area of a cube</li>

 <li>Quit</li>

</ol>

If the users selects option 4, the program should terminate.  If they select options 1, 2, or 3, the

program should ask the user to input the appropriate values needed to perform the computation (e.g. side length for a square, radius in the case of a sphere, etc.). The calculation should be carried out and the result should be presented to the user. Assume cm for all lengths. Do not worry about input validation, you can assume the user inputs a number in each case, and you should input and treat the numbers as doubles. Be sure to research how to use scanf to read a double value. Be careful when performing your calculations, make sure that what is output from your program is correct. <strong> </strong>

Use a do-while to present the menu to the user, and a switch statement to handle the menu choice selection and to carry out the desired computation by calling the appropriate function.  Create C functions to handle each computation… each function should take in any necessary measurement as an argument/parameter and return the correct computation. The function should not be responsible for asking for the necessary lengths, do this in your main function. All of these functions can be written in one line, they should not be very long at all.  For example, a triangle area function would look like:

Your program should run identically or near identically to this example:







<em> </em>


