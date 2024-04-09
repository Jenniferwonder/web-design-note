---
Title: CSS Images, media and form elements
Type: D
tags:
  - CSS
status: 
DateStarted: 2023-09-21
DateModified: 2023-09-23
DateDone: 2023-09-21T00:00:00.000+08:00
Difficulty: Good
Reviewed: 2
DateReviewed: 2024-01-19T00:00:00.000+08:00
Comment: ⭐⭐⭐
Topic:
  - Sizing
---

# CSS Images, videos and other replaced elements

## Replaced elements

### a replaced element is **an element whose representation is outside the scope of CSS**

### The **position** of the replaced element can be affected using CSS, but not the **contents**

### having an aspect ratio will be displayed using the intrinsic dimensions of the file by defaul

### Reference: https://developer.mozilla.org/en-US/docs/Web/CSS/Replaced_element

### Replaced elements in layout

- replaced elements, when they become part of a grid or flex layout, have different default behaviors

## Sizing images

### Responsive image

- `max-width: 100%`
  - to prevent image overflow while retaining aspect ratio
- `height: auto`
- [Responsive Image Techniques](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

### `object-fit`

- `object-fit: cover`
  - ![](z-Assets/Paste%20image%201695297488732image.png)
- `object-fit: contain`
  - ![](z-Assets/Paste%20image%201695297501729image.png)
- `object-fit: fill`
  - fill the box without keeping aspect ratio
