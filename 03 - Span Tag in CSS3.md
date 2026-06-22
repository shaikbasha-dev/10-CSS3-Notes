# 03 - Span Tag in CSS3

## HTML Span Tag Styling Example

### 1. Headline

**Understanding the `<span>` Tag and Inline CSS Styling in HTML**

---

## 2. Introduction to Span Tag

The `<span>` tag is an **inline HTML element** used to group small portions of text and apply CSS styles to them.

Unlike the `<div>` tag, the `<span>` tag does **not start on a new line**. It occupies only the required width and stays on the same line as surrounding text.

---

## 3. Method Definitions / Program Definitions

### Method 1: HTML Document Structure

**Definition:**

The HTML document structure is the fundamental framework of a webpage. It instructs the browser how to parse and display the document.

**Why it is used:**

It provides a standard structure for every HTML webpage.

---

### Method 2: Using the `<span>` Tag

**Definition:**

The `<span>` element is an inline-level container used to wrap small portions of text without creating line breaks.

**Why it is used:**

It allows developers to style:

* Single words
* Individual characters
* Small text portions
* Inline content

---

### Method 3: Inline CSS Styling (`style=""`)

**Definition:**

Inline CSS uses the HTML `style` attribute to apply CSS properties directly to an individual element.

**Why it is used:**

It provides quick styling for:

* Text color
* Font size
* Background color
* Font family

---

### Method 4: Center Alignment

**Definition:**

The `<center>` tag places content horizontally in the middle of the webpage.

**Note:**

In modern HTML5, CSS is preferred:

```css
text-align:center;
```

instead of:

```html
<center>
```

---

## 4. Purpose of the Program

This program demonstrates:

* The use of the `<span>` tag
* Inline CSS styling
* Text coloring
* Font sizing
* Multiple inline elements on the same line

---

## 5. Why This Program Helps in CSS Learning

This example helps understand:

### Block Elements

Examples:

```html
<div>
<p>
<h1>
```

They start on a new line.

### Inline Elements

Examples:

```html
<span>
<a>
<b>
<i>
```

They remain on the same line.

The `<span>` tag is one of the most commonly used inline elements in CSS.

---

## 6. Pseudocode

```text
START

Create HTML document

Create page title

Open body

Center content

Create span
Apply blue color
Display G

Create span
Apply red color
Display o

Create span
Apply goldenrod color
Display o

Create span
Apply green color
Display g

Create span
Apply blue color
Display l

Create span
Apply red color
Display e

Close body

END
```

---

## 7. Complete Program

```html
<!DOCTYPE html>
<html lang="en">

<head>

    <title>Span Tag</title>

</head>

<body>

<center>

    <span style="color:blue; font-size:60px;">
        G
    </span>

    <span style="color:red; font-size:60px;">
        o
    </span>

    <span style="color:goldenrod; font-size:60px;">
        o
    </span>

    <span style="color:green; font-size:60px;">
        g
    </span>

    <span style="color:blue; font-size:60px;">
        l
    </span>

    <span style="color:red; font-size:60px;">
        e
    </span>

</center>

</body>

</html>
```

---

## 8. Explanation of the Code

### `<!DOCTYPE html>`

Declares the document as HTML5.

---

### `<html lang="en">`

Starts the HTML document and specifies English as the language.

---

### `<head>`

Contains metadata information.

---

### `<title>Span Tag</title>`

Displays **Span Tag** in the browser tab.

---

### `<body>`

Contains the visible content of the webpage.

---

### `<center>`

Centers all child elements horizontally.

**Modern Alternative:**

```css
text-align:center;
```

---

### `<span>`

Creates an inline container.

Example:

```html
<span style="color:blue; font-size:60px;">
G
</span>
```

This:

* Displays the character G
* Colors it blue
* Sets font size to 60px

---

### `style=""`

Inline CSS attribute.

Used to apply:

```css
color:blue;
font-size:60px;
```

---

### `color`

Changes the text color.

Examples:

```css
color:blue;
color:red;
color:green;
color:goldenrod;
```

---

### `font-size`

Changes the size of the text.

Example:

```css
font-size:60px;
```

---

## 9. Colors Used in This Program

| Character | Color     |
| --------- | --------- |
| G         | Blue      |
| o         | Red       |
| o         | Goldenrod |
| g         | Green     |
| l         | Blue      |
| e         | Red       |

This creates a colorful **Google** text effect.

---

## 10. Span Tag vs Div Tag

| Span Tag                     | Div Tag                   |
| ---------------------------- | ------------------------- |
| Inline Element               | Block Element             |
| Occupies required width      | Occupies full width       |
| Does not start new line      | Starts new line           |
| Used for small text portions | Used for sections/layouts |
| Example: `<span>`            | Example: `<div>`          |

---

## 11. Output Summary

When executed in a browser:

* The word **Google** appears.
* Each character has a different color.
* Font size is 60px.
* All characters appear on the same line.
* The text is centered horizontally.

---

## 12. Real-Time Usage of Span Tag

The `<span>` tag is used in:

* Highlighting text
* Coloring keywords
* Error messages
* Search result highlighting
* Badges and labels
* Icons with text
* Partial text styling

---

## 13. Final Summary

The `<span>` tag is an important inline HTML element used to style individual words, letters, or small text sections without affecting the surrounding layout.

Combined with CSS, it allows developers to create:

* Colorful text
* Highlighted content
* Styled keywords
* Interactive user interfaces

Understanding the `<span>` tag is essential for Front-End Development and Java Full Stack Development.
