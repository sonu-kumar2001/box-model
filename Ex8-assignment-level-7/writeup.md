# Introduction

We know bettr about HTML elements and how they provide a simple structure to a page.It's time to go a bit deeper and see how the elements are exactly displayed on a page.

## Display properties

How elements are displayed, either block or inline or something else is determined by the display property. Every element has a default display property value. The common value for display property is block, inline, inline-block, and none.  
However, the element's default display property can be written. A block can be displayed as inline or an inline can be displayed as a block-level element.so we can overwrite the display properties.

## The Box-Model

According to the box model,every element is a rectangular box on a page and it may have some width, height, padding, borders, and margins.Which is basically not visible on our page but we can see that in our chrome developer by hovering on any elements on the page.

**The four important properties of box models are**
- content:-Its dimensions are basically the width and the height.Every element has some default width based on the display property. If it is a block-level element it will have 100% width covering whole horizontal space. If it is an inline or inline-block element it will have width according to the content it wraps.As every element has some default width in a similar way every element also has some default height and that is always determined by its content.

- Padding:-Padding comes after width and height, falls inside the element's border. For example,  
`padding: 20px;`  
This will provide padding all around the element  
Or We can give padding to only one side of the box, for example,  
`padding-right: 10px;`  
Besides, there are options for shorthand writing, which allow you to give a different value to each side  
`padding: 10px 20px 5px 15px; `

- Borders:-The border is to provide some outline around an element.  
The three basic properties for creating borders are:  
  - Border-style :- mostly used with the keywords like solid, dashed or dotted.  
  div{
      border-style: solid;
  }
  - Border-width :- Tells the browser about the size of the border. Usually, we use pixel value for this property, for example,  
   div {
    border-width: 10px;
  }
  - Border-color:- by default, the value uses the currentColor of the text. However, we prefer to define it even if we don’t have to. For example,  
  div{
      border-color: red;
  }  
  Or we can use the shorthand value like
  div{
      border: 10px solid red;
  }

- margin:-The last property in the box model is the margin. The margin property is very similar to padding. But instead of applying inside the element, it sets the space that surrounds outside the element.  



