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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](solution/desktop.png)


### Links

- Solution URL: [https://github.com/SpiritedSea091/frontend-project-1/](https://github.com/SpiritedSea091/frontend-project-1/)
- Live Site URL: [https://spiritedsea091.github.io/frontend-project-1/](https://spiritedsea091.github.io/frontend-project-1/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Bootstrap

### What I learned

Getting child elements to fit within the parent using overflow CSS property.

```css
.card-element{
  overflow: hidden;
}
```

Defining bootstrap grid elements to be displayed in a different order depending on whether it is viewed on a mobile or desktop screen.

``` html
<div class="col-md-6 order-md-2 image-col">
<div class="col-md-6 order-md-1 text-column">
```

Using blend modes for images to use the color of the the background in the image. Also ensuring the image is displayed properly on different screens with object-fit CSS property.

```css
img{
  mix-blend-mode: multiply;
  object-fit: cover;
}
```

### Continued development

Understanding of elements with default height and width of auto like divs can be improved.


### Useful resources

- [Reordering Bootstrap Grid Elements](https://getbootstrap.com/docs/5.0/layout/columns/#reordering) - This helped me get the grid ordered with the image on top in mobile.
- [CSS Blend Mode](https://www.w3schools.com/cssref/pr_mix-blend-mode.asp) - All the different modes available. If you are not a designer, you can try the different modes to get the effect you want.


## Author

- Twitter - [@spiritedsea091](https://twitter.com/spiritedsea091)


## Acknowledgments

I want to thank Angela Yu of London App Brewery for recommending Frontend Mentor.
