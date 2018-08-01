Work in Progress




name: Styling

description: Recipes, techniques and even more tips on how to enhance your CSS workflow.

sections:
  '0':
    - intro-css
    - css-basics
    - box-model
    - positioning
    - dimensioning-and-box-sizing
    - practical-css
    - typography
    - centring-recipes
    - colors-tips
    - positioning-tips
  '1':
    - styling-i
    - styling-ii
    - styling-iii
    - pseudo-classes-i
    - pseudo-classes-ii
    - pseudo-elements
  '2':
    - flexbox
    - features
    - recipes
    - responsive-design-tips
  '3':
    - sass-i
    - sass-ii
    - sass-iii
    - animations
    - css-animation

prerequisites:
  - web:html

standards:
  css-syntax:
    name: Identify and evaluate the syntax of CSS
    description: This standard deals with reading CSS, and identifying the component parts of the syntax.
    objectives:
      0: Identify the components of a CSS rule
      1: Distinguish cascading rules 
      2: Distinguish selectors from general to specific
      3: Identify the 3 ways of applying CSS to HTML
      4: Identify common CSS property/value pairs
      5: Identify common CSS measurements
      6: Identify and use commonly-held industry best practices
  css-box-model:
    name: CSS Box Model
    description: This standard covers how CSS is used to change the design of HTML elements.
    objectives:
      0: Identify the box properties of HTML elements
      1: Use CSS to add border styles to HTML elements 
      2: Use CSS to add margin space around HTML elements
      3: Use CSS to add padding space within HTML elements
      4: Use CSS to debug with the * selector
      5: Use CSS transparent border colors when working with hover state elements. (colors-tips/default-to-a-transparent-border-color-before-adding-a-border-to-on-hover-state-elements.md)
   css-basic-typography:  
    name: CSS Basic Typography
    description: This standard covers the common CSS rules related to typography.
    objectives:
      0: Use CSS to change the common type properties: color, alignment, font-size, and font-family
      1: Use Google Fonts to change the font  
      2: Distinguish potential fallbacks using font stacks
      3: Use CSS to change font style, font weight, text transform, text decoration, line height, letter spacing, text decoration, & text transform
  css-basic-colors:  
    name: CSS Basic Colors
    description: This standard covers the common methods of assigning color using CSS.
    objectives:
      0: Use hexadecimal color values to change colors in CSS.
      1: Use color name values to change colors in CSS
      2: Use RGB & RGBA values to change colors in CSS
      3: Use HSL & HSLA values to change colors in CSS
      4: Use currentColor to improve code reusability
  css-background-styles:  
    name: CSS Background Styles
    description: This standard covers using CSS to style backgrounds of HTML elements.
    objectives:
      0: Use CSS to change the background color of HTML elements
      1: Use CSS to assign a background image to HTML elements
      2: Use CSS to repeat images in the background of HTML elements
      3: Use CSS to set the position of a single image as the background of HTML elements
      4: Use CSS to set an image in a fixed position as the background of HTML elements
  css-basic-position:  
    name: CSS Basic Positioning
    description: This standard covers how CSS is used to position HTML elements.
    objectives:
      0: Distinguish the outcome between the three most common display properties: block, inline and inline-block
      1: Identify the default display properties of common HTML elements
      2: Use CSS to change the display properties of HTML elements using block, inline and inline-block
      3: Distinguish the outcome of these properties & values: display: none, visibility: hidden, & opacity: 0
      4: Use CSS to change the properites of HTML elements using  display: none, visibility: hidden, & opacity: 0
      5: Distinguish the outcome of these position properties: static, relative, absolute, fixed, & sticky
      6: Use CSS to change the position properties of HTML elements using static, relative, absolute, fixed, & sticky
  css-basic-layout:  
    name: CSS Basic Layouts
    description: This standard covers how CSS is used to layout HTML elements.
    objectives:
      0: Distinguish the differences between the past approaches & the modern standards for page layouts
      1: Use CSS to float HTML elements
      2: Use the clearfix technique with floating HTML elements when appropriate.
      3: Use CSS Flexbox to create rows & columns for HTML elements
      4: Use CSS Grid to create a simple grid template for HTML elements
  centering-recipes:  
    name: CSS Centering Recipes
    description: This standard covers how CSS is used to center HTML elements.
    objectives:
      0: Use CSS to horizontally center blocks of unknown width
      1: Use CSS to horizontally center blocks of known width
      2: Use CSS to vertically center blocks of unknown height
      3: Use CSS to vertically center blocks of known height
      4: Use CSS to vertically center anything
      5: Use CSS to vertically center text
      5: Use CSS to vertically center text & containers for older IE browsers

  css-tables:  
    name: CSS Tables
    description: This standard covers how CSS is used to style HTML tables.
    objectives:
      0: Use CSS to style borders within HTML tables
      1: Use CSS to style alternate rows within HTML tables
      2: Use CSS to control cellpadding and cellspacing within HTML tables
      3: Use CSS to keep a table's cells at equal width
     

