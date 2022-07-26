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
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](images/web%20version.jpeg)
![](images/mobile%20version.jpeg)

### Links

- Live Site URL: [https://pandamajor.github.io/product-preview-card-component-main/](https://pandamajor.github.io/product-preview-card-component-main/)

## My process

### Built with

- HTML5
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

How to manipulate the content displayed based on the viewport size. Below is the code used for smaller (mobile) displays.
```css
@media only screen and (min-width:650px) and (max-width:750px){
    .card {
        max-width: 650px;
    }
}

@media only screen and (max-width:650px){
    .card {
        min-width: auto;
        width: 90%;
        display: flex;
        flex-direction: column;
        border-radius: 10px;
    }
    .left {
        width: 100%;
        height: 350px;
        background-image: url(../images/image-product-mobile.jpg);
        border-radius: 10px 10px 0 0;
    }
    .right {
        width: 100%;
        row-gap: 12px;
        padding: 25px;
        border-radius: 0 0 10px 10px;
    }
}
```

### Useful resources

- [w3schools - flexbox](https://www.w3schools.com/css/css3_flexbox.asp) - This helped me understand how to use flexbox in my design to position the card without absolute positioning.
- [w3schools - RWD Media Queries](https://www.w3schools.com/css/css_rwd_mediaqueries.asp) - This resource was useful in determining how to resize the content based on the viewport size.

## Author

- Twitter - [@major_liu](https://www.twitter.com/major_liu)
