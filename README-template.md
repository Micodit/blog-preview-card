# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
- [The challenge](#the-challenge)
- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

This simple blog preview card is built using HTML and CSS. It has hover effects and it is also responsive to all screen sizes.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS clamp function
- Flexbox

### What I learned

I learned that I could use CSS clamp function to create responsive design (on text font size) without the need of @media querry, which helps simplify my code.

````.card__title {
  font-size: clamp(2.2rem, 4vw, 2.4rem);
  line-height: 1.1;
  font-weight: 800;
  }

I also learned how to style a specific child when we hover its parent

```.card:hover .card__title a {
  color: var(--color-yellow);
  transition: all 0.8s;
}

### Continued development

I want to improve my coding speed

I want to focus more on the accessibility

### Useful resources

- [Stack overflow](https://stackoverflow.com/questions/7217244/style-child-element-when-hover-on-parent) - This helped me for styling child in hover parent element.
- [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/clamp) - This tells me how to use clamp()

## Author

- Frontend Mentor - [Micodit](https://www.frontendmentor.io/profile/Micodit)


## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**

question:

- when i set border-radius to card\_\_img-box the rounded corner in each side is not equal (bottom lef and bottome right smaller than top left and top right). Should I wrap the img in a div at all?
- box-shadow on .card

````

```

```
