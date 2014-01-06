diag-btn is a CSS snippet that makes it easy to embed diagonal buttons or groups of diagonal buttons in a web page to improve mobile UIs.

Why use diagonal buttons?  For most mobile viewers, the thumb is used to browse and navigate the web.  Because the thumb moves in a radial motion, it's often easier for users to navigate via diagonally-placed UI controls.

It supports individual buttons and stacked buttons up side-by-side.  To use, embed the stylesheet and wrap the buttons in a class called "diag-btn".

Example:

    <link rel="stylesheet" href="css/diag-btn.css">


Now add one or more buttons wrapped in a div with the "diag-btn" class.

Example:

    <div class="diag-btn">
      <input type="submit" class="diag-btn"  value="OK">
      <input type="submit" class="diag-btn" value="Cancel">
    </div>
 
For lefthanded support add `class="left-handed"` to the body tag.

For more examples, see http://jsfiddle.net/maxk42/G7qLd/
 

