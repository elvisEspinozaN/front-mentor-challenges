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

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Mobile screenshot](https://github.com/elvisEspinozaN/front-mentor-challenges/blob/main/blog-preview-card-main/assets/images/mobile.png?raw=true)
![Desktop screenshot](https://github.com/elvisEspinozaN/front-mentor-challenges/blob/main/blog-preview-card-main/assets/images/desktop.png?raw=true)
![Hover effect screenshot](https://github.com/elvisEspinozaN/front-mentor-challenges/blob/main/blog-preview-card-main/assets/images/hover.png?raw=true)

### Links

- [Live site URL](https://elvisespinozan.github.io/front-mentor-challenges/blog-preview-card-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

While building this project, I focused on improving my workflow. I learned:

- How to prioritize a mobile-first design approach, starting with base styles and progressively enhancing them for larger screens.
- The importance of setting a CSS base structure before diving into specific styles, ensuring better scalability.
- A better understanding of how to use `max-width` and `object-fit` to ensure elements like images and cards are responsive.

Here’s an example of a media query I implemented for the desktop breakpoint:

```css
.container {
  width: 90%;
  max-width: 375px;
}

@media (min-width: 1440px) {
  .container {
    width: 375px;
    margin: 0 auto;
  }
}
```

### Continued development

I want to continue improving my CSS skills, particularly with responsive design and creating layouts that look consistent across all screen sizes.

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/) - Always a reliable reference for CSS and HTML features.
- [CSS Tricks](https://css-tricks.com/) - Helpful for understanding layout techniques and responsive design patterns.

## Author

As I am organizing all of my Frontend Mentor projects into a single repository folder, I have not uploaded individual repositories for this project. However, if you’d like to see my other work:

[Github Repository | My Projects](https://github.com/elvisEspinozaN)
