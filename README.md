# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

- [Desktop Preview](solution-screenshots/desktop-preview.png)
- [Mobile Preview](solution-screenshots/mobile-preview.png)

### Links

- Solution URL: [FrontEnd Mentor: My Solution](https://www.frontendmentor.io/solutions/responsive-4-card-feature-section-using-css-flexbox-aoUWHBpjR)
- Live Site URL: [GitHub Page: 4 Card Feature Section](https://anoshaahmed.github.io/fem07-4-card-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- Working on this project helped me understand how mobile-first workflow is easier than desktop-first.
- I also used overflow: hidden property today for the first time and I didn't know of it before so yay.
- I also used the ::before pseudoselector for the first time for the top "border":
```css
.box::before {
  content: "";
  height: 0.25rem;
  width: 100%;
  position: absolute;
  top: 0;
  left: 0;
  background-color: black;
}
```

### Continued development

I want to continue using mobile-first workflow and really get it down right.

## Author

- Website - [Anosha Ahmed](https://www.anoshaahmed.com)
- Frontend Mentor - [@anoshaahmed](https://www.frontendmentor.io/profile/anoshaahmed)
- Twitter - [@anosha1ahmed](https://www.twitter.com/anosha1ahmed)
