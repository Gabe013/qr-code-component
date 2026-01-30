# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).
Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

Used pure HTML and CSS to build a QR code component based on the design provided in the challenge.
The CSS technique used is Flexbox to center and align the elements on the page without any particular responsive design-related CSS.

### Screenshot

![QR Code Component for Desktop by Gabriel Mesaros](/images/screenshot-desktop.png)

## Links

[**Github repository**](https://github.com/Gabe013/qr-code-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I figured out that I just needed to add a certain `"vhxyz"` as the value of the `height`property in the `body` selector to achieve element centering on the page. _(Thanks to Google Gemini SRE AI tool response)_
In this case, I set the relevant selector's `height` declaration to `90vh`.

Code of the respective selector:

```css
body {
  background-color: var(--color-slate-300);
  width: fit-content;
  max-width: 1444px;
  min-width: 375px;
  margin: 0 auto;
  display: flex;
  flex-flow: column;
  justify-content: center;
  align-items: center;
  height: 90vh;
  /* ensures parent container's children are centered on all screens and devices by taking 90% of the viewport (made by Gemini via Google SRE at suggested 100%, but I decreased it to 80vh to push the `main` container up a bit) */
}
```

### Continued development

I will revisit the CSS and Flexbox lessons from [The Odin Project](https://www.theodinproject.com/paths/foundations/courses/foundations#css-foundations) and think thoroughly first when using it again in similar projects.

## Author

- Website (GH Pages) - [Gabe's QR Code Component](https://github.com/Gabe013/qr-code-component/deployments/github-pages)