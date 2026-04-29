# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Solution](https://github.com/vince4dev/challenge1)
- Live Site URL: [Live site](https://vince4dev.github.io/challenge1)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

As part of this challenge, I had the opportunity to design a web page completely from scratch, using HTML and CSS. This allowed me to practice my skills and learn new techniques.

Key points learned:

- Custom Font with @font-face: In this project, I created a custom font using the @font-face property. This allowed me to choose my font characteristics and apply them throughout my site. I can now customize the fonts on my site to give it a unique identity.
- Using CSS variables: I also used CSS variables to store reusable values ​​in my code. In this case, I created a variable --c-slate-900 that represents the HSL color (218, 44%, 22%) that I want to use repeatedly on my page. This allowed me to reduce the number of lines of code and improve the readability of my code.

```css
/* outfit-regular - latin */
@font-face {
  font-display: swap; /* Check https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/font-display for other options. */
  font-family: "Outfit";
  font-style: normal;
  font-weight: 400;
  src: url("../fonts/outfit-v15-latin-regular.woff2") format("woff2"); /* Chrome 36+, Opera 23+, Firefox 39+, Safari 12+, iOS 10+ */
}

:root {
  /* Colors */
  --c-slate-900: hsl(218, 44%, 22%);
  ...

  /* Fonts Size */
  --fs-22: calc(22 / 16 * 1rem);
  ...

  /* Fonts Weight */
  --fw-bold: 700;
  ...

  .card__title {
    font-weight: var(--fw-bold);
    color: var(--c-slate-900);
    font-size: var(--fs-22);
  }
}
```

## Author

- Frontend Mentor - [@vince4dev](https://www.frontendmentor.io/profile/vince4dev)
