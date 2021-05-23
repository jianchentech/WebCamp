# Design of a dynamic website
## **The code and website design must be original and not plagiarized**

You need to design a website for a caterer offering meals in secondary schools.
The site must offer the following functionalities:
```
• Home page;
• An "Information" section which describes the catering services;
• A "Contact" section which indicates the contact details of the caterer;
• An "Order" section which allows a parent to order meals for their child.
The order must present a form allowing the following data to be entered:
• The full name of the parent;
• The full name of the child;
• The child's school;
• The child's age;
• Choice of meal for the 5 days of the school week.
```
For each day of the week, the caterer offers 2 choices of dishes for the children. A photo must
illustrate each choice with a textual description of the dish and ingredients.
The form will be sent to the web server, which will perform data validation. A page
error should be displayed to the user if the entered data is invalid. A page of
confirmation, describing the complete order, should be displayed to the user if the order has
well treated by the server. Here are the validations to perform (all validations must be
made by the server):
```
• Parent's name, child's name, school and child's age are not blank;
• Commas are not allowed in parent's name, child's name, and child's name.
school;
• The child's age is a positive integer between 4 and 12 inclusive;
• A choice of meals must be made for each day of the week (it is assumed that children
are always present at school).
```
When a command is valid, the server must add it to a text file stored on the server.
The file should have the following format (each line corresponds to a command - imagine
that the following example is only on one line):
Parent: Jacques Berger, Child: Junior Berger, Age: 5, School: St-Etienne,
Monday: Spaghetti, Tuesday: Quinoa salad, Wednesday: Meatloaf, Thursday: Lasagna,
Friday: Cheese Cannelloni
You are not required to handle character encoding errors in the text file. However,
it would be appreciated if the text file was encoded in UTF-8.
Your website must meet the following requirements:
```
• The HTML version must be HTML 5;
• The CSS version must be CSS 3. • the server side must be PHP 7;
• HTML documents must be valid;
• Style sheets must be valid;
• The site must be free of character encoding errors;
• The site must be in French;
• The site must be presentable and functional with Google Chrome and Firefox;
• The site must use the POST-REDIRECT-GET template.
It is not allowed to use an existing CSS template. You can consult it, you
inspire but it is not allowed to use one.
The source code must meet the following requirements:
• the CSS must be in one (or more) separate file;
• no library or framework is allowed;
• no javascript is allowed;
• the code must be indented correctly;
• the names of elements, classes, identifiers, CSS properties must be in lowercase;
• the source files must be encoded in utf-8.
```