# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](design/mobile-design.jpg)
![](design/active-states.jpg)
![](design/desktop-preview.jpg)

### Links

- Solution URL: [Click Here](https://github.com/Muhammad-RK-Isa/product-preview-card-component)
- Live Site URL: [Click Here](https://muhammad-rk-isa.github.io/product-preview-card-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### Here is what I learned and some new methods that I implemented in this project.

```html
<s>$169.99</s>
```
```css
.visually-hidden:not(:focus):not(:active){
    clip: rect(0 0 0 0);
    clip-path: inset(50%);
    /* overflow: hidden; */
    position: absolute;
    white-space: nowrap;
    width: 1px;
    overflow: hidden;
}
```

### Continued development

I want to focus on the back-end technologies right now. Besides, I'm doing some front-end projects to keep in touch with new things and making it easier to master front-end development.

## Author
- Frontend Mentor - [@Muhammad-RK-Isa](https://www.frontendmentor.io/profile/Muhammad-RK-Isa)

