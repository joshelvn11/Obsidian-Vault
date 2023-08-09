Positioning with CSS is one of the most important parts of CSS. It forms the basis of every layout. Positioning is controlled by the `position` property. The flow of the page is the arrangement of the elements set by their `position` property and the order of HTML elements. All elements on a web page are positioned `static` by default, and this is what is considered “normal flow” of the page. It means that they will sit vertically above each other in the order that they appear in the HTML structure.

---

## Static Positioning 

The element is positioned according to the normal flow of the document. The `top`, `right`, `bottom`, `left`, and `z-index` properties have _no effect_. This is the default value.

---

## Relative Positioning 

The element is positioned according to the normal flow of the document, and then offset _relative to itself_ based on the values of `top`, `right`, `bottom`, and `left`. The offset does not affect the position of any other elements; thus, the space given for the element in the page layout is the same as if position were `static`.

---

## Absolute Positioning 

The element is removed from the normal document flow, and no space is created for the element in the page layout. The element is positioned relative to its closest positioned ancestor (if any) or to the initial containing block. Its final position is determined by the values of `top`, `right`, `bottom`, and `left`.

--- 

## Fixed Positioning 

The element is removed from the normal document flow, and no space is created for the element in the page layout. The element is positioned relative to the viewport. Its final position is determined by the values of `top`, `right`, `bottom`, and `left`.

---

## Sticky Positioning

The element is positioned according to the normal flow of the document, and then offset relative to its _nearest scrolling ancestor_ and containing block (nearest block-level ancestor), including table-related elements, based on the values of `top`, `right`, `bottom`, and `left`. The offset does not affect the position of any other elements.

This value always creates a new stacking context. Note that a sticky element "sticks" to its nearest ancestor that has a "scrolling mechanism" (created when `overflow` is `hidden`, `scroll`, `auto`, or `overlay`), even if that ancestor isn't the nearest actually scrolling ancestor.