== [1]

  css-style:  
    name: CSS Style 
    description: This standard covers how CSS is used to style ====
    objectives:
      0: Use CSS to change the border-radius of HTML elements.
      1: Use CSS to change the marker type in unordered lists
      2: Use CSS to change the transform (rotate, skew, & scale) properties of HTML elements
      3: Use 
     
   css-advanced-colors:  
    name: CSS Advanced Colors 
    description: This standard covers the advanced methods of assigning color using CSS.
    objectives:
      0: Use CSS to apply linear gradients to the background of HTML elements
      1: Use CSS to apply radial gradients to the background of HTML elements 
      2: Use CSS to apply multiple color stops to gradients
      3: Use CSS to apply transparent colors within gradients
      4: Use CSS to create repeating gradients
      5: Use CSS to change the shape (circle or ellipse) of radial gradients
      6: Use CSS to change the size of the gradient using closest-side, farthest-side, closest-corner, farthest-corner
      7: Use CSS to create conic gradients
  
  css-style-buttons:  
    name: CSS Style Buttons
    description: This standard covers how CSS is used to create better buttons.
    objectives:
      0: Use CSS to remove the underline of links
      1: Use CSS to change text link styles for all 4 states: link, visited, hover, & active

  css-pseudo-classes: 
    name: CSS Pseudo Classes
    description: This standard covers all of the Pseudo Classes within CSS.
    objectives:
      0: Use CSS to target an HTML element that is the first child of another element
      1: Use CSS to target an HTML element that is the last child of another element
      2: 
      
      Use CSS to change the HTML content based on the given language attribute

:not, nth-child , :required and :optional pseudo classes

== [2]

  css-flexbox:  
    name: CSS Flexbox
    description: This standard covers how CSS is used to create and control FlexBox layouts.
    objectives:
      0: Use CSS to change the direction of flex items in both rows and columns
      1: Use CSS to change how flex items display on single line or wrap onto multiple lines
      2: Use CSS to change how flex items are aligned & justified
      3: Use CSS to change the order of the flex items
      4: Use CSS to change the size of the flex item to grow and/or shrink
      5: Use CSS to override default alignment of individual flex items

  css-random???: 
    name: CSS Random???
    description: This standard covers random CSS styles.
    objectives:
      0: Use CSS to make text in a web page unselectable.
      1: Use CSS to change the horizontal radius different from the vertical radius of the border-radius 
      2: Use CSS to create multiple borders on HTML element with pseudo elements
      3: Use CSS to change the style of any HTML element when the user hovers over it

  css-form-styles: 
    name: CSS Form Styles
    description: This standard covers how to use CSS to style HTML forms.
    objectives:
      0: Use CSS to disable the resizing behavior of textarea elements.



      To disable the resizing behavior of textarea elements
      
  css-image-filters:  
    name: CSS Image Filters
    description: This standard covers how CSS is used to apply filters on images.
    objectives:
      0: Use CSS to apply single or multiple filters on images with appropriate browser support
      1: Use CSS to apply grayscale filter on images
      2: Use CSS to apply sepia filter on images
      3: Use CSS to apply saturate filter on images
      4: Use CSS to apply hue-rotate filter on images
      5: Use CSS to apply invert filter on images
      6: Use CSS to apply opacity filter on images
      7: Use CSS to apply brightness filter on images
      8: Use CSS to apply contrast filter on images
      9: Use CSS to apply blur filter on images
      10: Use CSS to apply drop-shadow filter on images
  
  
  
  
  css-animations:  
    name: CSS Animations
    description: This standard covers how CSS is used to create animations.
    objectives:
      0: Use CSS to animate filters on images
    
  
  

   




/* 
NOTE: The workout "centering-recipes" is mispelled in MASTER 


http://web.simmons.edu/~grabiner/comm244/weekthree/css-basic-properties.html

Image Filters
https://css-tricks.com/almanac/properties/f/filter/
https://codepen.io/shoutmatt/pen/VBXXeq

Add to [1]: Style text links as buttons https://css-tricks.com/css-basics-styling-links-like-boss/
            Change cursor with links https://css-tricks.com/css-basics-styling-links-like-boss/

Add to [2]: Flexbox, CSS Grid, Advanced Measurements: VH & HW
            practical-css/Difference between initial and inherit


Add to [?] PRINTING section: practical-css/page-breaks-for-printing.md


NOTE: Move /css-basics/will-this-work-on-ie8.md later in the lessons 



*/
