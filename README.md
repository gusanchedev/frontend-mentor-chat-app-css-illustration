# Frontend Mentor - Chat app CSS illustration solution

This is a solution to the [Chat app CSS illustration challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the component depending on their device's screen size

### Screenshot

![](./design/desktop-preview.jpg)

### Links

- Solution URL: [@Github](https://github.com/gustavosanchezgalarza/frontend-mentor-chat-app-css-illustration)
- Live Site URL: [@Vercel](http://frontend-mentor-chat-app-css-illustration-gusanchedev.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas I want to highlight is a great way to reinforce my own knowledge.

Using multiples CSS stylesheets files for different screen sizes with media queries
```html
    <link rel="stylesheet" href="./css/mobile.css" />
    <link rel="stylesheet" href="./css/tablet.css" media="screen and (min-width: 640px) and (max-width:1023px)"/>
    <link rel="stylesheet" href="./css/desktop.css" media="screen and (min-width:1024px)"/>
```
Using multiple background images
```css
body {
  background-image: url("../images/top-background-desktop.svg"),
    url("../images/bottom-background-desktop.svg");
  background-position: top -200px left -185px, top 150px right -300px;
  background-repeat: no-repeat;
  background-size: 40%, 45%;
}
```
Creating SVG background images with linear gradient colors
```html
<svg width="673" height="1440" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="grad1" x1="0%" y1="100%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:hsl(264, 100%, 61%);stop-opacity:1" />
      <stop offset="100%" style="stop-color:hsl(293, 100%, 63%);stop-opacity:1" />
    </linearGradient>
  </defs>
  <rect x="5" y="5" rx="90%" ry="20%" width="673" height="1024" style="fill:url(#grad1)" />
</svg>
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

New projects will include Javascript events and DOM manipulation.

### Useful resources

- [SVG <rect>](https://www.w3schools.com/graphics/svg_rect.asp) - This helped me to create svg background images.
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This is an amazing article which helped me finally understand Flexbox
- [CSS Box Shadow](https://css-tricks.com/almanac/properties/b/box-shadow/) - CSS Tricks article about box-shadow property in CSS.

## Author

- Website - [gusanche.dev](https://www.gusanche.dev) (Coming Soon!)
- Frontend Mentor - [@gustavosanchezgalarza](https://www.frontendmentor.io/profile/gustavosanchezgalarza)
- Twitter - [@gusanchedev](https://www.twitter.com/gusanchedev)

