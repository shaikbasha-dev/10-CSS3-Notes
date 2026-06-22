# 04 - Selectors in CSS3

## Introduction

CSS Selectors are patterns used to select HTML elements and apply styles to them. Selectors help developers target one element, a group of elements, or elements in specific states.

CSS3 provides three major categories of selectors:

1. Simple Selectors
2. Pseudo-Class Selectors
3. Pseudo-Element Selectors

---

## 1. Simple Selectors

Simple selectors target HTML elements directly based on:

* Element Name
* Class Name
* ID Name
* Group of Elements
* Universal Selection

### Definition

Simple selectors are CSS selectors used to select elements based on their type, class, id, or grouping.

### Why are they used?

They help apply styles efficiently to HTML elements without repeating CSS code.

---

### Types of Simple Selectors

#### 1. Universal Selector (*)

Selects all elements in the HTML document.

Example:

```css
*{
    font-family: Arial;
}
```

---

#### 2. Element Selector

Selects all occurrences of a specific HTML tag.

Example:

```css
h1{
    color: blue;
}
```

---

#### 3. Class Selector (.)

Selects elements having the same class attribute.

Example:

```css
.course{
    color: green;
}
```

---

#### 4. ID Selector (#)

Selects one unique element with a specific id.

Example:

```css
#student{
    color: red;
}
```

---

#### 5. Group Selector (,)

Applies the same style to multiple elements.

Example:

```css
h2,p{
    background-color: yellow;
}
```

---

## Complete Program: Simple Selectors

```html
<!DOCTYPE html>
<html>
<head>

    <title>Simple Selectors</title>

    <style>

        /* Universal Selector */

        *{
            font-family: Arial;
        }

        /* Element Selector */

        h1{
            color: blue;
        }

        /* Class Selector */

        .course{
            color: green;
        }

        /* ID Selector */

        #student{
            color: red;
        }

        /* Group Selector */

        h2,p{
            background-color: yellow;
        }

    </style>

</head>

<body>

    <h1>Element Selector Example</h1>

    <h2>Group Selector Example</h2>

    <p>
        This paragraph is styled using Group Selector.
    </p>

    <p class="course">
        HTML CSS JavaScript
    </p>

    <p id="student">
        Basha
    </p>

</body>
</html>
```

---

## 2. Pseudo-Class Selectors

Pseudo-class selectors use a single colon (:)

They select elements based on their current state.

### Definition

A pseudo-class is used to define the special state of an element.

### Why is it used?

It helps create interactive webpages.

Examples:

* Mouse Hover
* Visited Links
* Active Links
* Focus State

---

### Important Pseudo-Classes

####

Styles unvisited hyperlinks.

```css
a:link{
    color: green;
}
```

---

####

Styles visited hyperlinks.

```css
a:visited{
    color: purple;
}
```

---

####

Styles the link while it is being clicked.

```css
a:active{
    color:red;
}
```

---

####

Applies styles when the mouse pointer moves over an element.

```css
button:hover{
    background-color: lightgray;
}
```

---

## Complete Program: Pseudo-Class Selectors

```html
<!DOCTYPE html>

<html>

<head>

<title>Pseudo-Class Selectors</title>

<style>

a:link{
    color:green;
}

a:visited{
    color:purple;
}

a:active{
    color:red;
}

button:hover{
    background-color:lightgray;
}

</style>

</head>

<body>

<a href="https://www.google.com">
Google
</a>

<br><br>

<a href="https://www.facebook.com">
Facebook
</a>

<br><br>

<a href="https://www.twitter.com">
Twitter
</a>

<br><br>

<button>
Hover Me!
</button>

<button>
Hover Me Too!
</button>

</body>

</html>
```

---

## 3. Pseudo-Element Selectors

Pseudo-element selectors use double colons (::)

They style specific portions of an HTML element.

### Definition

Pseudo-elements select a specific part of an element and apply CSS styles.

### Why are they used?

They help:

* Add virtual content
* Style first letter
* Style first line
* Add decorative content

---

### Important Pseudo-Elements

#### ::before

Adds content before an element.

Example:

```css
li::before{
    content:"• ";
}
```

---

#### ::after

Adds content after an element.

Example:

```css
p::after{
    content:" ©";
}
```

---

#### ::first-letter

Styles the first letter of an element.

Example:

```css
p::first-letter{

font-size:200%;

font-weight:bold;

}
```

---

#### ::first-line

Styles the first line of an element.

Example:

```css
p::first-line{

font-style:italic;

}
```

---

## Complete Program: Pseudo-Element Selectors

```html
<!DOCTYPE html>

<html>

<head>

<title>Pseudo-Element Selectors</title>

<style>

li::before{

content:"• ";

}

p::after{

content:" ©";

}

p::first-letter{

font-size:200%;

font-weight:bold;

}

p::first-line{

font-style:italic;

}

</style>

</head>

<body>

<ul>

<li>Item 1</li>

<li>Item 2</li>

<li>Item 3</li>

</ul>

<p>

This is a paragraph.

The first letter is larger,

the first line is italic,

and copyright symbol is added automatically.

</p>

</body>

</html>
```

---

## Selector Symbols Summary

| Selector           | Symbol   | Example             |
| ------------------ | -------- | ------------------- |
| Universal Selector | *        | `*{}`               |
| Element Selector   | Tag Name | `h1{}`              |
| Class Selector     | .        | `.course{}`         |
| ID Selector        | #        | `#student{}`        |
| Group Selector     | ,        | `h1,p{}`            |
| Pseudo-Class       | :        | `a:hover{}`         |
| Pseudo-Element     | ::       | `p::first-letter{}` |

---

## Difference Between Class and ID Selector

| Class Selector                    | ID Selector                 |
| --------------------------------- | --------------------------- |
| Uses .                            | Uses #                      |
| Can be used for multiple elements | Used for one unique element |
| Example: `.course`                | Example: `#student`         |

---

## Difference Between Pseudo-Class and Pseudo-Element

| Pseudo-Class             | Pseudo-Element          |
| ------------------------ | ----------------------- |
| Uses :                   | Uses ::                 |
| Selects state of element | Selects part of element |
| Example                  | Example ::first-letter  |
| Example                  | Example ::before        |

---

## Pseudocode

```text
START

Create HTML Document

Apply Universal Selector

Apply Element Selector

Apply Class Selector

Apply ID Selector

Apply Group Selector

Create Pseudo Class Styles

Create Hover Effects

Create Pseudo Element Styles

Display Output

END
```

---

## Output Summary

When executed:

1. All text uses Arial font.
2. h1 text appears Blue.
3. Class element appears Green.
4. ID element appears Red.
5. h2 and p have Yellow background.
6. Links change colors according to their state.
7. Buttons change color on hover.
8. Paragraph shows:

   * Large first letter
   * Italic first line
   * Copyright symbol automatically.

---

## Final Summary

CSS3 Selectors are one of the most important concepts in Front-End Development.

By learning:

* Universal Selector
* Element Selector
* Class Selector
* ID Selector
* Group Selector
* Pseudo-Class Selectors
* Pseudo-Element Selectors

developers can build clean, maintainable, and interactive webpages efficiently.

Mastering selectors is an essential skill for HTML, CSS, JavaScript, Angular, and Java Full Stack Development.
