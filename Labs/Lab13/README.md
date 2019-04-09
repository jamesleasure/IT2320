## IT 2320 – Lab 13

In this lab, we try out browser objects, cookies, and web storage. Please create all of your file in a folder called Lab13 in your repository.

### Directions   
1. Create an html page called page1.html (add it to the Lab13 folder like all files in this lab).
     1. Display the location (or URL) on page1.html.
     2. Add button that says "Go to Page 2". When the user clicks on the button, use the location object to load page2.html.
2. Create a file called page2.html.
     1. Add a button labeled "Go Back". When the user clicks on "Go Back" use the history object to go back to page1.html.
3. Add a function to page1.html and page2.html that is called whenever the page is loaded. Create a cookie that stores how many times the user has loaded page1.html and page2.html separately. You could call the cookies page1HitCount and page2HitCount. Display the values on both pages using getCookieByName().