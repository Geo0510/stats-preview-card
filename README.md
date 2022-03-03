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

![](./images/Screenshot-desktop-Frontend-Mentor-Stats-preview-card%20component.png)
![](./images/Screenshot-mobile-Frontend-Mentor-Stats-preview-card%20component.png)

### Links

- Live Site URL: [https://geo0510.github.io/stats-preview-card/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

This challenge was espacially a very difficult for me, I'm not even sure if did it correctly but I did my best. Flexbox is amazing but if you combined it with responsive layouts it can be really trickly so i'll working more on that.

```html
<div class="container_information">
  <div>
    <h2 class="information_title lower">10k+</h2>
    <span class="information_text">companies</span>
  </div>
  <div>
    <h2 class="information_title">314</h2>
    <span class="information_text">templates</span>
  </div>
  <div>
    <h2 class="information_title">12m+</h2>
    <span class="information_text">queries</span>
  </div>
</div>
```

```css
img {
  max-width: 100%;
}

.image,
.color_image,
.container_image {
  width: 50%;
  border-top-right-radius: 10px;
  border-bottom-right-radius: 10px;
}

.image,
.color_image {
  position: absolute;
  top: 0;
  right: 0;
  height: 100%;
}

.color_image {
  background-color: hsl(277, 65%, 59%);
  opacity: 0.5;
}
```

### Continued development

Mobile-first workflow will be my first because this challenge I did desktop firts and it was great but I'm interested into try mobile-first

## Author

- Frontend Mentor - [@Geo0510](https://www.frontendmentor.io/profile/Geo0510)
