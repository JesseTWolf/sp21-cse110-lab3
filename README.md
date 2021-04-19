
Link to published site is https://jessetwolf.github.io/sp21-cse110-lab3/


# CSS Checklist
#### Below is a checklist to help me keep track what I have and haven't done so far. Included little tidbits of notes for future me to look back on. Descriptions found from original assignment, w3schools.com and developer.mozilla.org
---
1. General CSS Topics:

    - [x] Comment /* write down comments to make your css easier to read */

    - [x] Color                                               /* apply colors to your HTML elements */
        - [x] rgb(r, g, b) or rgba(r, g, b, a)     /* red, green, blue, alpha values */
        - [x] #FFF or #FFFFFF                    /* hex codes */
        - [x] hsl(h, s, l) or hsla(h, s, l, a)       /* hue, saturation, lightness, alpha values */
        - [x] Color name (i.e ‘orange’)

    - [x] Background     (Links to an external site.)/* apply background styles to your elements */
        - [x] background-color

    - [x] Unit (Links to an external site.)     /* units of measurement for sizing and spacing your elements */
        - [x] Use 3 unique relative units total
          - [x] em (Font size of the parent, in the case of typographical properties like font-size, and font size of the element itself, in the case of other properties like width.)
          - [ ] ex (x-height of the element's font.)
          - [ ] ch (The advance measure (width) of the glyph "0" of the element's font.)
          - [ ] rem (Font size of the root element.)
          - [ ] lh (Line height of the element.)
          - [x] vw (1% of the viewport's width.)
          - [x] vh (1% of the viewport's height.)
          - [ ] vmin (1% of the viewport's smaller dimension.)
          - [ ] vmax (1% of the viewport's larger dimension.)
        - [x] Use 3 unique absolute units total
          - [ ] cm (Centimeters)
          - [ ] mm (Millimeters)
          - [ ] Q (Quarter-millimeters)
          - [x] in (Inches)
          - [ ] pc (Picas)
          - [x] pt (Points)
          - [x] px (Pixels)

    - [x] Box Model (Links to an external site.)     /* configure the containers that holds your HTML content */
    (“long” and “short” refer to longhand and shorthand syntax and should give the same results. They’re simply different ways to declare your style rules, use at least one of each syntax) 

        - [x] Margin     /* spacing between html elements */
            - [x] Long (margin-top, margin-bottom, margin-left, margin-right)
            - [x] Short (margin: <top> <right> <bottom> <left>)
            - [x] Auto margins: margin: auto
     
        - [x] Padding     /* spacing within html elements */
            - [x] Long (padding-top, padding-bottom, padding-left, padding-right)
            - [x] Short (padding: <top> <right> <bottom> <left>)
     
        - [x] Borders (Links to an external site.)     /* borders around html elements, hint: apply borders before testing out padding and margin to better understand the difference between the two */
            - [x] border-style
            - [x] border-color
            - [x] border-width
            - [x] border-radius

    - [x] Text     /* style your text */
        - [x] color
        - [x] text-decoration
        - [x] text-align

    - [x] Display (Links to an external site.)
        - [x] Experiment with these values: none, block, inline-block, inline. Include at least two of them in your page.
        Apply theses values to the display property
    - [x] Sizing     /* set the height and width for an element */
        - [x] height / width
        - [x] max-width / min-width     /* add sizing constraints for responsive web pages */
    - [x] Position (Links to an external site.)     /* element positioning on the page */
        - [x] Experiment with these values: static, relative, fixed, absolute, sticky. Include at least two of them in your page.
        Apply these values to the position property
    - [x] Pseudo-class (Links to an external site.)     /* elements that exist in your document conditionally */
        - [x] :hover
        - [x] :active
    - [x] Layouts
            - [x] Flexbox (Links to an external site.)   /* allow your elements to lay themselves out automatically */
                apply flex to the display property
                Must have more than two children within the element that is using flexbox. Must use minimum three of the flexbox related attributes
            - [x] Grid  (Links to an external site.)        /* instantiate a grid for your layouts */
                apply grid to the display property
                Must have more than two children within the element that is using the grid. Must use a minimum of three of the grid related attributes
    - [x] Responsiveness       /* make your website friendly for multiple devices */
        - [x] At least one query based on the screen width
            - [x] Media Query (Links to an external site.)
    - [x] Fonts (Links to an external site.)       /* pick varying font styles to make your text fun to read */
        - [x] Include and use a 3rd party font (https://fonts.google.com/ (Links to an external site.)). You can load the font in either your HTML or your CSS
 
2. CSS Selectors (Links to an external site.)

CSS selectors allow you to select the HTML element you want to style. Each type of selector targets a different identifier on your HTML element. For this lab you must use at least one of every bulleted selector method.

  - [x] Class Selector (.class)
  - [x] ID Selector (#id)
  - [x] Universal Selector (*)
  - [x] Element Selector (element) 
  - [x] Attribute Selector (e.g. [attribute=foo])     
  - [x] Pseudo-class Selector (e.g. p::hover)
  - [x] Selector List (element, element)                   /* select multiple elements */
  - [x] Combinators (you must use one of each)    /* specify selections based on element positioning in the DOM tree */
      - [x] Descendant Combinator (element element)
      - [x] Child Combinator (element > element)
      - [x] General sibling combinator (element ~ element)
      - [x] Adjacent sibling combinator (element + element)
      - [x] Combining Two Selectors (element.class)