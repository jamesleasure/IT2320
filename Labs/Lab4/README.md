## IT 2320 – Lab 4

In this lab, we'll practice using JavaScript functions.

*Instructions:*  
1.	Create a folder called Lab04 in the root of your class repository – Lab04.  Note: you can create the folder and files using Visual Studio Code.  
2. Copy the HTML file Lab4.html to your repository. Note: you can click on "Raw" to view the HTML contents if you want to copy the HTML itself. 
3. Modify the HTML to create a working calculator using the following requirements:
     1. Create 2 global page variables: operand1 and operand2.
     2. Add an event to both html elements operand1 and operand2 that updates the value of the variables from the html elements' values. Note: they should be string values. We will convert them to numeric values inside of functions.
     3. Create functions and attach them to the events for the buttons on the page for add(), subtract(), multiple(), and divide. In these functions:
          1. Convert the values of operand1 and operand2 to numeric values, compute the arithmetic operation, and populate the result element with the result. 
          2. Clear the values of operand1 and operand2.
          3. Write a string version of the operation into the html span with id="operation". For example, an addition operation should read something like Result: 3 + 4 = 7. Still place the result "7" into the input element with id="result".
     4. Detect invalid inputs for operand1 and operand 2. Add a span element or multiple span elements and output any errors to inform the user of invalid input. Change the font to color red any errors that are presented.
4. When complete, push your code to GitHub. Again, it's a good idea to log into github.com to make sure your changes were successfully pushed/uploaded. Submit a link to your Lab04 folder in Blackboard.