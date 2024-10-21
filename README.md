# CSS Flexbox

This repository demonstrates the use of CSS Flexbox to create responsive layouts for five different page designs. Each page showcases a unique real-world use case for Flexbox layout properties.

## Introduction

CSS Flexbox (Flexible Box Layout) is a layout model that provides a more efficient way to arrange and distribute space among items in a container, even when their size is unknown or dynamic. It allows for responsive design by enabling items to grow or shrink to fill available space, aligning them along a single axis, either horizontally or vertically.

## CSS Flexbox Definition

CSS Flexbox (Flexible Box Layout) is a layout model that provides a more efficient way to arrange and distribute space among items in a container, even when their size is unknown or dynamic. It allows for responsive design by enabling items to grow or shrink to fill available space, aligning them along a single axis, either horizontally or vertically.

### Key Features of Flexbox

- **Alignment**: Easily align items along the main axis and cross axis.
- **Direction**: Control the direction of the layout (row, column, row-reverse, column-reverse).
- **Order**: Rearrange items without changing the HTML.
- **Responsive**: Automatically adjusts layout to fit different screen sizes.

## Layouts Included
1. Product Layout
The Product Layout showcases a grid of products, each displayed with its image, name, and price. This layout is designed to facilitate browsing and selecting products effectively.

2. Employee Layout
The Employee Cards layout features cards that display essential employee information such as their name, photo, and job title. This layout helps in presenting employee details in a visually appealing manner.

3. Student Layout
The Student Profiles layout provides profile cards showcasing student information, including their name, photo, and details. This layout is useful for educational institutions to display student data.

4. Course Layout
The Course Overview layout lists available courses with brief descriptions. This layout aids in presenting educational offerings clearly and concisely.

5. Blog Layout
The Blog Post Layout displays multiple posts with titles, descriptions, and images. This layout is ideal for showcasing blog content in an organized manner, making it easy for readers to navigate.

## Flexbox Implementation

To implement Flexbox in your CSS, set the `display` property of the container to `flex` or `inline-flex`. Here is a basic example:

```css
.container {
    display: flex;
    flex-direction: row; /* or column */
    justify-content: center; /* Align items horizontally */
    align-items: center; /* Align items vertically */
}

