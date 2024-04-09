---
Title: Styling Lists
Type: D
tags:
  - CSS
status:
DateStarted: 2023-09-22
DateModified: 2023-09-23
mindmap-plugin: basic
DateDone: 2023-09-22T00:00:00.000+08:00
Comment: ⭐⭐
DateReviewed: 2023-09-23T00:00:00.000+08:00
Reviewed: 1
Difficulty: Hard
Topic: Text
---

# Styling Lists

## List Types

### **Ordered list**

- `ol`
- 📌have a top and bottom margin of 16px (1em) and a padding-left of 40px (2.5em)
- ![](z-Assets/Paste%20image%201695359623245image.png)

### **Unordered list**

- `ul`
- 📌have a top and bottom margin of 16px (1em) and a padding-left of 40px (2.5em)
- ![](z-Assets/Paste%20image%201695359559748image.png)

### **List element**

- `li`
- 📌have no set defaults for spacing.

### **Description list**

- `dl`
- **`dt`**
  - description terms in `dl`
- **`dd`**
  - description details in `dl`, after `dt`
  - 📌have margin-left of 40px (2.5em).
- 📌has a top and bottom margin of 16px (1em), but no padding set.
- ![](z-Assets/Paste%20image%201695359663654image.png)

## List Spacing

### `font-size`

### `line-height`

### `font-weight`

## List-specific styles

### **`list-style-type`**

- 📌Sets the type of bullets to use
- 📌[List style values](https://developer.mozilla.org/en-US/docs/Web/CSS/list-style-type)
  - for unordered list
    - `circle`
      - A hollow circle
    - `disc`
      - A filled circle (by default)
    - `square`
    - Or use [@counter-style](https://developer.mozilla.org/en-US/docs/Web/CSS/@counter-style)
  - for ordered list
    - `decimal`
      - begin with `1.`
    - `decimal-leading-zero`
      - Decimal numbers, padded by initial zeros.
    - `lower-alpha`, `lower-latin` or `upper-alpha`, `upper-latin`
      - ASCII letters
    - `simp-chinese-formal` or `simp-chinese-informal`
    - `lower-roman` or `upper-roman`

### **`list-style-position`**

- **`inside`**
  - ![](z-Assets/Paste%20image%201695361307475image.png)
- **`outside`**
  - ![](z-Assets/Paste%20image%201695361275290image.png)

### Use a custom bullet image

- **`list-style-image`**
  - 📌use a custom image for your bullet
  - ⚠️is a bit limited in terms of controlling the position, size, etc. of the bullets (better using `background` properties)
  - `list-style-image: url(star.svg);`
- ![](z-Assets/Paste%20image%201695361727361image.png)

### List-style shorthand

- `list-style`
- The above mentioned three property values in any order

## Controlling list counting

### `start`

### `reversed`

### `value`
