## Background Shorthand

The background shorthand CSS property allows you to set all background style properties in one declaration. This reduces the amount of code you have to write. When using the shorthand property, if other background properties are not defined, they are set to their initial values or they may inherit values from other CSS style rules.

When using the shorthand property, the order of the values don't matter in most cases, but there are exceptions. The first exception is where rules share the same value. For example, background-origin and background-clip could both have value border-box so if applying values to both they need to be in the order of background-origin then background-clip. Also, if using two numerical values for background-position the first refers to horizontal and the second vertical. The order of position keywords is not important.

```
body {
  background:  
     red                      /* background-color */
     url(sunset.jpg)          /* background-image */
     top center / 200px 200px /* background-position / background-size */
     no-repeat                /* background-repeat */
     fixed;                   /* background-attachment */
}
```
