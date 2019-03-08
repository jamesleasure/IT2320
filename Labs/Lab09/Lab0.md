## IT 2320 – Lab 09

In this lab, we'll use forms and form validation.

Directions :
Download and open the attached file - Lab09.html.  Keep a separate copy of the file because you’ll use this file as a starting point for lab 09 for each part of the lab.

#Part 1 – HTML5
1.	Copy the attached Lab09.html file to Lab09-HTMLValidate.html
2.	Add an autofocus attribute to your form, so that it focuses on First Name when the page loads.
3.	Add another input text box with id=“phone”, name=“phone”.  Use the appropriate HTML5 data control for phone numbers.  Display the following Placeholder value “Mobile Phone (999-999-9999)” prior to the user entering text into the control. 
4.	Use HTML5 data validation attributes to validate the phone number.  Ensure that the user enters a pattern similar to 999-999-9999.  Display the tooltip “Must be formatted as 999-999-9999”
5.	Use HTML5 data validation attributes to make every field required.
6.	Save Lab09-HTMLValidate.html and make sure it is pushed to your remote repository.

#Part 2: JavaScript Validation
1.	Copy the original Lab09.html to Lab09-JSValidate.html (make sure it’s the original file and not the one you modified for part 1).
2.	Add a JavaScript function called validateForm(). 
3.	Add an onsubmit attribute to signupform (the form we added in step 1).  Return validateForm() in the onsubmit attribute.
4.	Add a checkbox above the Sign Up button.  Name the checkbox agree and display text after the checkbox “Check this box to agree to nothing”. 
5.	In validateForm(), make sure the user has checked the checkbox called agree.  Only allow the submit to occur if the checkbox is checked.
6.	In validateForm(), make sure the user has entered values for first name, last name, and email.  Note: you only need to make sure a value has been entered…no need to check for a pattern.
7.	Make sure your Lab09-JSValidate.html file is pushed to your remote repository.

#Part 3: JQuery Validation
1.	Copy Lab09-JSValidate.html to Lab09-jQueryValidate.html.  Keep the changes you made in Part 2.
2.	Modify the file, so that it uses jQuery (not the jQuery Validate Plug-In).  You will need to 1) remove the onsubmit attribute, 2) add the jQuery CDNs, 3) add document.ready, 4) create a function for the form submit, and 5) modify validateForm() so it uses jQuery syntax and event.preventDefault().
3.	Make sure Lab09-jQueryValidate.html is pushed to your remote repository.


#Deliverables – make sure the following files are successfully pushed to your remote git repository:
1.	Part 1 - Lab09-HTMLValidate.html 
2.	Part 2 - Lab09-JSValidate.html
3.	Part 3 - Lab09-jQueryValidate.html

Check your repositories at www.github.com to make sure the files were pushed successfully!
