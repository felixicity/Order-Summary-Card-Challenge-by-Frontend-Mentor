# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./images/Screenshot%202026-10-06%20123341.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/felixicity/Order-Summary-Card-Challenge-by-Frontend-Mentor)
- Live Site URL: [Add live site URL here](https://felixicity.github.io/Order-Summary-Card-Challenge-by-Frontend-Mentor/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I Undestood background position and box-shadows in another better way

```html
<div class="card-pricing">
  <div class="card-pricing-info">
    <div class="plan-icon">
      <img src="./images/icon-music.svg" alt="music icon svg" />
    </div>
    <div class="card-plan">
      <p class="plan-desc">Annual Plan</p>
      <p class="plan-price">$59.99/year</p>
    </div>
  </div>
  <span class="pricing-action">Change</span>
</div>
```

```css
body {
  font-family: "Red Hat Display";
  background-image: url("./images/pattern-background-desktop.svg");
  background-color: var(--Blue-100);
  background-repeat: no-repeat;
  background-position: 0% -140%;
  max-height: 100dvh;
  font-weight: var(--font-regular);
  font-size: var(--base-font);
}
```

## Author

- Website - [Chukwu Felix](https://chukwu-felix.vercel.app/)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/felixicity)

## Acknowledgments

I did this challenge to teach my students some css
