# CSS3 Interview Questions and Answers

This file contains important CSS3 interview questions and answers for beginners and Java Full Stack Developer aspirants.

---

## 1. What is CSS?

CSS stands for Cascading Style Sheets.

It is used to style HTML elements and control:

- Colors
- Fonts
- Borders
- Layouts
- Margins
- Padding
- Animations
- Responsive designs

---

## 2. Who invented CSS?

CSS was invented by Håkon Wium Lie in 1994.

---

## 3. What are the types of CSS?

There are three types of CSS:

1. Inline CSS
2. Internal CSS
3. External CSS

---

## 4. What is Inline CSS?

Inline CSS is written directly inside an HTML element using the style attribute.

Example:

```html
<h1 style="color:red;">Hello</h1>
```

---

## 5. What is Internal CSS?

Internal CSS is written inside the `<style>` tag in the `<head>` section.

Example:

```html
<style>
h1{
color:red;
}
</style>
```

---

## 6. What is External CSS?

External CSS is written in a separate `.css` file and linked to HTML.

Example:

```html
<link rel="stylesheet" href="style.css">
```

---

## 7. Which CSS type is recommended?

External CSS.

Because:

- Reusable
- Easy maintenance
- Clean code
- Faster development

---

## 8. What is CSS Syntax?

```css
selector{
property:value;
}
```

Example:

```css
h1{
color:blue;
}
```

---

## 9. What is a Selector in CSS?

A selector is used to select HTML elements for styling.

---

## 10. What are the types of selectors?

1. Universal Selector (*)
2. Element Selector
3. ID Selector
4. Class Selector
5. Group Selector
6. Pseudo Class Selector
7. Pseudo Element Selector

---

## 11. What is Universal Selector?

It selects all elements.

```css
*{
margin:0;
padding:0;
}
```

---

## 12. What is Element Selector?

It selects elements by tag name.

```css
p{
color:red;
}
```

---

## 13. What is ID Selector?

It selects a unique element using #.

```css
#student{
color:blue;
}
```

---

## 14. What is Class Selector?

It selects multiple elements using dot (.).

```css
.course{
color:green;
}
```

---

## 15. Difference between ID and Class Selector?

| ID | Class |
|-----|-------|
| Unique | Reusable |
| Uses # | Uses . |
| One element | Multiple elements |

---

## 16. What is Pseudo Class?

Pseudo classes define special states of elements.

Examples:

```css
:hover
:active
:visited
:link
```

---

## 17. What is :hover?

It applies style when mouse pointer moves over an element.

```css
button:hover{
background-color:gray;
}
```

---

## 18. What is :visited?

It styles already visited links.

---

## 19. What is Pseudo Element?

Pseudo elements style specific parts of an element.

Examples:

```css
::before
::after
::first-letter
::first-line
```

---

## 20. What is ::before?

It inserts content before an element.

```css
li::before{
content:"•";
}
```

---

## 21. What is ::after?

It inserts content after an element.

```css
p::after{
content:"©";
}
```

---

## 22. What is Div Tag?

`<div>` is a block-level container.

Used for:

- Layout creation
- Grouping elements
- Applying CSS

---

## 23. What is Span Tag?

`<span>` is an inline element.

Used for:

- Styling text
- Coloring words
- Formatting small sections

---

## 24. Difference between Div and Span?

| Div | Span |
|------|------|
| Block Level | Inline |
| Starts new line | Same line |
| Used for layout | Used for text |

---

## 25. What is Border in CSS?

Border is used to create outlines around elements.

Syntax:

```css
border:2px solid red;
```

---

## 26. What are border styles?

- solid
- dotted
- dashed
- double
- groove
- ridge
- inset
- outset

---

## 27. What is Margin?

Margin is the space outside the border.

Example:

```css
margin:20px;
```

---

## 28. What is Padding?

Padding is the space inside the border.

Example:

```css
padding:20px;
```

---

## 29. Difference between Margin and Padding?

| Margin | Padding |
|---------|---------|
| Outside Border | Inside Border |
| Creates outer spacing | Creates inner spacing |

