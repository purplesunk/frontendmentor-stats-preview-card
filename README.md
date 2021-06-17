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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![mobile-screenshot](./mobile-screenshot.jpg)
![desktop-screenshot](./desktop-screenshot.jpg)


### Links

- Solution URL: [Solution](https://github.com/purplesunk/stats-preview-card-component-main)
- Live Site URL: [Live Site](https://purplesunk.github.io/stats-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

How to make an image overlay

```css
.preview-card--img {
  background: linear-gradient(rgba(170, 92, 219, 0.4), rgba(170, 92, 219, 0.4)), url(../images/image-header-mobile.jpg);
  background-size: cover;
  filter: saturate(2) brightness(60%) contrast(110%);
}
```

