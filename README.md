# Django Assignment

## Part 1:
* Create a Python virtual environment.
* Include the packages you need in the folder requirements_env.
* Build and install the packages.
* Create a Django project school.
* Create an app students.
* Implement a base.html template that displays "Stuyvesant High School".
* Create a view list_students. Define the following list of students in inside the view ["Paul Smith", "Peter Jackson", "Claire Brown", "Michel Jones"]. Add a cookie in this view. Cookie data: (key: "student_name", and for the value, you are randomly going to choose a student name from your list). Define a variable that contains the student name from the cookie from the request (not the one you are setting in the response, it must be the one from the request).
* Create a template for the view list_students, load the base template, display the names of the students (expecting a loop here), and display the value of the cookie student_name from the request. 
* Optional: If you have extra time, add a CSS file to change the color of the "Stuyvesant High School" text in the base.html template, and add an image to the template.
* Optional: Add a middleware that prints "hello I am a custom middleware in the request" and prints "hello I am a custom middleware in the response".

## Part 2:
- In the file commands.txt, you must write the commands you used to create the project, create the app, run server, and detail about the project development that you would like to include.

**DO NOT FORGET TO COMMIT AND PUSH YOUR WORK**

**DO NOT ADD THE PYTHON VIRTUAL ENV TO YOUR REPO**
