# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Have to be careful when using vh heights in responsive design because elements may start to stretch in weird ways. Setting min-heights helped but I wonder if there is a more elegant way than to keep creating @media queries with different heights. 

I like flexbox a lot and am glad I found a use case for the order property for the image, as I hadn't had a chance to use this yet.

### Continued development

I don't like the way I wrote the purple overlay as an empty div over the image, but I couldn't think of another way to alter its colour. The overlay caused me some grief when I started to reduce screen size as it started to become longer than the image itself. Hence the afore-mentioned height adjustments in the media queries. I'd like to find a better way to create this in the future. 

## Author

- Website - [Daniela Parra](https://github.com/parradaniela)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
