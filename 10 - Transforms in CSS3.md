# 10 - Transforms in CSS3

## Introduction

CSS3 Transforms allow developers to change the position, size, shape, and orientation of HTML elements without affecting the normal document flow.

Using transforms, we can:

* Rotate elements
* Scale elements
* Move elements
* Skew elements
* Transform text appearance

Transforms are widely used in modern web applications to create attractive and responsive user interfaces.

---

## Types of CSS3 Transforms

1. rotate()
2. scale()
3. translate()
4. skew()
5. text-transform

---

## 1. rotate()

### Definition

The `rotate()` function rotates an element clockwise or anti-clockwise by a specified angle.

### Syntax

```css
transform: rotate(45deg);
```

### Example

```html
<!DOCTYPE html>
<html>
<head>
    <title>Rotate Example</title>

    <style>

        div{

            width:100px;

            height:100px;

            background-color:orange;

            transform:rotate(45deg);

        }

    </style>

</head>

<body>

    <div></div>

</body>
</html>
```

### Output

The square box rotates by 45 degrees.

---

## 2. scale()

### Definition

The `scale()` function increases or decreases the size of an element.

### Syntax

```css
transform: scale(1.5);
```

### Example

```html
<!DOCTYPE html>
<html>
<head>

    <title>Scale Example</title>

    <style>

        div{

            width:100px;

            height:100px;

            background-color:skyblue;

            transform:scale(1.5);

        }

    </style>

</head>

<body>

    <div></div>

</body>
</html>
```

### Output

The box becomes 1.5 times larger than its original size.

---

## 3. translate()

### Definition

The `translate()` function moves an element from its original position.

### Syntax

```css
transform: translate(100px,50px);
```

### Example

```html
<!DOCTYPE html>
<html>
<head>

    <title>Translate Example</title>

    <style>

        div{

            width:100px;

            height:100px;

            background-color:green;

            transform:translate(100px,50px);

        }

    </style>

</head>

<body>

    <div></div>

</body>
</html>
```

### Output

The element moves:

* 100px towards right
* 50px towards bottom

---

## 4. skew()

### Definition

The `skew()` function tilts an element along the X-axis or Y-axis.

### Syntax

```css
transform: skew(20deg);
```

### Example

```html
<!DOCTYPE html>
<html>

<head>

    <title>Skew Example</title>

    <style>

        div{

            width:150px;

            height:80px;

            background-color:purple;

            transform:skew(20deg);

        }

    </style>

</head>

<body>

    <div></div>

</body>

</html>
```

### Output

The rectangle becomes tilted diagonally.

---

## 5. text-transform

### Definition

The `text-transform` property changes the capitalization of text.

It does not change the original text stored in HTML.

---

### uppercase

Converts all characters into uppercase.

```css
p{

    text-transform:uppercase;

}
```

Example:

```html
<p>This is a paragraph.</p>
```

Output:

```text
THIS IS A PARAGRAPH.
```

---

### lowercase

Converts all characters into lowercase.

```css
h1{

    text-transform:lowercase;

}
```

Example:

```html
<h1>This is a Heading.</h1>
```

Output:

```text
this is a heading.
```

---

### capitalize

Converts the first letter of every word into uppercase.

```css
h2{

    text-transform:capitalize;

}
```

Example:

```html
<h2>this is another heading.</h2>
```

Output:

```text
This Is Another Heading.
```

---

## Complete Program

```html
<!DOCTYPE html>
<html>

<head>

    <title>Transforms in CSS3</title>

    <style>

        p{

            text-transform:uppercase;

        }

        h1{

            text-transform:lowercase;

        }

        h2{

            text-transform:capitalize;

        }

    </style>

</head>

<body>

    <p>This is a paragraph.</p>

    <h1>This is a Heading.</h1>

    <h2>this is another heading.</h2>

</body>

</html>
```

---

## Pseudocode

```text
START

Create HTML Document

Create CSS Style Section

Apply uppercase to paragraph

Apply lowercase to h1

Apply capitalize to h2

Display the output

END
```

---

## Output Summary

The browser displays:

* Paragraph text in UPPERCASE
* H1 text in lowercase
* H2 text with the first letter of each word capitalized

Example:

```text
THIS IS A PARAGRAPH.

this is a heading.

This Is Another Heading.
```

---

## Real-Time Applications

CSS3 Transforms are used in:

* Image Galleries
* Buttons
* Navigation Menus
* Cards
* Hover Effects
* Dashboards
* Loading Animations
* Login Forms
* E-Commerce Websites
* Angular Applications

---

## Advantages of CSS3 Transforms

✔ Fast Rendering

✔ Hardware Accelerated

✔ Better User Experience

✔ Responsive Design

✔ Smooth Animations

✔ Lightweight

✔ No JavaScript Required

---

## Important Interview Questions

### Q1. What is CSS Transform?

CSS Transform is used to change the size, position, rotation, or shape of an HTML element.

---

### Q2. Which property is used for rotation?

```css
transform: rotate(45deg);
```

---

### Q3. Which transform moves an element?

```css
translate()
```

---

### Q4. Which transform changes the size of an element?

```css
scale()
```

---

### Q5. What is text-transform?

The `text-transform` property changes the capitalization of text.

Values:

* uppercase
* lowercase
* capitalize

---

## Final Summary

CSS3 Transforms provide powerful features to manipulate HTML elements visually.

Using:

* rotate()
* scale()
* translate()
* skew()
* text-transform

developers can create attractive and interactive web pages with better user experience.

CSS3 Transforms are one of the most important topics for Front-End Development, Angular, and Java Full Stack Development.
