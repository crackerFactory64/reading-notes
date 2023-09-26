# CSS Layout

## Flexbox

Flexbox is suited for laying out one-dimensional content. One-dimensional content is content that is only displayed along one dimension, either a row or a column. In Flexbox, the main axis is the axis that Flexbox is configured to display content along, row or column. The other axis is referred to as the cross axis.

Some Flexbox properties can negatively impact accessibility. Properties such as _flex-reverse_ or _order_ affect the order in which elements are displayed but not the way they are read by a screen reader and therefore shouldn't be used when the order of items is important to the user experience.

Flexbox has many benefits over _float_ when it comes to layout:

- Flexbox makes it easy to line up elements neatly
- Flexbox makes it simple to vertically align elements
- Flexbox is responsive
- Flexbox makes it possible to change the order of elements from within CSS
