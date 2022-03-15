# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

1. This is huddle page frontendmentor challange solution by [Thisislearner](https://github.com/thisislearner/huddle-landing-page-with-single-introductory-section-master).
2. this solution include some animation, some psuedo elements and some animation.
3. Some changes are made to the stock background images provided by frontendmentor.

### Screenshot

![my solution screenshot](./figma_designs/png/screen_1400_normal.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/thisislearner/huddle-landing-page-with-single-introductory-section-master)
- Live Site URL: [Add live site URL here](https://thisislearner.github.io/huddle-landing-page-with-single-introductory-section-master/)
- figma look on hover: [Figma hover png](./figma_designs/png/huddle_design_with_hover_effect.png)
- figma design png normal : [figma normal](./figma_designs/png/screen_1400_normal.png)
- figma design normal svg: [figma svg normal](./figma_designs/svg/screen_1400_normal.svg)
- figma svg design with active buttons [figma svg](/figma_designs/svg/huddle_design_with_hover_effect.svg)

## My process

1. designed it on figma as per my laptop screen.
2. took measurements from figma created html.
3. added css.
4. added animation.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- I leart basic animation.

```css
@keyframes headingTxtAnimation {
  0% {
    transform: translateX(-8rem);
    opacity: 0;
  }
  50% {
    transform: translateX(-4rem);
    opacity: 0.5;
  }
  100% {
    transform: translateX(0);
    opacity: 1;
  }
}
```

- how to used pseudo elements.

```css
.register::after {
  content: "";
  display: inline-block;
  background-color: #fff;
  width: 100%;
  height: 100%;
  position: absolute;
  border-radius: 5rem;
  outline: none;
  top: 0;
  left: 0;
  z-index: -5;
  transition: all 200ms linear;
}

.register:hover::after {
  transform: scale(1.6);
  opacity: 0;
}
```

## continued-development

I will added responsiveness in this page.

## Author

- Frontend Mentor - [@Thisislearner](https://www.frontendmentor.io/profile/Thisislearner)
- Twitter - [@abhi92039385](https://twitter.com/abhi92039385)
