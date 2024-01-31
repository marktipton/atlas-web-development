# CSS (Cascading Style Sheets)

- CSS is a style sheet language used for specifying the presentation of markup language such as HTML and XML. CSS was first proposed in 1994 and first released by the World Wide Web Consortium in 1996. CSS enables the separation of content (HTML) and presentation (CSS). This separation allows for more flexibility and control over webpage presentation.

- Style can be added internally to HTML style sheet using the style tag or externally using a link to a style sheet with a .css extension.

- The goal of this project is to add style to our existing HTML to match the appearance of a webpage in Figma.

- To achieve this, I added classes and id's to my html blocks so that they could be targeted more specifically. I used flexboxes for most of the elements on the page and added margins to align the elements more closely with those in the Figma page.

- This project was my second experience working with CSS and the 'cascading' part of CSS really clicked for me this time. I now understand that classes can and should be used anywhere elements need to have the same attributes. However, parts of the class can be overriden by selectors with a higher specificity value. The specificity value is made up of four parts which take precedence in order: ID selectors, class/attribute selectors, element selectors, and pseudo classes/pseudo-elements in the selector. Inline styling takes precedence over all other styles.