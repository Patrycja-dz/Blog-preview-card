# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- See hover and focus states for all interactive elements on the page

### Screenshot

![Blog preview card screenshot](./screenshot.gif)

### Links

- Solution URL: [Add solution URL here](https://github.com/Patrycja-dz/Blog-preview-card)
- Live Site URL: [Add live site URL here](https://patrycja-dz.github.io/Blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Through this project, I enhanced my understanding of HTML and CSS. One of the key things I focused on in this project was creating smooth and engaging animations. I am particularly proud of the liquid animation effect combined with a smoother box shadow transition on the card component. This adds a dynamic feel to the card, enhancing the user experience. Below are some examples of code that I am proud of:

```css
main {
  max-width: 384px;
  height: 528px;
  background-color: var(--neutral-white);
  padding: 24px;
  border: 1px solid var(--neutral-black);
  border-radius: 20px;
  box-shadow: 8px 8px 0 0 var(--neutral-black);
  margin: 0 24px;
  transition: box-shadow 0.3s ease-in-out, transform 0.3s ease-in-out;
}

@keyframes liquid {
  0%,
  100% {
    transform: scale(1);
    filter: blur(0);
  }
  50% {
    transform: scale(1.05);
    filter: blur(4px);
  }
}

main:hover {
  box-shadow: 16px 16px 0 0 var(--neutral-black);
  transform: translateY(-5px);
  transition: box-shadow 0.5s ease-out, transform 0.5s ease-out;
  animation: liquid 2s infinite;
}
```

### Continued development

In future projects, I aim to focus more on:

- Enhancing responsive design techniques
- Implementing advanced CSS animations
- Improving accessibility features

### Useful resources

- [CSS-Tricks](https://css-tricks.com) - A great resource for various CSS techniques and tips.
- [MDN Web Docs](https://developer.mozilla.org) - Comprehensive documentation on web technologies including HTML and CSS.

## Author

- Frontend Mentor - [@Patrycja-dz](https://www.frontendmentor.io/profile/Patrycja-dz)

## Acknowledgments

Special thanks to the Frontend Mentor community for providing valuable feedback and support throughout this challenge.
