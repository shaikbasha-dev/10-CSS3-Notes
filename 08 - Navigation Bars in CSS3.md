# 08 - Navigation Bars in CSS3

## Introduction

A Navigation Bar (Navbar) is one of the most important components of a website. It provides links to different pages and helps users navigate through the website easily.

Navigation bars can be:

1. Horizontal Navigation Bar
2. Vertical Navigation Bar

CSS3 provides various properties to design attractive and responsive navigation menus.

---

## What is a Navigation Bar?

A Navigation Bar is a collection of hyperlinks grouped together to provide navigation across a website.

### Why Navigation Bars are Used

* Easy website navigation
* Better user experience
* Professional website design
* Improves accessibility
* Helps organize website pages

---

## Semantic Tag Used

### `<nav>`

**Definition:**

The `<nav>` element is a semantic HTML5 tag used to define a block of navigation links.

**Example:**

```html
<nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
</nav>
```

---

# 1. Horizontal Navigation Bar

## Program

```html
<!DOCTYPE html>
<html>

<head>

    <title>Horizontal Navigation Bar</title>

    <style>

        nav{

            background-color: lightgray;

            padding:10px;

        }

        nav a{

            text-decoration:none;

            color:black;

            padding:10px;

        }

        nav a:hover{

            background-color:gray;

        }

    </style>

</head>

<body>

    <nav>

        <a href="#">Home</a> |

        <a href="#">About</a> |

        <a href="#">Contact</a>

    </nav>

    <p>

        This is the main content of the page.

    </p>

</body>

</html>
```

---

## Explanation

### `text-decoration:none;`

Removes the default underline from hyperlinks.

```css
text-decoration:none;
```

---

### `padding:10px;`

Creates space around each menu item.

```css
padding:10px;
```

---

### `nav a:hover`

Changes the appearance when the mouse moves over the link.

```css
nav a:hover{
    background-color:gray;
}
```

---

# 2. Vertical Navigation Bar

## Program

```html
<!DOCTYPE html>
<html>

<head>

    <title>Vertical Navigation Bar</title>

    <style>

        nav{

            background-color:lightgray;

            padding:10px;

            width:200px;

        }

        nav a{

            text-decoration:none;

            color:black;

            display:block;

            padding:10px;

        }

        nav a:hover{

            background-color:gray;

        }

    </style>

</head>

<body>

    <nav>

        <a href="#">Home</a>

        <a href="#">About</a>

        <a href="#">Services</a>

        <a href="#">Contact</a>

    </nav>

</body>

</html>
```

---

## Important Property

### `display:block`

```css
display:block;
```

**Definition:**

Converts inline elements into block-level elements.

**Effect:**

* Each link appears on a new line.
* Occupies full available width.
* Creates a vertical menu.

---

## Difference Between Inline and Block

| Inline                       | Block                   |
| ---------------------------- | ----------------------- |
| Same Line                    | New Line                |
| Width depends on content     | Occupies full width     |
| Example: span, a             | Example: div, p         |
| Cannot set full width easily | Width can be controlled |

---

## CSS Properties Used

### 1. Background Color

```css
background-color:lightgray;
```

Sets the background color.

---

### 2. Color

```css
color:black;
```

Sets text color.

---

### 3. Padding

```css
padding:10px;
```

Adds inner spacing.

---

### 4. Hover Effect

```css
nav a:hover{
    background-color:gray;
}
```

Changes background color when the user places the mouse pointer over a menu item.

---

## Pseudocode

```text
START

Create HTML Document

Create Navigation Container

Add Hyperlinks

Apply Background Color

Remove Underline

Apply Padding

Add Hover Effect

Display Navigation Bar

END
```

---

## Output Summary

### Horizontal Navigation Bar

Output:

```text
Home | About | Contact
```

* Links appear in a single row.
* Background becomes gray when hovered.

---

### Vertical Navigation Bar

Output:

```text
Home

About

Services

Contact
```

* Links appear one below another.
* Each link occupies the entire width.
* Hover changes the background color.

---

## Real-Time Applications

Navigation Bars are used in:

* Portfolio Websites
* E-Commerce Websites
* Banking Applications
* Educational Websites
* Company Websites
* Dashboards
* Admin Panels
* Social Media Websites

---

## Advantages of Navigation Bars

✔ Easy Navigation

✔ Professional Design

✔ Responsive Layout

✔ Improved User Experience

✔ Better Accessibility

✔ SEO Friendly

✔ Organized Website Structure

---

## Horizontal vs Vertical Navigation

| Horizontal Navbar         | Vertical Navbar                |
| ------------------------- | ------------------------------ |
| Used at top of page       | Used in sidebar                |
| Links appear side by side | Links appear one below another |
| Uses inline elements      | Uses display:block             |
| Suitable for menus        | Suitable for dashboards        |

---

## Final Summary

Navigation Bars are essential components of modern web applications.

Using HTML5 `<nav>` and CSS3 properties such as:

* `background-color`
* `padding`
* `text-decoration`
* `display:block`
* `hover`

developers can create attractive and user-friendly navigation menus.

Both Horizontal and Vertical Navigation Bars are widely used in modern Front-End Development, Angular Applications, and Java Full Stack projects.
