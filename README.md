# Gap Intelligence's front-end coding standards
## Table of Contents
1. Overview
2. HTML Best Practices
3. HTML Formatting
4. CSS Best Practices
5. CSS Formatting
6. Sass
7. Accessibility
8. Browser and Device Support

# Overview

# HTML Best Practices

# HTML Formatting

# CSS Best Practices

# CSS Formatting
## Name Delimiters
**Class Names**

Use BEM for class names. Prefix the parent class with `.b-`

```
.block {
  padding: 0;
}
.block__element {
  padding: 0;
}
.block__element--modifier {
  padding: 0;
}
```
**States**
Use the class prefix `.is-` as in `.is-active` `.is-hidden` `.is-open`. To style, tie it to a class using a Sass `&`
```
.selector {
  &.is-open {
    display: block;
  }
}
```
## Brackets
Place the opening curly-bracket of each rule block on the same line as the last selector. Place the closing curly-bracket of each rule block on its own line after the final property of the rule block. End each property with a semicolon.
```
.selector {
  height: 100vh;
  padding: 1em;
}
```
## Indentation
Use 2 spaces for indenting. Indent each property in a rule block 2 spaces.
```
.selector {
  height: 100vh;
  padding: 1em;
}
```
## Property Whitespace
Put each property on its own line. Follow each property with a colon and a single space.
```
.selector {
  height: 100vh;
  padding: 1em;
}
```
## Semicolons
Follow each property value with a semi-colon.
```
.selector {
  height: 100vh;
  padding: 1em;
}
```
## Trailing Whitespace
Remove all trailing whitespace.

## Rule Block Separation
Separate each rule block with a line break.
```
.selector-one {
  height: 100vh;
  padding: 1em;
}
.selector-two {
  display: flex;
  margin: 1em;
}
```
## Property Order
CSS properties should be grouped alphabetically for easing scanning and locating.
```
.selector-one {
  align-items: center;
  background-color: #eee;
  display: flex;
  flex-flow: column wrap;
  height: 100vh;
  margin: 0 1em;
  opacity: 1;
  overflow: hidden;
  padding: 1em;
  visibility: visible;
  transition: all .2s;
}
```
# Sass

# Accessibility

# Browser and Device Support

