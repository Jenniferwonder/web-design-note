---
Title: Fundamental text and font styling
Type: D
tags:
  - CSS
status:
DateStarted: 2023-09-21T00:00:00.000+08:00
DateModified: 2023-09-23
mindmap-plugin: basic
DateDone: 2023-09-22T00:00:00.000+08:00
DateReviewed: 2024-01-19T00:00:00.000+08:00
Comment: ⭐⭐⭐
Reviewed: 3
Difficulty: Hard
Topic: Text
---

# Typography

## Fonts

### `font-family`

- 📌[Google Fonts](https://fonts.google.com/)

```html
<link
	href="https://fonts.googleapis.com/css?family=Rock+Salt"
	rel="stylesheet"
	type="text/css"
/>
```

- Web safe fonts
  - 📌[cssfontstack.com](https://www.cssfontstack.com/)
    - maintains a list of web safe fonts available
- Default fonts
  - CSS defines five generic names for fonts: `serif`, `sans-serif`, `monospace`, `cursive`, and `fantasy`
- Font stacks

### `font-size`

- [CSS Values and Units](CSS%20Values%20and%20Units.md)
- ⭐Fluid/ responsive typography
  - `font-size: clamp(48px, 4.8vw, 64px);`
    - the minimum size
    - the preferred size
    - the maximum size

### `line-height`

- Line height
- [CSS Values and Units](CSS%20Values%20and%20Units.md)

### `font-weight`

- `normal`, `bold`
- `lighter`, `bolder`
- `100`-`900`

### `font-style`

- `normal`
- `italic`
- `oblique`

### `font-variant`

- Switch between small caps and normal font alternatives

### `font-stretch`

- Switch between possible alternative stretched versions of a given font

### Font shorthand

- written in the following order: `font-style`, `font-variant`, `font-weight`, `font-stretch`, `font-size`/`line-height`, and `font-family`
  - `font: italic normal bold normal 3em/1.5 Helvetica, Arial, sans-serif;`

### `color`

## Text Style

### `text-transform`

- `uppercase`, `lowercase`
- `capitalize`
- `full-width`
- `none`

### `text-decoration`

- `none`
- `underline`
- `overline`
- `line-through`
- can accept multiple values at once
  - `text-decoration: underline overline`

### `text-shadow`

- `text-shadow: 4px 4px 5px red;`
- horizontal, vertical, blur radius, base color of the shadow
- can apply multiple shadows
  - ![](z-Assets/Paste%20image%201695304143112image.png)
- 📌[Box Shadow](Box%20Shadow.md)

## Text Layout

### `text-align`

- `left`, `right`, `center`
- `justify`
  - Makes the text spread out, varying the gaps in between the words so that all lines of text are the same width

### `letter-spacing`

### `word-spacing`

### [CSS Text Directions](CSS%20Text%20Directions.md)

- `writing-mode`

### [CSS Overflowing Content](CSS%20Overflowing%20Content.md)

- `overflow-wrap`

## 📌 Reference: https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals
