* BEM will be used as the naming covention for the properties of the components.
e.g 

## Block 
.btn {
    /* Styles for btn goes here */
}

The block represents a standalone component or a significant part of the interface. We should use it in several different places. 


## Element
.btn__text{
    /* Styles for the text within the button goes here */
}

An element is a part of a block and can have its own styling. Double underscore ( __ ) is used to separate the block name and element name.

## Modifier
.btn--primary  {
    /* Styles for the primary state of the btn block element goes here */
}

An modifier element represents the variation or different state of a block or an element. 
Double hypen ('--') is used to separate the block element and its modifier name.

More examples,

.container {
    /* Style for Header element goes here */
}

.container__text{
    /* Styles for the text within the text goes here */
}

.container--large{
    /* Styles for container that takes the entire width of the screen */
}

Tutorials
https://www.youtube.com/watch?v=xaXmoVZ3koo

https://www.youtube.com/watch?v=SLjHSVwXYq4