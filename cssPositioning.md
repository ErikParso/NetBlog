**Fixed positioning**

Fixes the position of an element relative to the browser window. Element stays fixed in place even when scrolling. Usually applies on menus.. 

**Absolute positioning**

Takes an element out of document flow, browser acts like if the element has no width and height and other elements moves up. The position of the element is then fixed relative to the top level container or the closest parent with specified position.

**Relative positioning**

Sets the position of an element relative to its original position. The element's original width and height is retained in document flow and other elements behave as it was in original position.

**Static, inherited and z-index positioning**

Static positioning is default behavior of elements. Top, bottom.. does not affect element position.  
Inherited position tells an element to inherit its positioning from its parent element.  
Z-index controls the vertical stacking order of elements. Elements must have a set positioning for z-index to work.

<hr/>

**Floating elements**

Floating left(right) removes an element from document flow. It takes element and pushes it to the far left(right) possible. Other elements will move up as far as possible to flow around the element and take its original space.

**Multiple floating elements**

Apply float property to more elements to float them. Optionally use clear property to the next element to supress floating behavior.

<hr/>

**Center element horizontally**

Center an element horizontally using margin property with horizontal value set to auto. An element has to have width and height properties set.

**Center element vertically**

Center an elemet vertically by setting its position to absolute, top to 50% and margin-top to half of a height of an element.

**Center element both**

To center an element horizontally and vertically, apply vertical center method to parent container, an horizontal center method on element.
