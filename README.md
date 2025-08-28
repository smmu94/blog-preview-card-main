# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).  
Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
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

### Screenshot

![](./images/screenshot.png)

### Links

- Solution URL: _(coming soon)_
- Live Site URL: _(coming soon)_

## My process

### Built with

- Semantic HTML5 markup  
- CSS custom properties (variables)  
- Flexbox  
- Mobile-first workflow  
- BEM naming

### What I learned

My main takeaway from this project was how to use the clamp() CSS function to create a fluid, responsive design without relying on media queries. This allowed me to control the minimum and maximum sizes of elements, ensuring they scale smoothly across different screen sizes.

**Typography example with clamp**

```css
:root {
  /* ... */
  /* Typography */
    --font-family: "Figtree", sans-serif;
    --text-preset-1: 800 clamp(1.25rem, 2vw, 1.5rem)/1.5 var(--font-family);
}
```

### Continued Development

- Keep practicing responsive design with modern CSS techniques like clamp().
- Explore CSS Grid for more complex layouts.

### Useful resources  

- [MDN – clamp()](https://developer.mozilla.org/en-US/docs/Web/CSS/clamp)  
- [MDN - Using CSS custom properties](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_cascading_variables/Using_CSS_custom_properties)
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)  

## Author  

- Frontend Mentor – [@smmu94](https://www.frontendmentor.io/profile/smmu94)  
- GitHub – [@smmu94](https://github.com/smmu94)  
