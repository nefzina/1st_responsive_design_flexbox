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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![desktop design screenshot](./Screenshot%202022-12-07%20desktop%20design.png)
![mobile design screenshot](./Screenshot%202022-12-07%20mobile%20design.png)

### Links

- Solution URL: [https://github.com/nefzina/Frontend-Mentor-designs/blob/main/gabrielle_perfume.html] 
and [https://github.com/nefzina/Frontend-Mentor-designs/blob/main/style10.css]

## My process

### Built with
- Flexbox
- Media Queries
- pseudo-class
- combinators


### What I learned

While working through this project, i learned how to:
* add text with a line through
```css
#old-price {
    text-decoration: line-through;
}
```

* change the space between text lines and between letters
```css
.details h1 {
    line-height: 32px;
}
#title {
    letter-spacing: 5px;
}
```

* obtain the references of font families from fonts google and add their links
```html
<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,700&family=Montserrat:wght@500;700&display=swap" rel="stylesheet">
```

* use <picture>, <source> and <img> tags for responsive design
```html
<picture>
  <source srcset="starters_&_sketches/product-preview-card-component-main/images/image-product-mobile.jpg" media="(max-width: 375px)">
  <source srcset="starters_&_sketches/product-preview-card-component-main/images/image-product-desktop.jpg">
  <img src="starters_&_sketches/product-preview-card-component-main/images/image-product-desktop.jpg" alt="perfume-photo">
</picture>
```

* eliminate white spaces so an image can occupy all the space 
```css
picture>img {
    display: block;
}
```

* responsive height by using vh (viewport height) as a unit
```css
.container-2 {
    height: 100vh;
}
```

* add shadow to a box or an image
```css
.container-2 {
        box-shadow: 0 4px 20px 5px hsla(0, 0%, 0%, 0.1);
}
```

* add a favicon
```html
<link rel="icon" type="image/png" href="/starters_&_sketches/product-preview-card-component-main/images/favicon-32x32.png">
```

### Continued development

I'm still in the beginning of my learning journey so i still have a lot to learn in html and css and i need to start learning javascript.


### Useful resources

- [w3schools website](https://www.w3schools.com/) - complete courses to learn the basics.
- [stackoverflow](https://www.stackoverflow.com) - a well known platform used to share coding related questions and answers.

## Author
- Frontend Mentor - [@nefzina](https://www.frontendmentor.io/profile/nefzina)