---

## 30. What is CSS Box Model?

CSS Box Model consists of:

```text
Margin
Border
Padding
Content
```

---

## 31. What is text-transform property?

Used to change text case.

Values:

```css
uppercase
lowercase
capitalize
```

---

## 32. What is uppercase?

Converts all letters into capital letters.

---

## 33. What is lowercase?

Converts all letters into small letters.

---

## 34. What is capitalize?

Capitalizes first letter of each word.

---

## 35. What are Semantic Elements?

Semantic elements describe the meaning of content.

Examples:

```html
<header>
<nav>
<main>
<section>
<article>
<aside>
<footer>
```

---

## 36. Why Semantic Elements are used?

- Better SEO
- Better Accessibility
- Clean Code
- Easy Maintenance

---

## 37. What is Navigation Bar?

Navigation bar is a group of hyperlinks used to navigate between pages.

---

## 38. Types of Navigation Bars?

1. Horizontal Navigation Bar
2. Vertical Navigation Bar

---

## 39. Which property creates Vertical Navigation Bar?

```css
display:block;
```

---

## 40. What is display:block?

It makes an element behave as a block element.

Starts on new line.

---

## 41. What is display:inline?

Makes element stay on same line.

---

## 42. What are Block Level Elements?

Elements that start on a new line.

Examples:

```html
<div>
<p>
<h1>
<form>
<section>
<table>
```

---

## 43. What are Inline Elements?

Elements that do not start on a new line.

Examples:

```html
<span>
<a>
<b>
<i>
<img>
<label>
```

---

## 44. Difference between Block and Inline Elements?

| Block | Inline |
|-------|--------|
| New Line | Same Line |
| Width & Height allowed | Width & Height ignored |
| Takes full width | Takes content width |

---

## 45. What is Animation in CSS3?

Animation changes element styles gradually over time.

---

## 46. What is @keyframes?

It defines animation stages.

Example:

```css
@keyframes example{

from{
background:red;
}

to{
background:yellow;
}

}
```

---

## 47. What is animation property?

Used to apply animation.

Example:

```css
animation:example 5s infinite;
```

---

## 48. What is animation-duration?

Defines animation speed.

Example:

```css
animation-duration:5s;
```

---

## 49. What is animation-iteration-count?

Defines number of repetitions.

Example:

```css
animation-iteration-count:infinite;
```

---

## 50. What are CSS Transforms?

Transforms change the shape, size, angle or position of elements.

Examples:

```css
rotate()
scale()
translate()
```

---

## 51. What is rotate()?

Rotates an element.

```css
transform:rotate(45deg);
```

---

## 52. What is scale()?

Changes element size.

```css
transform:scale(1.5);
```

---

## 53. What is translateX()?

Moves element horizontally.

```css
transform:translateX(100px);
```

---

## 54. Which CSS type is mostly used in real projects?

External CSS.

---

## 55. Why CSS is called Cascading Style Sheets?

Because styles are applied according to priority rules called Cascading.

Priority:

```text
Inline CSS
↓
Internal CSS
↓
External CSS
↓
Browser Default Styles
```

---

## Frequently Asked Fresher Questions

1. What is CSS?
2. Types of CSS?
3. Difference between ID and Class?
4. Difference between Margin and Padding?
5. Difference between Div and Span?
6. Difference between Block and Inline Elements?
7. What is Box Model?
8. What is Animation?
9. What is @keyframes?
10. What is transform property?
11. What is :hover?
12. What is ::before?
13. What is display:block?
14. What are Semantic Elements?
15. Difference between Internal and External CSS?

---

# Conclusion

These CSS3 Interview Questions and Answers cover beginner to intermediate level concepts including CSS basics, selectors, box model, semantic elements, navigation bars, animations, transforms, block-level elements, and inline elements.

This file is useful for:

- Java Full Stack Developer Interviews
- Front-End Developer Interviews
- Fresher Interviews
- Quick Revision
- GitHub Learning Repository

⭐ Happy Learning and Keep Coding!
