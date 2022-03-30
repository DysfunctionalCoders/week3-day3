# Week 3 Day 3 Notes

## Review

JavaScript has access to the HTML **document** in a form of an *class*.
The class has methods available, specifically **query selectors**, which allows us to access HTML **DOM** elements. 

### Query Selectors

It is the document itself that allows us to use the query selector therefore we prefix the method with `document.`

There are five query selectors.

- getElementById
- getElementsByClassName
- getElementsByTagName
- querySelector
- querySelectorAll

All methods have parenthese suffix because it is an invocation of a function.

These specific methods take in a string argument corresponding to what it is looking for. ie. `p`

### DOM Manipulation

We can store variables with the returned DOM element from query selectors.
From there we have access to the content and attributes of the element through JavaScript. 

Yesterday we change the style of DOM elements ie.

`element.style = 'color: green'`

Additionally, we can target the single color style as such:

`element.style.color = 'green'`

The second method will only override the color value if it already exists, whereas the first method will override the whole style attribute.

### Functions

The syntax:

```js

functionName(){
    // logic here
}

```

There are two stages to functions:
- declaration
- invocation

## Lesson

### For loop

The syntax:

```js

for (var i = 0; i < array.length; i++) {

}

```

### Carousel with JavaScript

Throwback to CSS!
- transform
- translate
  - translateX

### Relative vs. Absolute Paths

### HTML input value



