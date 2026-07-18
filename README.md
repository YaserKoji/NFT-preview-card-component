# Frontend Mentor - NFT preview card component solution

This is my professional solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-S2Z15w3IS). 

## Overview

### The challenge

Users should be able to:
- View the optimal layout depending on their device's screen size.
- See hover states for all interactive elements on the page.

### Screenshots

| Design Preview |
|--- |
| ![Design](./design/desktop-design.jpg) |

---

## My Process

### Built with

- **Semantic HTML5** markup (Using `<main>` as the core landmark)
- **CSS Custom Properties** (Variables) for color palettes
- **CSS Flexbox** for centering the layout, price distribution, and avatar alignment
- **Fluid Responsive Design** using `max-width` and percentage-based widths for seamless mobile adaptation

### What I learned

In this challenge, I learned how to create inherently responsive card components that scale beautifully across mobile and desktop screens using smart fluid sizing, eliminating the need for redundant media queries:

```css
.container {
    max-width: 20.875rem;
    width: 90%;
    margin: 1.5rem;
}
I also mastered how to properly override the browser's default 3D styles for the <hr> element to achieve a clean, modern flat line divider:

CSS
hr {
  border: none;
  border-top: 1px solid var(--Blue4);
  margin: 1rem 0;
}

Author:

Frontend Mentor - @YaserKoji
GitHub - @YaserKoji