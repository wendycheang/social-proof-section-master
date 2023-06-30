# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![Desktop](./images/desktop.png)

![Mobile](./images/mobile.png)


**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- CSS variables
- CSS functions like clamp

### What I learned

I learned more advanced Flexbox and Grid concepts.

I learned how to shrink and size divs in Grids and Flexboxes

I more about CSS selectors and selectors like :nth-child,

I learned how to set background images as well. 

To see how you can add code snippets, see below:

```css
    .stars {
        display: grid;
        grid-template: repeat(3, 1fr) / .5fr .5fr 10fr .5fr .5fr;
        justify-content: center;
        height: fit-content;
    }

    .rating:nth-child(1)  {
        grid-column: 1 / 4;
        grid-row: 1 ;
    }

    .rating:nth-child(2)   {
        grid-column: 2 / 5;
        grid-row: 2 ;
    }

    .rating:nth-child(3)   {
        grid-column: 3 / 6;
        grid-row: 3 ;
    }

    .rating {
        display: flex;
        align-items: center;
        gap: .5em;
        padding: .5em 2em;
    }
```
### Continued development

I would like to move on to more complicated projects with Javascript next. 

### Useful resources

- [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/) - This is a pretty complete and well organized guide to CSS grids which I found helpful
- [A Very In Depth CSS Grid Guide](https://coderpad.io/blog/development/a-very-very-in-depth-guide-on-css-grid/#expand-grid-items) - An even more in-depth CSS grid guide
- [ACSS Child Selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/:nth-child) - Mozilla Docs are very helpful

## Author

- Frontend Mentor - [@wendycheang](https://www.frontendmentor.io/profile/wendycheang)
