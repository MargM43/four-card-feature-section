# four-card-feature-section

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK).

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

This challenge asked students to 

- re-create a page layout of a heading with 4 cards
 - responsive to three different device types - desktop, laptop and phone
 - and legible at all screen sizes from 1400 px to 300px

### Screenshot

!(<Screenshot 2026-09-11 at 13-25-11 Frontend Mentor Four card feature section.png>)

### Links

-Solution URL: (https://github.com/MargM43/four-card-feature-section)
- live site URL: (supervisor.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

- The most important skill I learned here was how to use grid-areas.
- I was also happy with the fact that I knew how to search from help on MDN and W3Schools.
- My speed also improved -took about 3 hours including time to search for correct syntax.
- My use of clamp seems to be more effective
- I was happy with the way I used media queries to add responsiveness at difference screen widths:
```css
.card__5 {
    border-top: 10px solid var(--clr-Blue);
    margin-block-start: -6rem;
    grid-area: 5 / 9 / 5 / 13;
        @media (width <= 1000px) {
        margin-block-start: 1.5rem;
        grid-area: 5 / 7 / 5 / 12;
    }
    @media (width <= 600px) {
        grid-area: 6 / 2 / 6 / 12;
    }
}
```
### Continued development

- I want to learn much more about grid areas, especially how to set them up with area numbers rather than line numbers.
- I'll do further work on clamp and using Utopia to get an in-depth understanding of exactly how it works.
- I need more knowledge about how to improve accessability.
- Ways to reduce media queries is also something I need to work on. 


### Useful resources

- In this case, the best resource I found was Kevin Powell's video series, "The easiest way to get started with CSS Grid", in particular "Why CSS grid-area is the best property for laying out content".
- As usual, MDN and W3Schools.
- YouTube videos about Utopia:
 - "Utopia - an introduction", by Utopia. "Utopia Fluid Font Sizes in Webstudio" by Keep Learning.

 ## Author

- Frontend Mentor - [@MargM43](https://www.frontendmentor.io/profile/MargM43)