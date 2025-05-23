# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](./screenshot.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Each browser has its own styles that it applies to our web page which can hinder our design it is best to include below lines to avoid unexpected results.
Also early adoption of industry best practices to include colors as variables to be used in the entire project in :root and to download the fonts to avoid breaking WCAG regulations.

```css
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

:root {
  --white: hsl(0, 0%, 100%);
  --slate-300: hsl(212, 45%, 89%);
  --slate-500: hsl(216, 15%, 48%);
  --slate-900: hsl(218, 44%, 22%);
  font-family: "Outfit";
}

@font-face {
  font-display: swap;
  font-family: "Outfit";
  font-style: normal;
  font-weight: 400;
  src: url("./fonts/outfit-v11-latin-regular.woff2") format("woff2");
}

@font-face {
  font-display: swap;
  font-family: "Outfit";
  font-style: normal;
  font-weight: 700;
  src: url("./fonts/outfit-v11-latin-700.woff2") format("woff2");
}
```

### Continued development

Currently in this project there was no responsive content, would like to work more on it in the future.

### Useful resources

- [Font Downloader](https://gwfh.mranftl.com/fonts) - This resource helped me to download and install the fonts needed. I really liked the ease of it and will use it going forward.

## Author

- Frontend Mentor - [@akshitjain3](https://www.frontendmentor.io/profile/akshitjain3)
