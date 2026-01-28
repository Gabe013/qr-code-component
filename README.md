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

I figured out that I just needed to add `vh100` as the value of the `height`declaration in the `body` selector to achieve element centering on the page. _(Thanks to Google Gemini SRE AI tool window/field)

Code of the respective selector:
```css
main {
  display: inherit;
  flex-flow: column;
  padding: 0.8rem 1rem 0.5rem;
  background-color: var(--color-main-background);
  gap: 0.5rem;
}
```
I also understood that it was not necessary to turn all elements into Flexbox containers via their respective CSS declarations as I did initially.

### Continued development

I will revisit the CSS and Flexbox lessons from [The Odin Project](https://www.theodinproject.com/paths/foundations/courses/foundations#css-foundations) and think thoroughly first when using it again in similar projects.

## Author

- Website (GH Pages) - [Gabe's QR Code Component](https://github.com/Gabe013/qr-code-component/deployments/github-pages)