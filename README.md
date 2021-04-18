
Link to published site is https://jessetwolf.github.io/sp21-cse110-lab3/


# CSS Checklist
#### Below is a checklist to help me keep track what I have and haven't done so far. Included little tidbits of notes for future me to look back on. Descriptions found from w3schools.com and developer.mozilla.org
---
1. General CSS Topics:

    - [ ] Comment /* write down comments to make your css easier to read */

    - [ ] Color                                               /* apply colors to your HTML elements */
        - [ ] rgb(r, g, b) or rgba(r, g, b, a)     /* red, green, blue, alpha values */
        - [ ] #FFF or #FFFFFF                    /* hex codes */
        - [ ] hsl(h, s, l) or hsla(h, s, l, a)       /* hue, saturation, lightness, alpha values */
        - [ ] Color name (i.e ‘orange’)

    - [ ] Background     (Links to an external site.)/* apply background styles to your elements */
        - [ ] background-color

    - [ ] Unit (Links to an external site.)     /* units of measurement for sizing and spacing your elements */
        - [ ] Use 3 unique relative units total
        - [ ] Use 3 unique absolute units total

    - [ ] Box Model (Links to an external site.)     /* configure the containers that holds your HTML content */
    (“long” and “short” refer to longhand and shorthand syntax and should give the same results. They’re simply different ways to declare your style rules, use at least one of each syntax) 

        - [ ] Margin     /* spacing between html elements */
            - [ ] Long (margin-top, margin-bottom, margin-left, margin-right)
            - [ ] Short (margin: <top> <right> <bottom> <left>)
            - [ ] Auto margins: margin: auto
     
        - [ ] Padding     /* spacing within html elements */
            - [ ] Long (padding-top, padding-bottom, padding-left, padding-right)
            - [ ] Short (padding: <top> <right> <bottom> <left>)
     
        - [ ] Borders (Links to an external site.)     /* borders around html elements, hint: apply borders before testing out padding and margin to better understand the difference between the two */
            - [ ] border-style
            - [ ] border-color
            - [ ] border-width
            - [ ] border-radius

    - [ ] Text     /* style your text */
        - [ ] color
        - [ ] text-decoration
        - [ ] text-align

    - [ ] Display (Links to an external site.)
        - [ ] Experiment with these values: none, block, inline-block, inline. Include at least two of them in your page.
        Apply theses values to the display property
    - [ ] Sizing     /* set the height and width for an element */
        - [ ] height / width
        - [ ] max-width / min-width     /* add sizing constraints for responsive web pages */
    - [ ] Position (Links to an external site.)     /* element positioning on the page */
        - [ ] Experiment with these values: static, relative, fixed, absolute, sticky. Include at least two of them in your page.
        Apply these values to the position property
    - [ ] Pseudo-class (Links to an external site.)     /* elements that exist in your document conditionally */
        - [ ] :hover
        - [ ] :active
    - [ ] Layouts
            - [ ] Flexbox (Links to an external site.)   /* allow your elements to lay themselves out automatically */
                apply flex to the display property
                Must have more than two children within the element that is using flexbox. Must use minimum three of the flexbox related attributes
            - [ ] Grid  (Links to an external site.)        /* instantiate a grid for your layouts */
                apply grid to the display property
                Must have more than two children within the element that is using the grid. Must use a minimum of three of the grid related attributes
    - [ ] Responsiveness       /* make your website friendly for multiple devices */
        - [ ] At least one query based on the screen width
            - [ ] Media Query (Links to an external site.)
    - [ ] Fonts (Links to an external site.)       /* pick varying font styles to make your text fun to read */
        - [ ] Include and use a 3rd party font (https://fonts.google.com/ (Links to an external site.)). You can load the font in either your HTML or your CSS
 
2. CSS Selectors (Links to an external site.)

CSS selectors allow you to select the HTML element you want to style. Each type of selector targets a different identifier on your HTML element. For this lab you must use at least one of every bulleted selector method.

  - [ ] Class Selector (.class)
  - [ ] ID Selector (#id)
  - [ ] Universal Selector (*)
  - [ ] Element Selector (element) 
  - [ ] Attribute Selector (e.g. [attribute=foo])     
  - [ ] Pseudo-class Selector (e.g. p::hover)
  - [ ] Selector List (element, element)                   /* select multiple elements */
  - [ ] Combinators (you must use one of each)    /* specify selections based on element positioning in the DOM tree */
      - [ ] Descendant Combinator (element element)
      - [ ] Child Combinator (element > element)
      - [ ] General sibling combinator (element ~ element)
      - [ ] Adjacent sibling combinator (element + element)
      - [ ] Combining Two Selectors (element.class)