# Class 5 Notes

CSS
 Stands for (Cascading Style Sheets) 
Rule based language.
Uses {} brackets

Using CSS, you can control exactly how HTML elements look in the browser, presenting your markup using whatever design you like.

CSS can be used for very basic document text styling like changing the color and size of headings and links. It can be used to create a layout and you can specify how you want that layout to be and can even be used for animation.

Multiple declaration can be made in the same bracket to determine things such as color, font size, and placement.

element —-> h1 {
  Property -—>color: red; <——value
  font-size: 5em;
}

CSS color values can be represented in hex#, rgb value, rgba value, hsl, and hsla. Must match same format as below. Exception is hex#. It can be 3 characters instead of 6.
{color: #92a8d1;}
{color: rgb(201, 76, 76);}
{color: rgba(201, 76, 76, 0.6);}
{color: hsl(89, 43%, 51%);}
{color: hsla(89, 43%, 51%, 0.6);}