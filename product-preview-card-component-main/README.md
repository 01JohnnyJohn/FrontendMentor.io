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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![images\Screenshot_desktop.png] - desktop
![images\Screenshot_mobile_1.png] - mobile
![images\Screenshot_mobile_2.png] - mobile

### Links

- Solution URL: (https://github.com/01JohnnyJohn/FrontendMentor.io/tree/main) - GitHub repository
- Live Site URL: (https://nimble-choux-f4a444.netlify.app) - Netlify hosting

## My process

The process was quiet linear.
I've, first, set HTML structure. Then I've added all the basic CSS like variables for fonts, colors, background-colors, font-families etc, then matched CSS selectors with all the classes I've given while writing HTML

I've been stuck for a while when trying to make the right side of the product card be spread (in height) within its container. I've also been stuck when trying to make both sides take 50% of the main container when screen width is more than 600px. The problem was that I've set max-width: 100% for image to fill its container, that's why it wouldn't scale when setting main container as a flex container. So, I had to overwrite it in media-query.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

- I've been stuck for a while when trying to make the right side of the product card be spread (in height) within its container - <i>justify-content: space-evenly fixed it. However, it doesn't quite match the original design.</i>
- I've also been stuck when trying to make both sides take 50% of the main container when screen width is more than 600px. The problem was that I've set max-width: 100% for image to fill its container, that's why it wouldn't scale when setting main container as a flex container - <i>I had to overwrite it in media-query by setting max-width for both left and right sides to be 50%</i>

### Continued development

- need more practice with items inside flex container

### Useful resources

- stackoverlow.com

## Author

- Frontend Mentor - [@01JohnnyJohn](https://www.frontendmentor.io/profile/yourusername)

## Acknowledgments
