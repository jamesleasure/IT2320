## IT 2320 – Lab 2

In this lab, we’ll write our first JavaScript application. 

*Instructions:*  
1.	Create a folder called Lab02 in the root of your class repository – IT2320[FirstInitial][LastName]/Lab02.  Note: you can create the folder and files using Visual Studio Code.  
2.	Create an HTML file called Lab02.html. Add a header to the page that says “Grocery Shopping Cost Calculator”. You can use the following code (from Murach) as an example:
```
<html>   
<head>    
<title>Average Test Scores</title>   
<script>  
var entry;   
var average;   
var total = 0;  

//get 3 scores from user and add them together 
// entry 1:  
entry = prompt("Enter test score");   
entry = parseInt(entry);   
var score1 = entry;   
total = total + score1;  

// entry 2:  
entry = prompt("Enter test score");   
entry = parseInt(entry);   
var score2 = entry;    
total = total + score2;  

// entry 3:  
entry = prompt("Enter test score");   
entry = parseInt(entry);   
var score3 = entry;   
total = total + score3;   

//calculate the average   
average = parseInt(total/3);  
  
</script>  
</head>   
<body>   
<script>  
// Ouptut the scores:  
document.write("<h1>The Test Scores App</h1>");  
document.write("Score 1 = " + score1 + "<br>" + "Score 2 = " + score2 + "<br>" + "Score 3 = " + score3 + "<br><br>" + "Average score = " + average + "<br><br>");  
</script>   
Thanks for using the Test Scores application!  
</body>   
</html>    
```   
3. Instead of text scores, our page will ask users to input grocery items and costs. Prompt the user for 3 grocery items (this is the name of the item). Store these values in JavaScript variables item1, item2, and item3.   
4. In addition to the items, ask the user for the cost of each item. Store these in variables cost1, cost2, and cost3. You will need to parse these values into numberic types.   
5. Calculate a total cost from the 3 cost variables. Store the value in a variable called costTotal. 
6. Calculate a tax amount from total cost. Assume the tax amount is 7%. Store this in a variable called costTax.
7. Create a variable called costTotalWithTax. This should be costTotal + costTax.
8. Use document.write statements to output the following values. Note: see the example how they output each test score and the average. *Try to format it nicely so it appears like a receipt. You could add a fun fictitious name for the grocery store.*     
    1. each item with its cost,  
    2. the total before taxes,   
    3. total amount of tax, and   
    4. total with tax.   
9. Make sure all of your files are saved. Then Commit and Push your new folder and files to github. It would be a good idea to visit github.com to make sure all of the changes were successfully pushed.
10.	In Blackboard, submit the path to your github repository folder.  Please do not upload any files.


