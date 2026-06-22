# 11 - Block-Level Elements in CSS3

## Introduction

In HTML and CSS3, elements are classified into two main categories:

1. Block-Level Elements
2. Inline Elements

Block-level elements are the fundamental building blocks used to create the structure and layout of web pages.

---

## Definition

A **Block-Level Element** is an HTML element that:

* Starts on a new line.
* Occupies the full available width of its parent container.
* Creates a rectangular box.
* Supports width, height, margin, and padding properties.

---

## Why are they called Block-Level Elements?

They are called block-level elements because they behave like rectangular blocks.

Each element:

* Starts on a new line.
* Creates its own separate section.
* Pushes the next element to another line.
* Occupies the complete width available.

Example:

```text
--------------------------------
|         Heading             |
--------------------------------

--------------------------------
|       Paragraph             |
--------------------------------

--------------------------------
|          Div                |
--------------------------------
```

Every block occupies an independent row.

---

## Why Do They Start on a New Line?

By default, block elements have:

```css
display: block;
```

The browser automatically:

* Creates a new line before the element.
* Expands the element to full width.
* Places the next element on another line.

Therefore, no other element can appear beside it unless CSS properties like:

```css
display:inline-block;
```

or

```css
float:left;
```

are used.

---

## Characteristics of Block-Level Elements

### 1. Starts on a New Line

Every block element begins on a separate line.

Example:

```html
<h1>Heading</h1>

<p>Paragraph</p>

<div>Division</div>
```

---

### 2. Occupies Full Width

A block element automatically occupies:

```text
100% width of parent container
```

unless width is specified.

Example:

```css
div{

    width:300px;

}
```

---

### 3. Supports Width and Height

Example:

```css
div{

    width:200px;

    height:100px;

}
```

---

### 4. Supports Margin and Padding

Example:

```css
div{

    margin:20px;

    padding:15px;

}
```

---

## Common Block-Level Elements

### Structural Elements

```html
<div></div>

<header></header>

<footer></footer>

<main></main>

<section></section>

<article></article>

<aside></aside>
```

---

### Heading Elements

```html
<h1></h1>

<h2></h2>

<h3></h3>

<h4></h4>

<h5></h5>

<h6></h6>
```

---

### Text Elements

```html
<p></p>

<pre></pre>

<blockquote></blockquote>

<hr>
```

---

### Lists

```html
<ul></ul>

<ol></ol>

<li></li>

<dl></dl>

<dt></dt>

<dd></dd>
```

---

### Forms

```html
<form></form>

<fieldset></fieldset>

<output></output>
```

---

### Tables and Media

```html
<table></table>

<figure></figure>

<figcaption></figcaption>

<canvas></canvas>

<video></video>
```

---

## Example Program

### HTML Program

```html
<!DOCTYPE html>

<html>

<head>

    <title>Block Level Elements</title>

</head>

<body>

    <h1>This is Heading</h1>

    <p>This is Paragraph</p>

    <div>This is Div Tag</div>

</body>

</html>
```

---

## Output

```text
This is Heading

This is Paragraph

This is Div Tag
```

Each element starts on a new line.

---

## CSS Example

```html
<!DOCTYPE html>

<html>

<head>

<style>

div{

    border:2px solid red;

    width:300px;

    height:100px;

    padding:20px;

    margin:20px;

}

</style>

</head>

<body>

<div>

This is Block Level Element

</div>

</body>

</html>
```

---

## Output Explanation

The browser creates:

* A rectangular box.
* Width = 300px
* Height = 100px
* Padding = 20px
* Margin = 20px
* Red border around the element.

---

## Block-Level vs Inline Elements

| Block-Level Elements        | Inline Elements              |
| --------------------------- | ---------------------------- |
| Starts on new line          | Does not start on new line   |
| Occupies full width         | Occupies only required width |
| Supports width              | Width ignored                |
| Supports height             | Height ignored               |
| Supports margin and padding | Limited support              |
| Example: div                | Example: span                |

---

## CSS Display Property

You can convert an element into block-level.

Example:

```css
span{

    display:block;

}
```

Now the inline `<span>` behaves like a block element.

---

## Pseudocode

```text
START

Create HTML Document

Add Block Elements

Each element starts on new line

Apply CSS properties

Display output

END
```

---

## Real-Time Applications

Block-level elements are used in:

* Website Layouts
* Navigation Bars
* Login Forms
* Dashboards
* Sidebars
* Blogs
* E-Commerce Websites
* Portfolio Websites
* News Websites
* Landing Pages

---

## Advantages

✔ Creates structured layouts

✔ Supports width and height

✔ Easy spacing using margin and padding

✔ Responsive design friendly

✔ Compatible with Flexbox and Grid

✔ Easy to style using CSS

---

## Important Interview Questions

### Q1. What is a Block-Level Element?

A block-level element starts on a new line and occupies the full available width.

---

### Q2. Which CSS property makes an element block-level?

```css
display:block;
```

---

### Q3. Give examples of Block-Level Elements.

Examples:

* div
* p
* h1
* section
* article
* header
* footer
* form

---

### Q4. Can block elements have width and height?

Yes.

Block-level elements support:

* width
* height
* margin
* padding

---

### Q5. Which tag is the most commonly used block-level element?

```html
<div></div>
```

The `<div>` tag is the most commonly used block-level element for webpage layouts.

---

## Final Summary

Block-Level Elements are the structural foundation of HTML and CSS3 layouts.

They:

* Start on a new line.
* Occupy the full width.
* Support the CSS Box Model.
* Create webpage layouts efficiently.

Understanding block-level elements is essential for learning:

* CSS Box Model
* Flexbox
* Grid
* Responsive Design
* Front-End Development
* Angular
* Java Full Stack Development
