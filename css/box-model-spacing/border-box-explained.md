---
Title: Border-Box Explained
Type: D
tags:
  - CSS
DateStarted: 2024-01-09
DateModified: 2024-01-09
DateDo:
DateDone: 2024-01-09T00:00:00.000+08:00
DateDue:
status:
Reviewed: 1
DateReviewed: 2024-01-19T00:00:00.000+08:00
Topic: Box
Difficulty: Good
Comment: ⭐⭐
---

## Border-Box Explained

### ⭐Standard CSS Box Model

- ![](<z-Assets/CSS%20Box%20Model%20(盒模型)-Standard%20CSS%20Box.png>)

### ⭐Alternative CSS Box Model

- border-box
- `box-sizing: border-box`
  - ![](<z-Assets/CSS%20Box%20Model%20(盒模型)-Border%20Box.png>)
- 📌[Base Styles](Base%20Styles.md)
- 📌To use the alternative box model for all of your elements (which is a common choice among developers)

  ```css
    html {
    	box-sizing: border-box;
    }
    *,
    *::before,
    *::after {
    	box-sizing: inherit;
    }
    ```

  - separates the reset from the global styling of all elements
    - explicitly sets the box-sizing for the root element and lets the rest inherit it
    - can be seen as a form of organization, especially if you have other global styles applied to the `<html>` element
