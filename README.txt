Introduction

The Website Optimization project for Udacity. Two parts of the application are to be given special attention. 
The main page(s), and the pizzeria page. A brief description of each file will be given.


Main page(s)
1)CSS-print.css/style.css: contains the css for the main page(s)
2)img:contains the images for the main page(s)
3)js-perfmatters:contains the javascript for the main page(s)
4)indx/project-2048/project-mobile/project-webperf:all the html for the main page(s)

Pizzeria page(in the view folder)
1)css-style/bootstrap-grid:contains the css for the pizzeria page
2)images:contains the images for the pizzeria page
3)js-main:constains the javascript for the pizzeria page
4)pizza:contains the html for the pizzeria page

To run a page open either the pizza or index html in the browser of your choice. 


Main page(s)(index.html/style.css/print.css)
10:minified and inlined style.css
11:rendered critical path of style.css, then minified and inlined
12:deleted font style
58:moved script from head to body
66:made script asynchronous
67:made script asynchronous
68:made script asynchronous

Pizzeria page
1:added the "use strict" directive
415:added query selector getElementById
435:added function determineDX
462:pulled var randomPizzas out of for loop and used specific query selector
534:moved scrollTop out of for loop. 
570:reduced scrolling pizzas from 200 to 35