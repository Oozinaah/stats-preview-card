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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Screenshot for desktop experience.](screenshots/Screenshot_desktop.png)

![Screenshot for mobile experience.](screenshots/Screenshot_mobile.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned to work with CSS flex property, @media properties and color overlay for images.

Code snippet for overlay for images:


``html
    <div class="image">
      <img src="images/image-header-mobile.jpg" alt="Women, computer, laughing">
    </div>
``
```css
/*Change color on the image, position:relative; and ::after*/
.image {
    flex: 50%;
    position: relative;
}

.image::after {
    position: absolute;
    content: "";
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: 0;
    background-color: rgba(140, 4, 224, 0.5);
    border-radius: 0px 10px 10px 0px;
}
```

### Continued development

I will continue to make Frontends challenges to improve my skills in HTML, CSS and JavaScript.

### Useful resources

- [W3 shools](https://www.w3schools.com/css/css3_images.asp) - This helped me for overlay for images.

## Author

- Frontend Mentor - [@Oozinaah](https://www.frontendmentor.io/profile/Oozinaah)
