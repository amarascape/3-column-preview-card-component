# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

- [Desktop View](screenshots/desktop-view-screenshot.png)
- [Mobile View](screenshots/mobile-view-screenshot.png)

### Links

- Solution URL: [https://amarascape.github.io/3-column-preview-card-component/](https://amarascape.github.io/3-column-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- Bootstrap
- CSS Grid
- Mobile-first workflow

### What I learned

- I prefer adding my responsive styles in a separate document and then importing more than one document.

```css
/* || MOBILE FIRST STYLES */
...
```
```css
/* || RESPONSIVE STYLES */
...
```
```html
<link rel="stylesheet" href="styles/styles.css">
<link rel="stylesheet" href="styles/responsive.css">
```

- ```text-transform: uppercase; ``` vs ```text-transform: capitalize;```

```text-transform: uppercase; ``` capitalizes all text while ```text-transform: capitalize;``` capitalizes only the first letter.

- It's better to use ```<a>``` and style as buttons than to use ```<button>```

```html
<a class="btn btn-suvs" href="#">Learn More</a>
```
```css
.btn {
  /* bootstrap */
  border-radius: 2rem;
}

.btn-sedans {
  color: var(--bright-orange);
  background-color: white;
}

.btn-sedans:hover {
  color: white;
  background-color: var(--bright-orange);
  border-color: white;
}
```

### Useful resources

- [text-transform - CSS: Cascading Style Sheets | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/text-transform) - MDN Reference for ```text-transform```
- [A Complete Guide to Flexbox | CSS-Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Used as a referece for ```align-self``` for flexbox items
- [Chrome Developer Tools](screenshots/desktop-view-screenshot.png) - Allows you to experiment with different settigns on the flex box without changing the CSS. Makes it really easy and simple to experiment with how different CSS rules would work. 

## Author

- Github - [amarascape](https://github.com/amarascape)
