---
Title: Styling Links
Type: D
tags:
  - CSS
DateStarted: 2023-09-22
DateModified: 2023-09-23
status:
mindmap-plugin: basic
DateDone: 2023-09-22T00:00:00.000+08:00
Comment: ⭐⭐
DateReviewed: 2023-09-23T00:00:00.000+08:00
Reviewed: 1
Difficulty: Hard
Topic: Text
---

# Styling Links

## Reference 
- [Styling Links](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Styling_links#lets_look_at_some_links)

## Link states & Default styles

### **a**

- `<a href="http://example.com">link</a>`
- Select the anchor element

### **:link**

- A link that has a destination (i.e., not just a named anchor)
- 📌Links are underlined.

### **:visited**

- unvisited, visited
- 📌Unvisited links are blue. Visited links are purple.

### **:focus**

- focused via the keyboard
- 📌Focused links have an outline around them

### **:hover**

- being hovered over
- 📌Hovering a link makes the mouse pointer change to a little hand icon.

### **:active**

- ! When a button is clicked
- in the process of being clicked (activated)
- 📌Active links are red

### ⭐ The above order matters when styling links, cuz link styles build on one another

## To change default styles

### `color`

### `cursor`

- mouse pointer style

### `outline`

- text outline, similar to a border

### `background`

### Refer to [Typography](Typography.md)

- `text-align`
- `line-height`
- `text-decoration`

## Including icons on links

### ![](z-Assets/Paste%20image%201695366049825image.png)

### specify the position as 100% of the way to the right of the text content, and 0 pixels from the top.

### Refer to [CSS Selectors](CSS%20Selectors.md)

## Styling links as buttons
