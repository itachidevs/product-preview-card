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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot
![Frontend Mentor _ Product preview card component - Google Chrome 14-03-2024 21_24_56](https://github.com/babybhavani/product-preview-card/assets/152834101/e3b9e5f6-f125-4a1e-b4c5-ff26df17c5be)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Resopnsive layputs
- Viewport widths and heights

### What I learned

- Arranging and setting the font-size of the text for different widths
- View Port width and height
- Creating Responsive Layout
- Mobile view ports
- Changing the responsive layout at different breakpoints

```html
<section class="container">
    <section class="card">
      <section class="top-section">
        <img src="images\image-product-mobile.jpg" class="top-section-img">
        <img src="images\image-product-desktop.jpg" class="top-section-img-desktop">
      </section>
      <section class="bottom-section">
        <h1 class="card-head-small">PERFUME</h1>
        <h1 class="card-head-big">Gabrielle Essence Eau De Parfum</h1>
      <p class="about"> A floral, solar and voluptuous interpretation composed by Olivier Polge, 
        Perfumer-Creator for the House of CHANEL.
      </p>
      <h1 class="card-price">$149.99</h1>
      <h1 class="card-price-striked">$169.99</h1>
      <button class="btn"><img src="images/icon-cart.svg" class="cart">Add to Cart </button>
      </section>
    </section>
  </section>
```
```css
@media screen and (min-width:48em){
   
   .card{
    display: flex;
   max-width: 1440px;
   }
   .bottom-section{
    padding:4em;
    width: 50%;
    height: 100%;
   }
   .top-section{
    width: 50%;
    height: 100%;
   }
   .btn{
    height: 5rem;
   }
   .cart{
    height: 1em;
    width: 1em;
   }
   .top-section-img-desktop{
    display: block;
    width: 100%;
    height: 100%;
   }
   .top-section-img{
    display: none;
   }
   .about{
    margin-top: 2em;
    font-size: 2em;
   }
   .card-head-big{
    margin-top: 1rem;
    font-size: 5em;
   }
   .card-head-small{
    margin-top: 1em;
    font-size: 2rem;
   }
   .card-price{
    margin-top: 2em;
   }
   .card-price-striked{
    margin-top: 2em;
   }
   .btn{
    margin-top: 2em;
   }

}

}
```
### Continued development

Iam moving forward this project adding some other design and animations using JavaScript.

## Author

- Frontend Mentor - [@babybhavani](https://www.frontendmentor.io/profile/babybhavani)


