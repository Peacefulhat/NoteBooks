- CSS is the language we use to style an HTML document.
- CSS describes how HTML elements should be displayed.
- CSS file contains properties.
#### How to link CSS file to an HTML file:
<h6><span style="color:#00ff00;">There are three ways of inserting a style sheet:</span></h6>
- External CSS
- Internal CSS
- Inline CSS
##### External CSS:
- With an external style sheet, you can change the look of an entire website by changing just one file.
- `<link>` tag is used to link this external CSS file.
- `<link rel="stylesheet" href="path/to/css/file">` 
- `rel`: attribute defines the relation between the files , what kind of file is the one we are trying to link. 
- `href`: is used to specify the file path.
#### Internal CSS:
- An internal style sheet may be used if one single HTML page has a unique style.
- The internal style is defined inside the `<style>` tag, inside the head section.
- `<style> css properties comes here </style>`

#### Inline CSS:
- An inline style may be used to apply a unique style for a single element.
- To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.
- `<p style="color:red;">This is a paragraph.</p>`

#### How to write CSS file:

##### Selector in CSS:
- is a way using which we can select an element/elements. 
- 