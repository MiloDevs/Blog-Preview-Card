# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover and focus states for all interactive elements on the page

### Screenshot

![](/assets/images/screenshot.png)

### Screensot Active State
![](/assets/images/screenshot-active-state.png)

### Links

- Solution URL: (https://github.com/MiloDevs/Blog-Preview-Card)
- Live Site URL: ([Add live site URL here](https://your-live-site-url.com))

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- CSS Has Selector
- CSS @font-face 

### What I learned

- Use of :has() selector to toggle the hover state of the card when you hover the title
- Use of @font-face to import locally stored fonts.

```css
.card:has(.card_title:hover){
    box-shadow: 10px 10px 0px 0px var(--neutral-black);
    transform: translate(0px, -3px);
    transition: all 0.3s ease-in-out;
}
```

### Continued development

Improve the responsiveness of the card element

### Useful resources

- [:has('')](https://webkit.org/blog/13096/css-has-pseudo-class/) - This helped me learn how to select parents based on children using the :has() selector. With this I could style the Card based on it's child's (the title) active state

- [@font-face](https://www.codeconcisely.com/posts/css-import-font/) - This was a really helpful article that helped me learn about @font-face tags for importing local fonts

## Author

- Frontend Mentor - [@MiloDevs](https://www.frontendmentor.io/profile/MiloDevs)

