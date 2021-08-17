# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

Desktop View:

![](./screenshot-desktop.jpg)

Mobile View:

![](./screenshot-mob.jpg)


### Links

- Solution URL: [Click Here for Solution](https://github.com/MaqsudMallick/responsive-design-css-grid-project)
- Live Site URL: [Click here to go to site](https://maqsudmallick.github.io/responsive-design-css-grid-project/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

- how to use ordering of grid elements

```html
  <div class="col-lg-5 text order-last order-sm-last order-md-last order-lg-first">
```

- how to edit bootstrap default dimensions for containers

```css
@media (min-width: 992px) {
  .container-lg, .container-md, .container-sm, .container {
    max-width: 878px;
  }
}
@media (min-width: 576px)
{
  .container-sm .container{
    max-width: 520px;
  }
}
```

- how to perform responsive web design
```css
@media screen and (max-width: 600px){...}
@media screen and (min-width: 602px){...}
```

## Author

- Frontend Mentor - [@MaqsudMallick](https://www.frontendmentor.io/profile/MaqsudMallick)
