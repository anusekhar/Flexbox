# Flexbox
The Flexbox Layout (Flexible Box) module (currently a W3C Last Call Working Draft) aims at providing a more efficient way to lay out, align and distribute space among items in a container, even when their size is unknown and/or dynamic (thus the word "flex").

The main idea behind the flex layout is to give the container the ability to alter its items' width/height (and order) to best fill the available space. A flex container expands items to fill available free space, or shrinks them to prevent overflow.

Most importantly, the flexbox layout is direction-agnostic as opposed to the regular layouts (block which is vertically-based and inline which is horizontally-based). While those work well for pages, they lack flexibility (no pun intended) to support large or complex applications (especially when it comes to orientation changing, resizing, stretching, shrinking, etc.).

```
         Properties for the Parent
            (flex container)
                   display
                   flex-direction
                   flex-wrap
                   flex-flow
                   justify-content
                   align-items
                   align-content

        Properties for the Children
            (flex items)
                    align-self
                    order
                    flex-grow
                    flex-shrink
                    flex-basis
```

Prefixing Flexbox:

IE 10 : -ms-   
    display: -ms-flex;

Safari 8 & IOS Safari 8.4 : -webkit-   
    display: -webkit-flex;

Android 4.1 & 4.3: -webkit-   
    display: -webkit-flex;

Bugs:

Flexbox is certainly not without its bugs.The best collection of them I've seen is Philip Walton and Greg Whitworth's Flexbugs[https://github.com/philipwalton/flexbugs].
