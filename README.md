# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)


## Overview

### Screenshot
![](./assets/images/22.png)


### Links
- Solution URL: (https://github.com/jacey10/fm-product-preview-card-challenge)
- Live Site URL: (https://jacey10.github.io/fm-product-preview-card-challenge/)

## My process

### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox Layout
- CSS GRID Layout
- Mobile-first workflow
- Principles of Web Accessibility


### What I learned

- I recently learned CSS Grid and how it is used for two dimensional layouts and decided to apply it to the desktop view for this particular project. It was so simple to implement.
- The design appeared to be very simple and I was excited to dive into building it. Even though I implemented, mobile first principles, the product card on mobile screens didn't look good at all. So, I focused on the desktop. Everything looked good on the desktop but when I reduced screen sizes (larger screens), I noticed that the image and texts where shrinking and they weren't filling up their parent element (the Grid container), because it was also shrinking. After looking at two solutions from other members, I realise it was a problem of "width" and "height". So, I gave the Grid container a width and height (for both mobile and desktop), using the CLAMP FUNCTION.
- I struggled with changing the images from mobile to desktop, but then I found a way around it by using display of "block" to reveal one and "none" to hide the other. For the moblile image, I gave it a height, to reduce overflow and size appropriately too.

### Continued development
- I would continue to explore how to create layouts that are responsive across many screens and devices.
- I would practice more with CSS Grids

## Author
- Website - [James Chima](https://jacey.hashnode.dev/)
- Frontend Mentor - [@jacey10](https://www.frontendmentor.io/profile/jacey10)
- Twitter - [@jacey_opara](https://x.com/jacey_opara)
