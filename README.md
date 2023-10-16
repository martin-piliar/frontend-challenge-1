# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Tips & Tricks](#tips--tricks)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshots

#### Template
![](./design/desktop-preview.jpg)

#### My solution
![](./design/screenshot.png)
![](./screenshot.jpg)
### Links
- Solution URL: [Github](https://github.com/martin-piliar/frontend-challenge-1)
- Live Site URL: [Website](https://martin-piliar-frontend-challenge-1.netlify.app/)

## My process

### Tips & Tricks

Many people in the community had problems with properly nesting the corners and their radius. A good design rule is to calculate the inner corner radius by taking the outer radius and subtract the padding between the two elements. 

So, for example, in this project, the card corner radius is `1.25rem`, the padding on the content is `0.75rem` = `0.5rem` inner corner radius. 

This is how you can calculate it in CSS:
```css
border-radius: calc(var(--card-border-radius) - var(--size-xs));
```
- `--card-border-radius` is defined in the `:root` element
- `--size-xs` is defined in the `:root` element of the `sizes.css` file

### Useful resources

- [Box Shadows](https://box-shadow.dev/) - A quick way to generate fancy-looking box shadows.

## Author

- Website - [Martin Piliar](https://www.piliar.me/)
- Frontend Mentor - [@martin-piliar](https://www.frontendmentor.io/profile/martin-piliar)
- LinkedIn - [@martin-piliar](https://www.linkedin.com/in/martin-piliar/)
- Twitter - [@MartinPiliar](https://twitter.com/MartinPiliar)
