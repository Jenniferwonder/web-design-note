---
Title: Attribute Selector
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
DateReviewed: 2024-01-09T00:00:00.000+08:00
Topic: Selectors
Difficulty: Good
---
## Attribute Selector

### `a[title] {}`
- select elements based on **a certain attribute on an element**

### `a[href="https://example.com"] {}`
- make a selection based on **the presence of an attribute with a particular value**

### `p[class~="special"]`
- Matches elements with an attribute whose value is **exactly value, or contains value in its (space separated) list of values**.

### `div[lang|="zh"]`
- Matches elements with an attribute whose value is **exactly value or begins with value immediately followed by a hyphen**.

### `li[class^="box-"]`
- Matches elements with an attribute, whose value **begins with value**.

### `li[class$="-box"]`
- Matches elements with an attr attribute whose value **ends with value**.

### `li[class*="box"]`
- Matches elements with an attr attribute whose value **contains value anywhere within the string**.

### 📌 To match **case-insensitive**
- use the value `i `before the closing bracket
- `li[class^="a" i] { }`