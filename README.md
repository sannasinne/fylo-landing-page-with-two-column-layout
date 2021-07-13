# Frontend Mentor - Fylo landing page with two column layout solution

This is a solution to the [Fylo landing page with two column layout challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-landing-page-with-two-column-layout-5ca5ef041e82137ec91a50f5). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution URL: [https://github.com/sannasinne/fylo-landing-page-with-two-column-layout](https://github.com/sannasinne/fylo-landing-page-with-two-column-layout)
- Live Site URL: [https://sannasinne.github.io/fylo-landing-page-with-two-column-layout/](https://sannasinne.github.io/fylo-landing-page-with-two-column-layout/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

During this project I learned to use Flexbox in two column setup. I learned to make a circle to social icons by adding class "circle" to a in html.

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
<ul class="social-icons">
  <li> <a class="circle" href="#"> <i class="fab fa-facebook"></i> </a> </li>
  <li> <a class="circle" href="#"> <i class="fab fa-instagram"></i> </a> </li>
  <li> <a class="circle" href="#"> <i class="fab fa-twitter"></i> </a> </li>
</ul>
```
```css
footer .circle {
  border: 1px solid white;
  border-radius: 50%;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 30px;
  height: 30px;
  margin-left: 10px;
}
```

### Continued development

In next projects I want to use more Grid as I'm getting now very comfortable with Flexbox.

## Author

- Frontend Mentor - [@sannasinne](https://www.frontendmentor.io/profile/sannasinne)