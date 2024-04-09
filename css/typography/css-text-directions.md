---
Title: CSS Text Directions
Type: D
tags:
  - CSS
status: 
DateStarted: 2023-09-20
DateModified: 2023-09-23
DateDone: 2023-09-20T00:00:00.000+08:00
Difficulty: Good
Reviewed: 1
DateReviewed: 2023-09-23T00:00:00.000+08:00
Comment: ⭐
Topic:
  - Text
---

# CSS Text Directions

## Writing Modes

### `writing-mode: horizontal-tb/ vertical-rl/ vertical-lr`
- setting the direction in which block-level elements are displayed on the page — either from top-to-bottom, right-to-left, or left-to-right

### 📌the block dimension is always the direction blocks are displayed on the page in the writing mode in use.

### 📌The inline dimension is always the direction a sentence flows.

## Logical Properties and Values

### `width` > **`inline-size`**

### `height` > **`block-size`**

### `margin-top` > **`margin-block-start`**

### `border-bottom` > **`border-block-end`**

### `padding-left` > **`padding-inline-start`**

### 📌 Reference: [Logical Properties and Values](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_logical_properties_and_values)