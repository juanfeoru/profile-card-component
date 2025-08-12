# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

- Build the profile card to match the provided design.
- Make sure the layout adapts to different screen sizes (mobile-first approach).
- Use background SVGs with a color base to match the original style.

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [Add your solution URL here](https://www.frontendmentor.io/solutions/responsive-profile-card-component-using-html-and-css-it3DT9XwVq)
- Live Site URL: [Add your live site URL here](https://juanfeoru.github.io/profile-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Multiple background images in CSS
- BEM (Block Element Modifier) naming convention

### What I learned

This project helped me practice working with **multiple background images in CSS** combined with a background color, as well as using **relative units (`vw`, `vh`)** for responsive positioning.  
I also improved my understanding of **BEM naming** to keep the code organized.

```css
body {
  background-color: hsl(185, 75%, 39%);
  background-image: url("bg-pattern-top.svg"), url("bg-pattern-bottom.svg");
  background-position: left -15vw top -15vh, right -15vw bottom -15vh;
  background-repeat: no-repeat, no-repeat;
  background-size: 40vw, 40vw;
}
```

### Continued development

In the future, I want to:

- Improve handling of SVG backgrounds on very small screens.
- Explore using CSS Grid for the stats section instead of Flexbox.
- Experiment with CSS animations to make the card more interactive.

## Author

- Frontend Mentor - @juanfeoru
- GitHub - @juanfeoru

## Acknowledgments

Thanks to the Frontend Mentor community for feedback and inspiration from other solutions to this challenge.
