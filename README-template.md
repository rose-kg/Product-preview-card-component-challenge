# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Product preview card component solution](#frontend-mentor---product-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
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
  
## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: [My solution URL](https://github.com/rose-kg/Product-preview-card-component-challenge.git)
- Live Site URL: [Add live site URL here](http://127.0.0.1:3000/index.html)

## My process

### Built with

-HTML
-CSS

### What I learned

1. Responsive Design
Learned how to create a responsive layout using CSS media queries to adjust the design for different screen sizes.
<!-- code snippet -->
@media (max-width: 768px) {
    /* CSS rules for mobile devices */
}

2. Typography Styling
Explored techniques for styling typography, including font families, font sizes, font weights, and letter spacing.
<!-- code snippet -->
h1 {
    font-family: "Fraunces", serif;
    font-size: 32px;
    font-weight: 700;
    letter-spacing: 0.05em;
}

3. Box Model and Layout
Implemented the box model concept to control the layout of elements, including margins, padding, and borders.
<!-- code snipet -->
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 120px;
}


```html
<h1>Some HTML code I'm proud of</h1>

```

   <div class="price">
      $149.99<span class="original-price">$169.99</span> 
    </div>

        <p>A floral, solar and voluptuous
<br>interpretation composed by <br> Olivier
Polge, Perfumer-Creator <br> for the House of
CHANEL.</p>

```css
.proud-of-this-css {
  color: papayawhip;
}

@media (max-width: 768px) {
  .container{
    flex-direction: column; 
  }

```

### Continued development
Moving forward, I aim to enhance my proficiency in HTML and CSS, prioritizing mastery of the core concepts before exploring advanced frameworks like Bootstrap or Tailwind. Throughout the development of this project, I faced challenges, notably in replicating the precise appearance of the shopping basket as depicted in the design. While I came close to the desired outcome, I recognize the potential efficiency gains that could be achieved through the use of a CSS framework. Additionally, ensuring consistency in fonts and content presentation presented another engaging challenge, one that I thoroughly enjoyed tackling.
 
### Useful resources

- [Example resource 1](https://fontawesome.com/v4/icon/shopping-cart) - This helped me get a close replica of the shopping cart and will use it going forward.


## Author

- Frontend Mentor - [@rose-kg](https://www.frontendmentor.io/profile/rose-kg)
- TikTok - [@rose in tech](https://www.tiktok.com/@just_rose01?_t=8kdwxZkkTqg&_r=1)


