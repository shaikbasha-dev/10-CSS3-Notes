# 05 - Borders in CSS3

## Introduction

Borders in CSS3 are used to create visible outlines around HTML elements. Borders help separate content, improve page design, and create visually attractive layouts.

CSS provides several border styles ranging from simple flat borders to 3D border effects.

---

## 1. Border Property

### Definition

The `border` property is a shorthand property used to define:

* Border Width
* Border Style
* Border Color

### Syntax

```css
border: width style color;
```

### Example

```css
border: 2px solid black;
```

This means:

* Width → 2px
* Style → solid
* Color → black

---

## 2. Border Styles in CSS3

CSS3 supports the following border styles:

1. solid
2. dotted
3. dashed
4. double
5. groove
6. ridge
7. inset
8. outset

---

### 1. Solid Border

Creates a continuous straight line.

```css
border: 2px solid black;
```

---

### 2. Dotted Border

Creates a border made of dots.

```css
border: 2px dotted red;
```

---

### 3. Dashed Border

Creates a border made of dashes.

```css
border: 2px dashed blue;
```

---

### 4. Double Border

Creates two parallel border lines.

```css
border: 4px double green;
```

---

### 5. Groove Border

Creates a carved 3D border effect.

```css
border: 3px groove orange;
```

---

### 6. Ridge Border

Creates a raised 3D border effect.

```css
border: 3px ridge purple;
```

---

### 7. Inset Border

Creates a border that appears pressed inward.

```css
border: 3px inset gray;
```

---

### 8. Outset Border

Creates a border that appears raised outward.

```css
border: 3px outset brown;
```

---

## Complete Program

```html
<!DOCTYPE html>
<html>

<head>

    <title>Borders in CSS3</title>

    <style>

        /* Default Border */

        p{

            border:2px solid black;

        }

        /* Dotted Border */

        p.dotted{

            border:2px dotted red;

        }

        /* Dashed Border */

        p.dashed{

            border:2px dashed blue;

        }

        /* Double Border */

        p.double{

            border:4px double green;

        }

        /* Groove Border */

        p.groove{

            border:3px groove orange;

        }

        /* Ridge Border */

        p.ridge{

            border:3px ridge purple;

        }

        /* Inset Border */

        p.inset{

            border:3px inset gray;

        }

        /* Outset Border */

        p.outset{

            border:3px outset brown;

        }

    </style>

</head>

<body>

    <p>
        This is a solid border.
    </p>

    <p class="dotted">
        This is a dotted border.
    </p>

    <p class="dashed">
        This is a dashed border.
    </p>

    <p class="double">
        This is a double border.
    </p>

    <p class="groove">
        This is a groove border.
    </p>

    <p class="ridge">
        This is a ridge border.
    </p>

    <p class="inset">
        This is an inset border.
    </p>

    <p class="outset">
        This is an outset border.
    </p>

</body>

</html>
```

---

## Explanation of the Program

### `border:2px solid black;`

Creates:

* Width → 2px
* Style → solid
* Color → black

This border is applied to all paragraphs.

---

### `p.dotted`

```css
p.dotted{

border:2px dotted red;

}
```

Applies a red dotted border to:

```html
<p class="dotted">
```

---

### `p.dashed`

```css
p.dashed{

border:2px dashed blue;

}
```

Creates a blue dashed border.

---

### `p.double`

```css
p.double{

border:4px double green;

}
```

Creates two green border lines.

---

### `p.groove`

```css
p.groove{

border:3px groove orange;

}
```

Creates a carved 3D border.

---

### `p.ridge`

```css
p.ridge{

border:3px ridge purple;

}
```

Creates a raised 3D border.

---

### `p.inset`

```css
p.inset{

border:3px inset gray;

}
```

Makes the element appear pressed inward.

---

### `p.outset`

```css
p.outset{

border:3px outset brown;

}
```

Makes the element appear raised outward.

---

## Border Styles Summary Table

| Border Style | Description           |
| ------------ | --------------------- |
| solid        | Single straight line  |
| dotted       | Dotted line           |
| dashed       | Dashed line           |
| double       | Double line           |
| groove       | Carved 3D border      |
| ridge        | Raised 3D border      |
| inset        | Pressed inward border |
| outset       | Raised outward border |

---

## Flat Borders vs 3D Borders

| Flat Borders | 3D Borders |
| ------------ | ---------- |
| solid        | groove     |
| dotted       | ridge      |
| dashed       | inset      |
| double       | outset     |

---

## Pseudocode

```text
START

Create HTML Document

Create Internal CSS

Apply default solid border

Apply dotted border

Apply dashed border

Apply double border

Apply groove border

Apply ridge border

Apply inset border

Apply outset border

Display paragraphs

END
```

---

## Output Summary

When executed in a browser:

* Paragraph 1 → Solid Black Border
* Paragraph 2 → Red Dotted Border
* Paragraph 3 → Blue Dashed Border
* Paragraph 4 → Green Double Border
* Paragraph 5 → Orange Groove Border
* Paragraph 6 → Purple Ridge Border
* Paragraph 7 → Gray Inset Border
* Paragraph 8 → Brown Outset Border

Each paragraph demonstrates a different CSS3 border style.

---

## Real-Time Usage of Borders

Borders are commonly used in:

* Login Forms
* Registration Forms
* Cards
* Buttons
* Navigation Bars
* Tables
* Profile Boxes
* Dashboard Components

---

## Final Summary

CSS3 Borders are an important part of web design. They help developers create attractive and structured webpages by adding visible outlines around elements.

By learning:

* Border Shorthand Property
* Solid Border
* Dotted Border
* Dashed Border
* Double Border
* Groove Border
* Ridge Border
* Inset Border
* Outset Border

developers can build professional-looking user interfaces for Front-End Development and Java Full Stack applications.
