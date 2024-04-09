---
Type: Note
Title: HTML-Input and label
tags: HTML
DateStarted: 2022-12-06
DateModified: 2023-07-08
status: null
EST: NaN
LeadTime: NaN
Page-D: NaN
Cards-D: NaN
---

> [The Input (Form Input) element - HTML | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input)

## Questions

- `input type - button` and `button element`?

## How to use?

```html
<label for="name">Name (4 to 8 characters):</label>
<input
	type="text"
	id="name"
	name="name"
	required
	minlength="4"
	maxlength="8"
	size="10"
/>
```

## JS Method

```js
guessField.disabled = false;
guessSubmit.disabled = false;
guessField.focus();
guessField.value = "";
```

## Basics
- type
- id
- name
- minlength
- maxlength
- min
- max
- value
- required
- disabled
