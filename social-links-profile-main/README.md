# Frontend Mentor - Social Links Profile Solution

This is a solution to the [Social Links Profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

---

## Table of contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)

---

## Overview

### The Challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page.

---

### Screenshot

Here are screenshots of the solution for both desktop (1440px) and mobile (375px):

![1440px Desktop View](https://github.com/elvisEspinozaN/front-mentor-challenges/blob/main/social-links-profile-main/assets/images/1440-desktop.png?raw=true "Desktop View at 1440px")  
_Desktop view at 1440px screen width._

![375px Mobile View](https://github.com/elvisEspinozaN/front-mentor-challenges/blob/main/social-links-profile-main/assets/images/375-mobile.png?raw=true "Mobile View at 375px")  
_Mobile view at 375px screen width._

---

### Links

- [Live Site](https://elvisespinozan.github.io/front-mentor-challenges/social-links-profile-main/)

---

## My Process

### Built With

This project was built using:

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

---

### What I Learned

This project helped me refine my CSS skills, especially when styling the navigation (`nav`) element. I learned how to effectively use `flexbox` to stack and align elements and how to style hover and focus states for better user interaction.

Here's an example of the `social-links` navigation styling:

```css
.social-links {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  flex-direction: column;
  gap: 0.75rem;
}

.social-link {
  display: block;
  text-decoration: none;
  color: var(--color-white);
  font-weight: 400;
  padding: 0.75rem 2rem;
  background-color: var(--grey-700);
  border-radius: 8px;
  transition: background-color 0.3s, color 0.3s;
}

.social-link:hover {
  background-color: var(--color-green);
  color: var(--grey-900);
  cursor: pointer;
}
```

### Continued development

I aim to continue improving my CSS skills by focusing on creating responsive, accessible designs. This project emphasized the importance of hover and focus states, which I plan to refine further in future work. Additionally, I want to explore advanced CSS techniques, like animations and transitions, to enhance interactivity.

### Useful resources

some resources are traditional css documentation

- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - A comprehensive resource for understanding CSS properties and best practices.
- [Frontend Mentor Documentation](https://www.frontendmentor.io/resources) - This helped me grasp the structure of the challenge and improve my workflow.
- [CSS Tricks](https://css-tricks.com/) - A great website with tips and tricks for writing better CSS.

## Author

- **GitHub** - [elvisEspinozaN](https://github.com/elvisEspinozaN)
