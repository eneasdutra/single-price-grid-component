# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Acknowledgments](#acknowledgments)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action
- Accessing content in a structured way through semantic HTML.

### Screenshot

![](./images/Screenshot.png)

### Links

- Solution URL: [https://github.com/eneasdutra/single-price-grid-component](https://github.com/eneasdutra/single-price-grid-component)
- Live Site URL: [https://eneasdutra.github.io/single-price-grid-component/](https://eneasdutra.github.io/single-price-grid-component/)

## My process

### Built with

- **HTML5 Semantic**: Use of tags such as `<main>`, `<section>`, `<article>`, and `<footer>` for better accessibility and SEO.
- **CSS Custom Properties (Variables)**: Organization of colors using the HSL format to facilitate maintenance.
- **Flexbox**: Used for center alignment of the page and simple internal elements.
- **CSS Grid**: Used to efficiently manage the two-column layout in the desktop version.
- **Mobile-First** Workflow: Styling was designed first for mobile devices and then expanded to desktop through Media Queries.

### What I learned

In this project, I emphasized the importance of structuring HTML with SEO in mind. Using `article` for pricing and differentiating factors sections helps search engines understand that they are independent pieces of content.

I also practiced color manipulation with HSL, which makes it much easier to create variations in tone (like the dark cyan used in the lower right corner) simply by changing the brightness.

```css
:root {
  --cyan: hsl(179, 62%, 43%);
  --dark-cyan: hsl(179, 62%, 38%); /* Apenas reduzi a luminosidade para criar profundidade */
}
```
### Continued development

I intend to continue focusing on:

- Accessibility (A11y): Ensuring all components are navigable via keyboard.
- Advanced CSS Grid: Exploring more complex layouts and the use of grid-template-areas.

## Author

- Frontend Mentor - [@eneasdutra](https://www.frontendmentor.io/profile/eneasdutra)
- Linkedin - [@eneasmdutra](https://www.linkedin.com/in/eneasmdutra/)
- Github - [@eneasdutra](https://github.com/eneasdutra)

## Acknowledgments

I thank the Frontend Mentor team for providing such inspiring designs for practice.
