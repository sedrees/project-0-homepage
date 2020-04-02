# Project 0

Web Programming with Python and JavaScript

This is my personal homepage project from the original CS50 course, updated for CS50 Web. This has been updated to include bootstrap grid columns to satisfy the project requirement.

To create this page I have created a foundation using a tool called Compass(found at http://compass-style.org/). This allows you to initialize a web project with other technologies you select yourself, in this case I have elected to use Bootstrap and normalize.css. The most useful feature of Compass by far however is automatic SCSS preprocessing with real-time error notifications on your desktop. 

Project Files____________________________________

Javascripts
--- Bootstrap components

Sass
--- _base.css This is a SASS partial containing some base styles for the main file to pull from, including fonts and colors.
--- _bootstrap-variables.scss Bootstrap-made partial for their own purposes
--- styles.scss The bread-and-butter stylesheet which gets preprocessed to form the CSS file. This is where most of the work is done.

Stylesheets
--- styles.css This is the file that compass creates from the SCSS. It is not super human-readable but does provide some helpful diagnostic information if necessary.

HTMLS
The base folder contains four HTML files: index.html, about.html, contact.html and portfolio.html. These are the markup for all four website pages. 