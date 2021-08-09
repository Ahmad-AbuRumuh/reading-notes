# HTML & CSS

## Layouts

Each HTML element is treated as if it were in its own box by CSS. This box will either be a block-level box or an inline box. Block-level boxes begin on a new line and serve as the foundation of any layout, whereas inline boxes flow between adjacent text. By adjusting the width of the boxes, you can decide how much space each one takes up (and sometimes the height, too). Borders, margins, padding, and background colors can all be used to separate boxes.

* The outer box is known as the contained or parent element when one block-level element lies inside another block-level element.

Example:

``` HTML
<body>
  <h1>The Evolution of the Bicycle</h1>  
  <div>
    <p>In 1817 Baron von Drais invented a walking  machine that would help him get around the  royal gardens faster...
    </p>  
  </div>
</body>
```
