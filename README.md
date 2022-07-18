# Frontend Mentor - Product preview card component solution

![3° F.E.P. Banner - ](https://user-images.githubusercontent.com/105513033/179428495-83824bcf-9cb7-43fa-92c6-0680837331be.png)

<span>
  <img src="https://img.shields.io/badge/STATUS-FINISHED-success" alt="Status: Finished">
  <img src="https://img.shields.io/badge/RELEASE_DATA-JULY%202022-informational" alt="Release Data: July 2022">
  <img src="https://img.shields.io/badge/LICENCE-MIT-important" alt="Licence: MIT">
</span>

&nbsp;

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). 

Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

&nbsp;

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

&nbsp;

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

&nbsp;

### Screenshot

#### 🖥️ Desktop
![3° F E P  - Desktop Screenshot](https://user-images.githubusercontent.com/105513033/179430712-1974ddc2-3a73-4e91-8841-bdeabc2911d6.png)

#### 📱 Mobile
![3° F E P  - Mobile Screenshot](https://user-images.githubusercontent.com/105513033/179428302-8c286665-ecc4-40a5-b8e6-451be70bc330.png)

&nbsp;

### Links

- Solution URL: [Solution in Github](https://github.com/EliveltonSilvaCordeiro/3-FEP-X-1st-Frontend-Mentor/)
- Live Site URL: [Live site by Vercel](https://preview-card-topaz.vercel.app/)

&nbsp;

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow

&nbsp;

### What I learned

The **media** rule can be used to create a responsive website, this helped me to change the product's desktop and mobile images depending on the user's device.

```css
/*Desktop*/
@media screen and (max-width: 1445px) and (min-width: 651px) {
   background-image: url(../images/image-product-desktop.jpg);
}

/*Mobile*/
@media screen and (max-width: 650px) {
    background-image: url(../images/image-product-mobile.jpg);
}
```
&nbsp;

### Continued development

My plans are to focus in improving my knowledge about the display and position properties.

&nbsp;

### Useful resources

- [Learn CSS FLEXBOX in 20 Minutes](https://youtu.be/qqDH0T6K5gY) - This helped me for understanding the flex propriets being direct to the point.

&nbsp;

## Author

- Github - [EliveltonSilvaCoredeiro](https://github.com/EliveltonSilvaCordeiro/)
- Frontend Mentor - [@EliveltonSilvaCordeiro](https://www.frontendmentor.io/profile/EliveltonSilvaCordeiro)
