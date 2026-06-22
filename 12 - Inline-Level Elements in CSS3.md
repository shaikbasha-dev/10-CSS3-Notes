# 12 - Inline-Level Elements in CSS3

## Introduction

In HTML and CSS3, elements are mainly classified into:

1. Block-Level Elements
2. Inline-Level Elements

Inline-level elements are used to display content within a line without breaking the normal flow of text.

---

## Definition

An **Inline-Level Element** is an HTML element that:

* Does not start on a new line.
* Occupies only the width required by its content.
* Allows other inline elements to appear beside it.
* Flows naturally with surrounding text.

---

## Why are they called Inline-Level Elements?

They are called inline-level elements because they appear **in the same line** as the surrounding text.

Example:

```text
This is HTML, CSS and JavaScript.
```

Here, multiple inline elements can exist side-by-side without creating a new line.

---

## Default CSS Property

By default, inline elements use:

```css
display:inline;
```

Because of this property:

* The element stays on the same line.
* It occupies only the required width.
* The next element appears beside it.

---

## Characteristics of Inline-Level Elements

### 1. Does Not Start on a New Line

Example:

```html
<span>HTML</span>

<span>CSS</span>

<span>JavaScript</span>
```

Output:

```text
HTML CSS JavaScript
```

All elements appear on the same line.

---

### 2. Occupies Only Required Width

Example:

```html
<span>Hello</span>
```

The span occupies only enough width to display:

```text
Hello
```

---

### 3. Width and Height Are Ignored

Example:

```css
span{

    width:300px;

    height:100px;

}
```

The browser ignores these properties for normal inline elements.

---

### 4. Horizontal Margin and Padding Work Properly

Example:

```css
span{

    margin-left:20px;

    padding-left:15px;

}
```

---

### 5. Vertical Margin and Height Have Limited Effect

Example:

```css
span{

    margin-top:50px;

}
```

The element remains in the same text flow.

---

## Common Inline-Level Elements

### Text Formatting Elements

```html
<span></span>

<strong></strong>

<b></b>

<em></em>

<i></i>

<small></small>

<sub></sub>

<sup></sup>

<mark></mark>
```

---

### Hyperlinks

```html
<a></a>

<br>
```

---

### Media Elements

```html
<img>

<audio></audio>

<iframe></iframe>
```

---

### Code Elements

```html
<code></code>

<kbd></kbd>

<samp></samp>

<cite></cite>
```

---

### Form Elements

```html
<input>

<label></label>

<button></button>

<select></select>

<textarea></textarea>
```

---

## Example Program

### HTML Program

```html
<!DOCTYPE html>

<html>

<head>

    <title>Inline Level Elements</title>

</head>

<body>

    <span style="color:red;">HTML</span>

    <span style="color:blue;">CSS</span>

    <span style="color:green;">JavaScript</span>

</body>

</html>
```

---

## Output

```text
HTML CSS JavaScript
```

All elements appear on the same line with different colors.

---

## Inline Element with CSS

```html
<!DOCTYPE html>

<html>

<head>

<style>

span{

    color:white;

    background-color:teal;

    padding:10px;

}

</style>

</head>

<body>

<span>Inline Element Example</span>

</body>

</html>
```

---

## Output Explanation

The browser displays:

* Text with teal background.
* White font color.
* Padding around the text.
* Element remains inline.

---

## Inline vs Block-Level Elements

| Inline Elements         | Block Elements      |
| ----------------------- | ------------------- |
| Same line               | New line            |
| Occupies required width | Occupies full width |
| Width ignored           | Width supported     |
| Height ignored          | Height supported    |
| Example: span           | Example: div        |

---

## Converting Inline to Block

You can change an inline element into a block element.

Example:

```css
span{

    display:block;

}
```

Now:

* It starts on a new line.
* Occupies full width.
* Behaves like a block element.

---

## Converting Block to Inline

Example:

```css
div{

    display:inline;

}
```

Now:

* Div does not start on a new line.
* Occupies only required width.

---

## Pseudocode

```text
START

Create HTML Document

Create inline elements

Display them in same line

Apply CSS styles

Display output

END
```

---

## Real-Time Applications

Inline elements are used in:

* Text Formatting
* Hyperlinks
* Navigation Menus
* Buttons
* Icons
* Labels
* Search Bars
* Login Forms
* Badges
* Inline Notifications

---

## Advantages

✔ Occupies minimum space

✔ Displays elements side-by-side

✔ Useful for text formatting

✔ Lightweight

✔ Easy to style

✔ Responsive

---

## Important Interview Questions

### Q1. What is an Inline-Level Element?

An inline-level element occupies only the width required by its content and does not start on a new line.

---

### Q2. Which CSS property is used by inline elements by default?

```css
display:inline;
```

---

### Q3. Name some inline elements.

Examples:

* span
* a
* strong
* b
* em
* i
* img
* input
* button

---

### Q4. Can width and height be applied to inline elements?

Normally, width and height are ignored by inline elements.

---

### Q5. Which tag is the most commonly used inline element?

```html
<span></span>
```

The `<span>` tag is the most commonly used inline-level element.

---

## Final Summary

Inline-Level Elements are used to display content within the same line of a webpage.

They:

* Do not start on a new line.
* Occupy only the required width.
* Flow naturally with text.
* Are widely used for formatting and hyperlinks.

Understanding Inline Elements is essential for:

* CSS Styling
* Responsive Design
* Flexbox
* Navigation Bars
* Front-End Development
* Angular
* Java Full Stack Development
