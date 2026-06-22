# 02 - Div Tag in CSS3

## HTML Div Tag Styling

### 1. Headline

**Understanding the `<div>` Tag and CSS Styling in HTML**

---

## 2. Introduction to Div Tag

The `<div>` tag is one of the most important elements in HTML and CSS.

It is a **block-level container** used to group HTML elements together and apply CSS styles to them.

The `<div>` tag does not have any visual appearance by default. Its appearance depends on the CSS properties applied to it.

---

## 3. Method Definitions / Program Definitions

### Method 1: HTML Document Structure

**Definition:**

The HTML document structure is the foundation of every webpage. It tells the browser how to read and display the content.

**Why it is used:**

It helps organize the webpage correctly so that browsers can understand and render the layout properly.

---

### Method 2: Using the `<div>` Tag

**Definition:**

The `<div>` element is a block-level container used to group content and apply CSS styling.

**Why it is used:**

It helps divide a webpage into logical sections such as:

* Header
* Navigation Bar
* Sidebar
* Content Area
* Footer
* Cards and Containers

---

### Method 3: CSS Styling

**Definition:**

CSS (Cascading Style Sheets) is used to style HTML elements and control their visual appearance.

**Why it is used:**

CSS helps:

* Add colors
* Add borders
* Control width and height
* Create layouts
* Improve webpage appearance

---

### Method 4: ID Selector (`#div1`)

**Definition:**

The `#div1` selector selects the HTML element whose id is `div1`.

**Why it is used:**

It is used to apply unique styles to a single element.

Example:

```css
#div1{
    border:3px solid red;
}
```

---

### Method 5: Class Selector (`.div2`)

**Definition:**

The `.div2` selector selects all elements that use the class name `div2`.

**Why it is used:**

It allows the same CSS style to be reused across multiple elements.

Example:

```css
.div2{
    border:3px solid red;
}
```

---

## 4. Purpose of the Program

This program demonstrates how to:

* Create containers using `<div>`
* Apply CSS styling
* Use ID selectors
* Use Class selectors
* Apply width and height properties
* Create bordered sections

---

## 5. Why This Program Helps in CSS Learning

This example helps in understanding:

**HTML → Defines Structure**

**CSS → Defines Presentation**

This is one of the most important concepts in Front-End Development.

---

## 6. Pseudocode

```text
START

Create HTML document

Create internal CSS

Style div with id selector
    Add border
    Add height
    Add width

Style div with class selector
    Add border

Create first div
Display text

Create second div
Display text

END
```

---

## 7. Complete Program

```html
<!DOCTYPE html>
<html lang="en">

<head>

    <title>Div Tag</title>

    <style>

        #div1{
            border:3px solid red;
            height:300px;
            width:100px;
        }

        .div2{
            border:3px solid red;
        }

    </style>

</head>

<body>

    <div id="div1">

        This is First Division Tag

    </div>

    <br>

    <div class="div2">

        This is Second Division Tag

    </div>

</body>

</html>
```

---

## 8. Explanation of the Code

### `<!DOCTYPE html>`

Declares that the document is an HTML5 document.

---

### `<html lang="en">`

Starts the HTML document and specifies English as the language.

---

### `<head>`

Contains metadata and CSS styles.

---

### `<title>Div Tag</title>`

Displays **Div Tag** in the browser tab.

---

### `<style>`

Begins the internal CSS section.

---

### `#div1`

ID selector.

Selects:

```html
<div id="div1">
```

and applies:

```css
border:3px solid red;
height:300px;
width:100px;
```

---

### `.div2`

Class selector.

Selects:

```html
<div class="div2">
```

and applies:

```css
border:3px solid red;
```

---

### `border:3px solid red;`

Creates:

* Border width = 3 pixels
* Border style = Solid
* Border color = Red

---

### `height:300px;`

Sets the height of the div to:

```text
300 pixels
```

---

### `width:100px;`

Sets the width of the div to:

```text
100 pixels
```

---

### `<div id="div1">`

Creates the first container using an ID selector.

Output:

```text
This is First Division Tag
```

---

### `<div class="div2">`

Creates the second container using a class selector.

Output:

```text
This is Second Division Tag
```

---

## 9. Difference Between ID and Class

| ID                   | Class                      |
| -------------------- | -------------------------- |
| Starts with #        | Starts with .              |
| Used for one element | Used for multiple elements |
| Must be unique       | Can be reused              |
| Example: #div1       | Example: .div2             |

---

## 10. Output Summary

When executed in the browser:

* The first div appears with:

  * Red border
  * Height = 300px
  * Width = 100px

* The second div appears with:

  * Red border
  * Automatic width and height

Both divs display their respective text.

---

## 11. Real-Time Usage of Div Tag

The `<div>` tag is widely used for:

* Website Header
* Navigation Menu
* Login Forms
* Cards
* Sidebars
* Dashboards
* Product Sections
* Footer Sections

Almost every modern website uses multiple `<div>` containers.

---

## 12. Final Summary

The `<div>` tag is one of the most important building blocks of web development.

Combined with CSS, it helps developers create:

* Structured layouts
* Beautiful interfaces
* Responsive designs
* Professional websites

Understanding the `<div>` tag and CSS selectors is essential for becoming a Front-End Developer or Java Full Stack Developer.
