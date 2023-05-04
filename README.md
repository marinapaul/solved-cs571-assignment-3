Download Link: https://assignmentchef.com/product/solved-cs571-assignment-3
<br>
In this assignment, you will implement a postfix calculator that computes the value of postfix expressions using Javascript and HTML.  The interface of the calculator is given below. Your calculator should have the same layout, i.e.. the first line shows buttons on off 0 1, the 2<sup>nd</sup> line shows buttons 2 3 4 5, etc.

Your calculator needs to handle only single-digit integers in the postfix expression. For example, 12+ represents 1+2 and 123+- represents 1-(2+3). There will be no space between single-digit integers.

Initially, the calculator is off.  When the calculator is off, the calculator does not display anything until the user clicks the “on” button.

When the user clicks the “on” button, the calculator displays 0. When the user clicks the “off” button, the calculator erases the display.

If the calculator is on and the user clicks the button 0-9, +, -, *, or /, then the calculator displays the symbol on each button.

If the calculator is on and the user clicks “clear”, then the calculator displays 0.

If the calculator is on and the user clicks button =, then the calculator evaluates the expression entered by the user and displays the result.

You can assume that the arithmetic expression entered is always valid.  For example, you do not need to consider invalid inputs such as 1+,  12+*, etc.

Hint: you can use a stack to implement the postfix calculator. Javascript provides function push to add an element to the stack and function pop to remove an element from the stack.




<strong><u>Examples</u></strong>




<ol>

 <li>The calculator is off and the user clicks 1</li>

</ol>

The calculator does not display anything




<ol start="2">

 <li>The user clicks “on”</li>

</ol>

The calculator displays 0




<ol start="2">

 <li>The calculator is on and the user clicks “1”, “3”, “+”, and “=”</li>

</ol>

The calculator displays “13+” before the user clicks “=”

After the user clicks “=”, the calculator displays 4




<ol start="3">

 <li>The calculator is on and the user clicks “clear”, 1”, “2”, “3”, “+”, “-“, and “=”</li>

</ol>

The calculator displays 0 when “clear” is clicked

The calculator then displays “123+-“ before “=” is clicked. After the user clicks “=”, the calculator displays -4




<ol start="4">

 <li>The user clicks “off” and “1”</li>

</ol>

The calculator erases the display and displays nothing when the user clicks “1”




<ol start="5">

 <li>The calculator is turned on and the user clicks “1”, “3”, “+”, “=”, “clear”, and “5”</li>

</ol>

Before the user clicks “=”, the calculator displays 13+ After the user clicks “=”, the calculator displays 4

After the user clicks “clear”, the calculator displays 0

After the user clicks “5”, the calculator displays 5




<ol start="6">

 <li>The calculator is on and the user clicks “1”, “3”, “+”, “=”,  “5”, “-“ and “=”</li>

</ol>

Before the user clicks “=”, the calculator displays 13+ After the user clicks “=”, the calculator displays 4

After the user clicks “5”, the calculator displays 45

After the user clicks “-“, the calculator displays 45-

After the user clicks the 2<sup>nd</sup> “=”, the calculator displays -1


