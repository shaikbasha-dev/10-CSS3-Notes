# 07 - Semantic Elements in HTML5 and CSS3

## Introduction

Semantic Elements are special HTML5 tags that clearly describe the meaning and purpose of the content they contain.

Unlike generic tags such as `<div>`, semantic elements provide meaningful structure to web pages, making the code:

* Easier to read
* Easier to maintain
* More accessible
* Better for SEO (Search Engine Optimization)

---

## What are Semantic Elements?

Semantic elements are HTML tags that describe their content clearly to:

* Browsers
* Search Engines
* Screen Readers
* Developers

### Examples

* `<header>`
* `<nav>`
* `<main>`
* `<section>`
* `<article>`
* `<aside>`
* `<footer>`

---

## Why Semantic Elements are Important

Semantic elements help to:

* Improve code readability
* Increase website accessibility
* Improve search engine ranking
* Create well-structured layouts
* Replace excessive use of `<div>` tags

---

## Important Semantic Elements

### 1. `<header>`

**Definition:**

The `<header>` element represents the introductory section of a webpage or a section.

**Used for:**

* Website logo
* Website title
* Navigation menu
* Search bar

---

### 2. `<nav>`

**Definition:**

The `<nav>` element contains navigation links.

**Used for:**

* Home
* About
* Services
* Contact
* Menus

---

### 3. `<main>`

**Definition:**

The `<main>` element contains the main content of the webpage.

**Important Rule:**

Only one `<main>` element should exist in a webpage.

---

### 4. `<section>`

**Definition:**

The `<section>` element groups related content together.

**Examples:**

* Courses Section
* Services Section
* Contact Section

---

### 5. `<article>`

**Definition:**

The `<article>` element represents an independent piece of content.

**Examples:**

* Blog Post
* News Article
* Forum Post
* Magazine Article

---

### 6. `<aside>`

**Definition:**

The `<aside>` element contains side information related to the main content.

**Examples:**

* Related Links
* Advertisements
* Sidebars
* Author Information

---

### 7. `<footer>`

**Definition:**

The `<footer>` element represents the bottom section of the webpage.

**Used for:**

* Copyright information
* Contact information
* Social media links
* Privacy policy

---

## Complete Program

```html
<!DOCTYPE html>
<html>

<head>

    <title>Semantic Elements in HTML5 and CSS3</title>

    <style>

        header{

            background-color:lightblue;

            padding:20px;

            text-align:center;

        }

        nav{

            background-color:lightgray;

            padding:10px;

        }

        main{

            padding:20px;

        }

        aside{

            background-color:lightyellow;

            padding:10px;

            width:200px;

            float:right;

        }

        footer{

            background-color:lightgreen;

            padding:20px;

            text-align:center;

        }

    </style>

</head>

<body>

    <header>

        <h1>Welcome to My Website</h1>

    </header>


    <nav>

        <a href="#">Home</a> |

        <a href="#">About</a> |

        <a href="#">Contact</a>

    </nav>


    <main>

        <article>

            <h2>Article Title</h2>

            <p>

                This is the main content of the article.

                It can contain text, images and videos.

            </p>

        </article>

    </main>


    <aside>

        <h3>Related Links</h3>

        <ul>

            <li><a href="#">Link 1</a></li>

            <li><a href="#">Link 2</a></li>

            <li><a href="#">Link 3</a></li>

        </ul>

    </aside>


    <footer>

        &copy; 2026 My Website. All rights reserved.

    </footer>

</body>

</html>
```

---

## Explanation of the CSS

### Header Styling

```css
header{
    background-color:lightblue;
    padding:20px;
    text-align:center;
}
```

* Adds light blue background
* Adds inner spacing
* Centers the text

---

### Navigation Styling

```css
nav{
    background-color:lightgray;
    padding:10px;
}
```

Creates a navigation bar with spacing.

---

### Main Section

```css
main{
    padding:20px;
}
```

Creates spacing around the main content.

---

### Aside Section

```css
aside{
    background-color:lightyellow;
    width:200px;
    float:right;
    padding:10px;
}
```

Creates a sidebar aligned to the right side.

---

### Footer Styling

```css
footer{
    background-color:lightgreen;
    padding:20px;
    text-align:center;
}
```

Creates a footer section with centered content.

---

## Pseudocode

```text
START

Create HTML Document

Create Header Section

Create Navigation Menu

Create Main Content Area

Create Article

Create Sidebar

Create Footer

Apply CSS Styling

Display Webpage

END
```

---

## Output Summary

When executed in a browser:

* A light blue header appears at the top.
* A gray navigation bar appears below it.
* The main article content appears in the center.
* A light yellow sidebar appears on the right.
* A green footer appears at the bottom.

The webpage becomes clean, structured, and easy to understand.

---

## Semantic Elements vs Div Tag

| Semantic Elements    | Div Tag                 |
| -------------------- | ----------------------- |
| Meaningful           | Generic Container       |
| Better SEO           | Poor SEO                |
| Better Accessibility | Less Accessibility      |
| Easy to Read         | Difficult to Understand |
| Recommended in HTML5 | Old Layout Practice     |

---

## Advantages of Semantic Elements

✔ Better Search Engine Ranking

✔ Better Accessibility

✔ Cleaner Code Structure

✔ Easy Maintenance

✔ Improved Readability

✔ Screen Reader Friendly

✔ Modern HTML5 Standard

---

## Real-Time Applications

Semantic elements are used in:

* Company Websites
* Portfolio Websites
* Blogs
* E-Commerce Websites
* News Portals
* Educational Websites
* Dashboards
* Admin Panels

---

## Final Summary

Semantic Elements are one of the most important features introduced in HTML5.

They provide:

* Meaningful page structure
* Better SEO
* Better Accessibility
* Clean and Professional Code

Using `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>`, and `<footer>` is considered a best practice in modern Front-End Development and is widely used in HTML5, CSS3, Angular, and Java Full Stack applications.
