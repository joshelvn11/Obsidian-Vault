## Function Declaration

```js
function isMinor1(age, legalAge) {
  if (age < legalAge) {
    return `Minor`;
  } else {
    return `Adult`;
  }
}
```

## Function Expression

```js
const isMinor = function (age, legalAge) {
  if (age < legalAge) {
    return `Minor`;
  } else {
    return `Adult`;
  }
};
```

## Arrow Functions
Syntax
```js
const functionName = (parameters) => return value;
```

Example
```js
const getAge = (birthYear) => 2023 - birthYear;
```

Multi-line arrow functions
```js
const isMinor = (age, legalAge) => {
  if (age < legalAge) {
    return `Minor`;
  } else {
    return `Adult`;
  }
};
```