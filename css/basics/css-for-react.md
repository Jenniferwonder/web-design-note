---
DateDue: 
Title: CSS for React
Type: D
tags:
  - CSS
DateStarted: 2024-01-08
DateModified: 2024-01-10
DateDo: 
DateDone: 
status: 
mindmap-plugin: basic
Topic: Basics
Comment: ⭐⭐⭐
Difficulty: Hard
---

# CSS for React

## Reference

### https://www.freecodecamp.org/news/how-to-style-react-apps-with-css/

### https://blog.devgenius.io/best-ways-to-style-a-react-js-application-c818b71f6341

### 📌[O-React](obsidian://open?vault=Front-End%20Frameworks&file=React%2FO-React%2FO-React)

## Folder Structure

### `src`
- `components`
- `containers`
- `data`
- `pages`
- `context`

### `public`

## Practice

### Global CSS
- 📌[Base Styles](Base%20Styles.md)

### Using normal CSS
- Module CSS
- `import './styles.css'`
- `<img className="avatar" />`
    - `className` 相当于 html `class`
- Open Props
    - https://open-props.style/#getting-started
    - [Open-Props Normalize Demo Page, aka Everything But The Bagel (codepen.io)](https://codepen.io/argyleink/pen/KKvRORE)

### Inline CSS
- Utility Class
    - 📌[O-TailwindCSS](O-TailwindCSS.md)
- `style={{
                   width: user.imageSize, height: user.imageSize, }}`

### [UI Componenet Library](UI%20Componenet%20Library.md)
- 💡Pre-styled components
    - ❌Difficult to customize
    - material-ui
    - react-bootstrap
    - chakra
    - react-select
- 💡Unstyled components
    - Hooks version
        - react-aria
            - backed by Adobe
        - downshift.js
    - Components version
        - base-ui
        - ✅radix-ui
            - Projects Examples
                - cal.com
                - steven-tey/dub (dub.sh)
                    - radix
                    - tailwind
        - headless-ui
        - reach-ui
- 💡Templates for styles
    - ShadCN