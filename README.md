# Frontend Mentor - Product Preview Card Component solution

This is a solution to the [Product Preview Card Component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/screenshot.png)

### Links

- [Solution URL](https://github.com/Kking927/product-preview-card-component)
- [Live Site URL](https://kking927.github.io/product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- The `<picture>` element for responsive art direction

### What I learned

**Responsive Image Handling:** One of the key takeaways from this project was using the `<picture>` tag. Instead of using CSS background images or hiding elements with display: none, the `<picture>` element allowed me to serve the mobile or desktop image based on the user's screen size more efficiently.
```
<picture>
  <source media="(min-width: 600px)" srcset="images/image-product-desktop.jpg">
  <img src="images/image-product-mobile.jpg" alt="Gabrielle Essence Eau De Parfum">
</picture>
```
  
### Continued development

* **Advanced Micro-interactions:** I want to learn the best practices for using animations effectively. I’m interested in finding the right balance between making a site feel more interactive and intuitive, while ensuring the effects are smooth, purposeful, and improve the overall user experience.

* **SVG Optimization:** I want to get better at styling and animating SVGs (like the cart icon) directly within HTML or CSS to reduce HTTP requests and allow for greater design control.

## Author

- Frontend Mentor - [@Kking927](https://www.frontendmentor.io/profile/Kking927)
