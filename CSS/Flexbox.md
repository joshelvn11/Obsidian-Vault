## Flexbox Parent Properties
Flexbox dynamically arranges items along a main axis and cross axis. It is a 1 dimensional layout as it deals lays out items in one dimension at a time. By default the main axis is horizontal axis but this can be changed using the `flex-direction` property.

By default flexbox will try to fit all child items on one line, this can be changed using the `flex-wrap` property.

### `flex-direction`
This controls how the child elements are arranged by setting the **main axis** (horizontal for row, vertical for column) and direction (left to right or reversed, top to bottom or reversed)

The possible values are:
- `row` (default)
- `column`
- `row-reverse`
- `column-reverse`

### `flex-wrap`
Controls whether the child elements are allowed to wrap to a new row/column if there isn't enough space. By default flex will try fit all child elements on one line.

The possible values are 
- `no-wrap` (default)
- `wrap`
- `wrap-reverse`

### `justify-content`
Controls how child elements are distributed along the main axis

The possible values are:
- `flex-start` (default)
- `flex-end`
- `center`
- `space-between`
- `space-around`
- `space-evenly`

### `align-items`
Controls how child elements are distributed on the cross axis

The possible values are:
- `stretch`
- `flex-start`
- `center`
- `baseline`

### `gap`
Sets a minimum space between child elements.

### `flex-flow`
Shorthand property that sets `flex-direction` and `flex-wrap` in a single property

## Flexbox Child Properties

### `flex-basis`
Flexbox version of width. It determines the size of the element along the main axis

### `align-self`
Overrides the align-items property from the parent and sets the alignment on the cross axis.

### `order`
Moves an element towards the start (negative) or end (positive) according to the flex-direction.

### `flex-grow`
Allocates how excess space in the parent is used by an element compared to its siblings

### `flex-shrink`
If there is a **deficit of space** in the parent, flex-shrink decides the ratio at which this must be divided. The higher the number, the more an element will shrink.

### `flex`
Shorthand property for `flex-grow`, `flex-shrink`, `flex-basis`
