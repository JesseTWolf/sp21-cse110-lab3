

# Part 1. Intro to HTML
#### Below is a sort of checklist to help me keep track what I have and haven't done so far. Included little tidbits of notes for future me to look back on. Descriptions found from provided sites as well as w3schools.com.
---
## Document metadata
- [x] title (Title of page that will show up within the tab.)
- [x] meta (Metadata that will not be shown to user but instead given to the browser.)
- [x] link (usually <link> is used to link a stylesheet, but since we're not using CSS, you can use it to link a favicon instead. The favicon is the image that is seen within the tab next to the title of the page)
 
## Content sectioning
- [x] main (Signifies the main content of the document. The content inside should be unique and not repeated elsewhere or within)
- [x] header, footer
- [x] nav (Defines a set of navigation links. Is intended only for major block of navigation links)
- [x] h1, h2, h3 (Represents headings. h1 being the most important, going down in importance from there.)
- [x] section (defines a section in a document)

## Text content
- [x] div, span (div defines a division and is usually used as a container for HTML elements which is then styled with CSS. Span is an inline container used to mark up a part of a text, or a part of a document. Div is a block level element while span is an inline element.)
- [x] hr (Used to define thematic changes in the content. Usually displayed as a horizontal line.) 
- [x] p (Defines a paragraph of text)
- [x] ul (Defines an unordered list, aka bullet list)
- [x] ol (Defines an ordered list, the list will be marked with numbers by default. Types can be changed however via the type attribute.)
- [x] li (Defines a list item, this is used within either a ul or ol element as an item of the corresponding list.)

## Inline text semantics
- [x] b (Specifies bold text and according to documentation should be used as a last resort and when no extra emphasis is required.)
- [x] strong (Defines text with strong importance. The content is typically displayed in bold. If what you are trying to bolden does not need any extra importance then use the b tag instead.)
- [x] i (Specifies text that you want italicized, something in an alternate voice or mood, a technical term, a phrase from another language, a thought, a ship name, etc. Should only be used when there is not a more appropriate semantic element. )
- [x] em (Defines emphasized text. The content is usually italicized.)
- [x] a (Defines a hyperlink, which is used to link from one page to another. The href attribute will be what the link actually is and due to this is incredibly important to include.)
- [x] br (Is used as a single line break between elements. Something to note is that this is a single tag, no closing tag goes along with this one.)
 
## Images and multimedia
- [x] img ("Embeds" an image within an HTML page. Two attributes for this one that are basically required: src - specifies the path to the image and alt - specifies alternate text, text that will be displayed if the image is not reachable.)
- [x] audio (Adds audio controls, like play, pause, and volume. The source element is embedded within this audio element and is where the audio file itself is specified.)
- [x] video (Is used to show a video on a web page. Video tag has a few attributes that are important: controls - which adds in the controls, width and height, which are self explanatory. Just like the audio tag the actual file is linked via the source tag within this video element.)

## Interactive Elements
- [x] details (Specifies additional details that the user can open and close on demand. Really any content can be put within this element.)
- [x] summary (Defines a visible heading for the details element. The heading can be clicked to view/hide the details.)

## Forms
- [ ] form (Used to create an HTML form for user input. Can contain one or more of the following elements: input, textarea, button, select, option, optgroup, fieldset, label, and output)
- [ ] fieldset (Used to group related elements in a form. Draws a box around said related elements.)
- [ ] input (Specifies an input field where the user can enter data. Can be displayed in multiple ways depening on the type of the attribute.)
  - [ ] checkbox 
  - [ ] radio
  - [ ] text
  - [ ] date
- [ ] textarea (Defines a multi-line text input control. Is often used in a form to collect user inputs like comments or reviews.)
- [ ] datalist (Specifies a list of predefined options for an input element.)
- [ ] select (Used to create a drop-down list.)
- [ ] option (Defines an option in a select list. Option elements go inside a select, optgroup, or datalist element.)
- [ ] button (Defines a clickable button. You can embed a lot of different tags within the button itself.)

*You need to have at least one input of each type specified. 