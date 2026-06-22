# 09 - Animations in CSS3

## Introduction

CSS3 Animations allow developers to animate HTML elements without using JavaScript.

Animations can change:

* Color
* Position
* Size
* Width
* Height
* Rotation
* Opacity
* Background Color

CSS3 animations create smooth visual effects and improve user experience.

---

## What is Animation in CSS3?

Animation is the process of changing one or more CSS properties of an element gradually over a period of time.

CSS3 provides:

1. `@keyframes`
2. `animation-name`
3. `animation-duration`
4. `animation-delay`
5. `animation-iteration-count`
6. `animation-direction`
7. `animation-timing-function`
8. `animation-fill-mode`
9. `animation` (Shorthand Property)

---

## @keyframes Rule

### Definition

`@keyframes` is used to define the different stages of an animation.

It specifies:

* Starting state (`from` or `0%`)
* Ending state (`to` or `100%`)
* Intermediate stages if required

### Syntax

```css
@keyframes animationName {

    from {
        property:value;
    }

    to {
        property:value;
    }

}
```

---

## Program: Background Color Animation

### HTML Program

```html
<!DOCTYPE html>
<html>

<head>

    <title>Animations in CSS3</title>

    <style>

        @keyframes example {

            from {

                background-color:red;

            }

            to {

                background-color:yellow;

            }

        }

        div{

            width:100px;

            height:100px;

            background-color:red;

            animation:example 5s infinite;

        }

    </style>

</head>

<body>

    <div></div>

</body>

</html>
```

---

## Explanation of the Program

### Step 1

```css
@keyframes example
```

Creates an animation named **example**.

---

### Step 2

```css
from{

    background-color:red;

}
```

Specifies the starting state.

The element begins with a red background.

---

### Step 3

```css
to{

    background-color:yellow;

}
```

Specifies the ending state.

The background color changes to yellow.

---

### Step 4

```css
animation:example 5s infinite;
```

This is the shorthand animation property.

It means:

* Animation Name → `example`
* Duration → `5 seconds`
* Iteration Count → `Infinite`

---

## Individual Animation Properties

### 1. animation-name

Specifies the name of the animation.

```css
animation-name: example;
```

---

### 2. animation-duration

Specifies how long one animation cycle takes.

```css
animation-duration:5s;
```

The animation completes one cycle in 5 seconds.

---

### 3. animation-delay

Specifies the waiting time before animation starts.

```css
animation-delay:2s;
```

Animation starts after 2 seconds.

---

### 4. animation-iteration-count

Specifies how many times the animation repeats.

```css
animation-iteration-count:infinite;
```

Other examples:

```css
animation-iteration-count:3;
```

Animation repeats 3 times.

---

### 5. animation-direction

Specifies the direction of animation.

```css
animation-direction:normal;
```

Possible values:

* normal
* reverse
* alternate
* alternate-reverse

---

### 6. animation-timing-function

Controls animation speed.

```css
animation-timing-function:linear;
```

Other values:

* ease
* ease-in
* ease-out
* ease-in-out
* linear

---

## Using Percentage in Keyframes

You can define multiple stages.

Example:

```css
@keyframes colors {

    0%{

        background:red;

    }

    50%{

        background:blue;

    }

    100%{

        background:green;

    }

}
```

The color changes:

Red → Blue → Green

---

## Pseudocode

```text
START

Create HTML Document

Define animation using @keyframes

Set starting background color

Set ending background color

Create div element

Set width and height

Apply animation

Display animation

END
```

---

## Output Summary

When the page runs:

* A square box appears.
* Width = 100px
* Height = 100px
* Background color starts as Red.
* Gradually changes to Yellow.
* Takes 5 seconds.
* Repeats forever.

---

## Real-Time Applications of CSS Animations

CSS Animations are widely used in:

* Loading Spinners
* Progress Bars
* Image Sliders
* Navigation Menus
* Hover Effects
* Notifications
* Buttons
* Web Banners
* Landing Pages
* Dashboards

---

## Advantages of CSS3 Animations

✔ No JavaScript Required

✔ Better User Experience

✔ Smooth Transitions

✔ Faster Performance

✔ Hardware Accelerated

✔ Lightweight

✔ Responsive

✔ Easy to Maintain

---

## Important Interview Questions

### Q1. What is CSS Animation?

CSS Animation is used to change the style of an element gradually over time.

---

### Q2. What is @keyframes?

`@keyframes` defines the stages of an animation.

---

### Q3. Which property specifies animation duration?

```css
animation-duration
```

---

### Q4. Which property repeats animation forever?

```css
animation-iteration-count: infinite;
```

---

### Q5. Which property combines all animation properties?

```css
animation
```

It is called the shorthand animation property.

---

## Final Summary

CSS3 Animations provide a powerful way to create dynamic and attractive web pages.

Using:

* `@keyframes`
* `animation`
* `animation-duration`
* `animation-delay`
* `animation-iteration-count`
* `animation-direction`

developers can create smooth animations without using JavaScript.

CSS Animations are an important topic for Front-End Development, Angular Applications, and Java Full Stack Development.
