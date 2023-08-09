## Selector List
The selector list (`,`) separates all matching elements. A selector list is comma separated list of selects.
```
span,
div {
  border: red 2px solid;
}
```

```
#main,
.content,
article,
h1 + p {
  font-size: 1.1em;
}
```

---

## Descendant Combinator
The descendant combinator (" ") will select an descendants of a specified ancestor.
```
/* List items that are descendants of the "my-things" list */
ul.my-things li {
  margin: 2em;
}
```

---

## Child Combinator
The child combinator (`>`) will only select the direct child of a specified parent element.
```
/* List items that are children of the "my-things" list */
ul.my-things > li {
  margin: 2em;
}
```

---

## Adjacent Sibling Combinator
The adjacent sibling combinator (`+`) separates two selectors and selects the second element only if it immediately follows the first and they are both children of the same parent.
```
/* Paragraphs that come immediately after any image */
img + p {
  font-weight: bold;
}
```

---

## General Sibling Combinator
The general sibling combinator (`~`) seperates two selectors and selects all iterations of the select element the follow (though not necessarily immediately) and are children of the same parent.
```
/* Paragraphs that are siblings of and
   subsequent to any image */
img ~ p {
  color: red;
}
```