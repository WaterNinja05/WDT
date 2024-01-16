# The display Property

The display property specifies if/how an element is displayed.

Every HTML element has a default display value depending on what type of element it is. The default display value for most elements is `block` or `inline`.

## Block-level Elements
A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can).

Examples of block-level elements:

`<div>` - The `<div>` tag defines a division or a section in an HTML document.<br> 
`<h1> - <h6>` <br>
`<p>` <br>
`<form>`<br>
`<header>` <br>
`<footer>`<br>
`<section>`<br>


## Inline Elements
An inline element does not start on a new line and only takes up as much width as necessary.

Examples of inline elements:

`<span>`
`<a>`
`<img>`


## Activity 1
In the file `1.display.html`;
1. Change the default behavior of block and inline elements.
2. Try to change the `width` of an inline and block element.
3. Try to use `display:none` and `visibility:hidden` to any of the elements. What did happen?

**Some Use Cases**: `display:none`: hiding a popup, a todo list item on the UI that has been checked, or the sidebar in a page. `visibility:hidden`: display some animation while you "hide" or "show" an element.
Link: https://www.freecodecamp.org/news/css-display-none-and-visibility-hidden-the-difference/


# The position Property
The position property specifies the type of positioning method used for an element.

There are five different position values:

`static`  -- HTML elements are positioned static by default.<br>
`relative` -- An element with position: relative; is positioned relative to its normal position.<br>
`fixed` -- An element with position: fixed; is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled.<br>
`absolute` -- An element with position: absolute; is positioned relative to the nearest positioned ancestor<br>
`sticky` -- An element with position: sticky; is positioned based on the user's scroll position.<br>

Check out this link: https://www.w3schools.com/css/css_positioning.asp

## Activity 2
1. Open the `2.Relative_positioning.html` file and add `position:relative` to the top red div. Now push that div to `20px` from the left using `left: 20px;` and observe what happens.
2. Restore its original position. Now push it `200px` to the right (`right: 200px;`). What did you see?
3. Restore its original position. Now push it `30px` from the top.
4. Restore its original position. Now try to add `display:inline` to each of these elements.  Did you see anything? Can you explain why? [HINT: width <> block]
5. Now change the display position to `inline-block` and move the red square to the right of the other two elements.


# Absolute Positioning
An element with position: absolute; is positioned relative to the nearest positioned ancestor. 

However; if an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling.

Note: Absolute positioned elements are removed from the normal flow, and can overlap elements.


## Activity 2

Open the `3.Absolute_positioning` and add `position:absolute` to the blue square. Now add `left: 100px`. What did you see? Can you explain what has happened?





