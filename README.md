# Frontend Mentor - QR code component solution

This is a solution to the
[QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).
Frontend Mentor challenges help you improve your coding skills by building
realistic projects.

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Links

- Solution URL: https://github.com/Alexisliao10/QR-code-P
- Live Site URL: https://visionary-froyo-d315d0.netlify.app/

## My process

- Indentified the html structure
- Build common styles in CSS using Sass
- Add git to my proyect
- Style the proyect according to the design

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Sass

### What I learned

I learned to create the HTML struture first then follow a design guide and
finishing with custom styles.

```html
<div class="card">
  <div class="qrcode">
    <div class="qrcode__image">
      <img src="./images/image-qr-code.png" alt="A QR-code" />
    </div>
    <div class="qrcode__legend">
      <h1>Improve your front-end skills by building projects</h1>
      <p>
        Scan the QR code to visit Frontend Mentor and take your coding skills to
        the next level
      </p>
    </div>
  </div>
</div>
```

```css
.proud-of-this-css {
 .card {
  display: flex;
  justify-content: center;
  width: 100vw;
  height: 100vh;
  background-color: hsl(212deg, 45%, 89%);
}
.card .qrcode {
  display: flex;
  flex-direction: column;
  width: 280px;
  height: -webkit-fit-content;
  height: -moz-fit-content;
  height: fit-content;
  margin-top: 100px;
  padding: 16px;
  background-color: hsl(0deg, 0%, 100%);
  border-radius: 20px;
  box-shadow: 0px 10px 45px 12px rgba(0, 0, 0, 0.1);
}
.card .qrcode__image img {
  width: 100%;
  height: auto;
  border-radius: 10px;
}
.card .qrcode__legend {
  margin: 17px 0;
  text-align: center;
  font-family: "Outfit", sans-serif;
}
.card .qrcode__legend h1 {
  color: hsl(218deg, 44%, 22%);
  font-weight: 700;
  line-height: 25px;
}
.card .qrcode__legend p {
  margin-top: 15px;
  font-weight: 400;
  line-height: 20px;
  color: hsl(220deg, 15%, 55%);
```

### Useful resources

Sass documentation - Mixin -
https://sass-lang.com/documentation/at-rules/mixin - This helped me to recap how
to properly assign mixin and call them in the stylesheet.

Shadow CSS generator - https://cssgenerator.org/box-shadow-css-generator.html -
Using a shadoow generator let me visualized the shadow of the card more easily
and helped a lot when try to match a shadow from the design card.

## Author

- Frontend Mentor -
  [@Alexisliao10](https://www.frontendmentor.io/profile/Alexisliao10)
