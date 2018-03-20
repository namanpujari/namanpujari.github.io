What I have learned today (3/15/2018)
-------------------------------------

1. Sass is a compiler for .sass and .scss files. Essentially, these compilable languages that output .css files. You can structure .scss files like any ordinary compiled language, and once sass does its job, a nicely structured .css file is returned to the programmer. 
2. Bootstrap uses sass on its .scss files. If we used node npm to install the source files of bootstrap, then we can see that the repositor contains a lot of .scss files. 
3. Bootstrap allows for the use of 12 columns in its grid system. Essentially, a grid system is the graphic designer's way of organizing the details of a webpage in an appealing manner. 

What I have learned today (3/19/2018)
-------------------------------------

1. Don't try to use the bootstrap elements (columns and containers, and such) to complete the layout of the design. Use flexbox and its capabilities to style the website usingt the custom styles.css file. 
2. `<div>` doesn't represent anything. It just allows for the customization (using css) of the items that fall under it. We can categorize blocks by wrapping it with `<div>`, and, say give it a particular background color. 
3. To stack navbars we can use flexbox to align them like a column (in the template example). Flexbox can also align singular items (like a column in bootstrap) at the center of the page without having to use the naive way of manually putting invisible columns to the right and left of a column that has to be centered. 
4. Fonts are made available by the imports in the `<head>` section. You can call them in the styles.css file under the font-family category. 
!. I still don't understand what is going on in the resume.js file. From what I can tell, it is smoothing down scrolling (possible to make the user experience more fluid and seamless?)