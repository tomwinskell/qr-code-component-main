# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

Basic HTML and CSS QR code component

### Screenshot

![Screenshot 2024-09-23.jpg](./Screenshot 2024-09-23.jpg)

### Links

- Solution URL: [https://github.com/tomwinskell/qr-code-component-main](https://github.com/tomwinskell/qr-code-component-main)
- Live Site URL: [https://tomwinskell.github.io/qr-code-component-main/](https://tomwinskell.github.io/qr-code-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Cursor

### What I learned

Learned to use variables to store colors and re-use them later in css file. Div with spacing class name and re-use. Border-box property for padding inside the box.

```html
<div class="space-200"></div>
```

```css
:root {
  --white: hsl(0, 0%, 100%);
  --slate-300: hsl(212, 45%, 89%);
  --slate-500: hsl(216, 15%, 48%);
  --slate-900: hsl(218, 44%, 22%);
}

body {
  background-color: var(--slate-300);
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
```
