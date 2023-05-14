# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [Github](https://github.com/parthamallick313/fylo-data-storage-component)
- Live Site URL: [Netlify](https://fylo-data-storage-fmio.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow
- Tailwind CSS

### What I learned

For me, the small triangle like structure is the main challenge here. I have implemented it with the clip path property.

```html
<div
  class="rounded-sm md:absolute md:top-0 md:right-8 md:w-12 md:h-1/3 md:bg-white z-0 clip"
></div>
```

```css
.clip {
  clip-path: polygon(0 0, 100% 0, 100% 100%, 0 0);
}
```

## Author

- Frontend Mentor - [@parthamallick313](https://www.frontendmentor.io/profile/parthamallick313)
