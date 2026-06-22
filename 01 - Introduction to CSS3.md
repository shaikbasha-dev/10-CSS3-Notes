# 01 - Introduction to CSS3

## Cascading Style Sheets (CSS)

CSS stands for **Cascading Style Sheets**.

CSS is used to apply styles and formatting to HTML elements. It controls the appearance of web pages, including colors, fonts, spacing, layouts, and animations.

CSS was proposed by **Håkon Wium Lie** in **1994**.

---

## Why do we use CSS?

CSS is used to:

1. Change text color and font style.
2. Add backgrounds and borders.
3. Control spacing using margin and padding.
4. Create responsive layouts.
5. Add animations and transitions.
6. Improve the visual appearance of websites.

---

## Syntax of CSS

```html
<style>
selector {
    property: value;
}
</style>
```

### Example

```css
h1 {
    color: blue;
    font-size: 30px;
}
```

---

## Style Attribute

```html
style=""
```

`style` is an HTML attribute used to apply CSS directly to an HTML element.

---

# CSS can be applied in three different ways

1. Inline CSS
2. Internal CSS
3. External CSS

---

# 1. Inline CSS

If we apply CSS directly inside an HTML element using the **style attribute**, it is called **Inline CSS**.

### HTML Document: InlineCSS.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Inline CSS</title>
</head>
<body>

    <h1 style="font-size:30px; background-color:yellowgreen;">
        CSS
    </h1>

    <p style="background-color:burlywood;">
        Hello Inline CSS
    </p>

    <pre style="color:antiquewhite; font-family:fantasy; background-color:black;">
Hi,
This is Inline CSS
    </pre>

</body>
</html>
```

### Output

* CSS heading with yellow-green background
* Paragraph with burlywood background
* Preformatted text with custom font and color

### Advantages of Inline CSS

* Easy to apply for a single element.
* Quick testing of styles.

### Disadvantages

* Difficult to maintain.
* Repetition of code.
* Not suitable for large projects.

---

## Important Note

* Use **px** (pixels) for text sizes.

Example:

```css
font-size:30px;
```

* Use **%** for responsive widths.

Example:

```css
width:50%;
```

---

# 2. Internal CSS

If CSS is written inside the `<style>` tag within the `<head>` section of an HTML document, it is called **Internal CSS**.

### HTML Document: InternalCSS.html

```html
<!DOCTYPE html>
<html lang="en">
<head>

<title>Internal CSS</title>

<style>

#S1{
    border:4px solid #FF884C;
    font-size:30px;
    text-align:right;
    background-color:#804674;
}

.S2{
    border:2px solid #FF884C;
    font-size:30px;
    text-align:center;
}

p{
    background-color:#086464;
    color:white;
}

</style>

</head>

<body>

<h1 id="S1">CSS</h1>

<h2 class="S2">Internal CSS</h2>

<p>Hi, I am Internal CSS</p>

</body>
</html>
```

---

## Important Notes

### 1. ID Selector

When we use:

```css
#idName
```

It is called an **ID Selector**.

Example:

```css
#S1{
color:red;
}
```

---

### 2. Class Selector

When we use:

```css
.className
```

It is called a **Class Selector**.

Example:

```css
.S2{
font-size:30px;
}
```

---

### 3. Color Palettes

To explore more colors, you can use:

```text
https://colorhunt.co
```

Copy the hexadecimal color codes and use them in CSS.

Example:

```css
background-color:#FF884C;
```

---

# 3. External CSS

If CSS is written in a separate `.css` file and linked to an HTML document, it is called **External CSS**.

This is the most commonly used method in real-world projects.

---

### HTML Document: ExternalCSS.html

```html
<!DOCTYPE html>
<html lang="en">

<head>

<title>External CSS</title>

<link rel="stylesheet" href="external.css">

</head>

<body>

<ol id="S1">

<li>HTML5</li>
<li>CSS3</li>
<li>JavaScript</li>

</ol>

<ul class="S2">

<li>HTML5</li>
<li>CSS3</li>
<li>JavaScript</li>

</ul>

</body>
</html>
```

---

### CSS Style Sheet: external.css

```css
#S1{
    background-color:#FFACCC;
}

.S2{
    background-color:#FBFFB1;
}
```

---

## Advantages of External CSS

* Reusable across multiple HTML files.
* Easy to maintain.
* Cleaner HTML code.
* Suitable for large applications.
* Faster website maintenance.

---

## Inline CSS vs Internal CSS vs External CSS

| Inline CSS             | Internal CSS         | External CSS            |
| ---------------------- | -------------------- | ----------------------- |
| Uses style attribute   | Uses style tag       | Uses separate CSS file  |
| Affects single element | Affects single page  | Affects multiple pages  |
| Difficult to maintain  | Moderate             | Easy to maintain        |
| Not preferred          | Used for small pages | Mostly used in projects |

---

## Summary

CSS is used to style HTML content and improve the appearance of web pages.

CSS can be applied in three ways:

* Inline CSS
* Internal CSS
* External CSS

Among these, **External CSS is the most preferred method** because it is reusable, maintainable, and widely used in professional web development projects.
