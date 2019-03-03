## IT 2320 – Lab 8

In this lab, we'll practice using jQuery for the first time.

*Instructions:* 
1. Copy Lab8.html to your local repository.
2. Add jQuery included a CDN to the header section of the page.
3. Modify the window.onload event, so that it uses jQuery’s $(document).ready event (1 point).
4. In the window.onload event, there is a line of code that adds a copyright statement to the bottom of the page.  Modify this, so that it uses jQuery’s .text() method as opposed to assigning a value to the JavaScript innerHTML property (2 points).
5. Add a hover event that will highlight the background of each li in the programs list when a user hovers over the li.  It should highlight upon the mouse hovering over the item.  The highlighting should disappear when the mouse leaves the li.  You will need to add a handler for the hover event.  In the function for the hover event, use addClass(className) and removeClass() inside of the hover event (4 points).
6. Add a click event, so that the programs div is hidden when you click on the degreeHeader element (4 points).
7. Similarly, add a click event, so that the programs div is hidden when you click on the certificatesHeader element (4 points).
8. When done, push your file to your repository and submit a link using the Blackboard drop box.