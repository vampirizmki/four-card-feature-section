# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

### Links

- Live Site URL: [https://vampirizmki.github.io/four-card-feature-section/](https://vampirizmki.github.io/four-card-feature-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

During this project, I ran into a few key layout challenges and worked through solving them:

1. **Avoid Code Duplication:**
   - Writing repetitive styles for all four cards was inefficient.
   - **Solution:** Used a shared `.card` class for common styles and separate utility classes for unique properties (like border colors). An HTML element can have multiple classes.

2. **Mastering CSS Grid Layout:**
   - Initially defined grid layout properties directly on `.card` instead of the container `.boxes`, and used quotes incorrectly inside `grid-area`.
   - **Solution:** Properly applied `grid-template-areas` to the grid container and assigned `grid-area` values without quotes in CSS.

3. **Resolving `column-gap` Conflicts:**
   - `1fr` flexible grid columns conflicted with fixed card widths (`25rem`), resulting in unintended gaps.
   - **Solution:** Aligned grid column definitions with the actual card width constraints to remove conflicting styles.

4. **Centering Grid Content:**
   - Cards shifted to the left when fixed-width grid columns were smaller than the overall container width.
   - **Solution:** Used `justify-content: center` to evenly distribute extra horizontal space.

### Continued development

- Further practice with advanced CSS Grid properties (`justify-content`, `align-items`, and dynamic layout calculations).
- Building more complex responsive layouts seamlessly.

## Author

- Frontend Mentor - [@vampirizmki](https://www.frontendmentor.io/profile/vampirizmki)
- GitHub - [@vampirizmki](https://github.com/vampirizmki)