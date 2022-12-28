# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

**Desktop**

![](./solution/preview-card-solution-desktop.png)

**Mobile**

![](./solution/preview-card-solution-mobile.png)

### Links

- Solution URL: [Github Repo](https://github.com/gian-noche/frontend-mentor-product-preview-card)
- Live Site URL: [Github Pages](https://gian-noche.github.io/frontend-mentor-product-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- Further understanding of flexbox.

- The weird gap/white space below an image. Since images are inline elements and they are, by default, aligned at the baseline of the text making the white space caused by the *descenders*.

- To use different images based on the screen size, you can use ```html
<source>```
For example:

```html
<picture>
  <source srcset="image1.jpg" media="(min-width: value1)">
  <source srcset="image2.jpg" media="(min-width: value2)">
  <img src="image3.jpg">
</picture>
```
### Continued development

Hopefully in the future I'd be able to make images more responsive and rely less on media query by using responsive layout instead through flexbox as well as figure out the best breakpoints for the layout.

### Useful resources

- [MDN](https://developer.mozilla.org/)
- [Stackoverflow](https://stackoverflow.com/)

## Author

- Github - [pewpewhamster(gian-noche)](https://github.com/gian-noche)
- Linkedin - [Gian Levi Noche](https://www.linkedin.com/in/giannoche/)
- Frontend Mentor - [@gian-noche](https://www.frontendmentor.io/profile/gian-noche)
- Instagram - [@pewpewhamster](https://www.instagram.com/pewpewhamster/)

## Acknowledgments

Thank you **Frontend Mentor** for this challenge!
Thank you [Grace!](https://www.buymeacoffee.com/gracesnow) for responding to my question on the Frontend Mentor Slack channel! 