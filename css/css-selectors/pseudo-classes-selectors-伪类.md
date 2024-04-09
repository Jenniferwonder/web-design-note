---
Title: pseudo-classes selectors (伪类)
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
Difficulty: Hard
---
## pseudo-classes selectors (伪类)

### Style **certain states** of an element
- as if you had added a class for that state to the DOM

### User-action Pseudo Class (Anchor element states)
- [Styling Links](Styling%20Links.md)

### Structural
- `:root`
- `:empty`
    - Selects elements that have no children or text content

### Child
- `:first-child`
- `:last-child`
- `:only-child`
- `tbody tr:nth-child(odd) { }`
    - [Table Style](Table%20Style.md)

### Type Child
- `:first-of-type`
- `:last-of-type`
- `:nth-of-type(n)`

### Link
- `:link`
- `:visited`
- `:hover`
- `:active`

### Form-related
- `:focus`
- `:focus-visible`
	- `outline: 4px auto -webkit-focus-ring-color`
- `:checked`
- `:disabled`
- `:enabled`
- `:valid`
- `:invalid`
- `:required`
- `:optional`

### 📌  It is valid to write pseudo-classes and elements without any element selector preceding them
- the rule would apply to any element that belongs to the class