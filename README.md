# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![](./bento-desktop.png)
![](./bento-mobile.png)


### Links

- Solution URL: [https://github.com/2emeagauche/frontend-mentor-bento-grid/tree/main](https://github.com/2emeagauche/frontend-mentor-bento-grid/tree/main)
- Live Site URL: [https://2emeagauche.github.io/frontend-mentor-bento-grid/](https://2emeagauche.github.io/frontend-mentor-bento-grid/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

How to use grid-template-areas

```css
  .bento {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: 324px 60px 156px 246px;
    gap: 1.8rem;
    grid-template-areas:
      "card7 card1 card1 card4"
      "card7 card2 card3 card4"
      "card8 card2 card3 card4"
      "card8 card6 card5 card5";
  }
```

### Useful resources

Kevin Powell Youtube channel on CSS: [https://www.youtube.com/@KevinPowell](https://www.youtube.com/@KevinPowell)
Especially about grid area: [https://youtu.be/duH4DLq5yoo?si=dYv7EvOWB0_Mhdx8](https://youtu.be/duH4DLq5yoo?si=dYv7EvOWB0_Mhdx8)

## Author

- Frontend Mentor - [@2emeagauche](https://www.frontendmentor.io/profile/2emeagauche)
