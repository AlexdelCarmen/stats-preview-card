# Frontend Mentor - Stats preview card component

![Design preview for the Stats preview card component coding challenge](./design/desktop-preview.jpg)

## Welcome! 👋

Thanks for checking out this front-end coding challenge.

[Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects.

**To do this challenge, you need a basic understanding of HTML and CSS.**

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

- Solution URL: [Source Code](https://github.com/AlexdelCarmen/stats-preview-card)
- Live Site URL: [Live Page](https://alexdelcarmen.github.io/stats-preview-card/)

## My process

I structured the HTML first, with a mobile layout first mindset, then styled it for mobile screens, and lastly, added a media query to handle desktop displays.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

A good second run to add a "filter" on an image.  

```css
@media (min-width: 1000px) {
  .stats-container {
    flex-direction: row-reverse;
    width: 80%;
    align-items: center;
    justify-content: center;
  }

  .mobile-img {
    display: none;
  }

  .desktop-img {
    display: block;
    width: 508px;
    margin-top: 4px;
    border-top-right-radius: 15px;
    border-bottom-right-radius: 15px;
  }

  .stats-card {
    width: 50%;
    padding: 4rem;
    min-width: 500px;
    max-width: 500px;
    margin-top: 3px;
    border-bottom-left-radius: 15px;
    border-bottom-right-radius: 0px;
    border-top-left-radius: 15px;
  }

  .stats-title {
    text-align: left;
  }

  .stats-text {
    text-align: left;
    padding: unset;
  }

  .stats-section {
    display: flex;
    align-items: center;
    justify-content: space-around;
  }

  .img-filter {
    width: 508px;
    margin-top: 4px;
    border-top-right-radius: 15px;
    border-bottom-right-radius: 15px;
    border-top-left-radius: 0;
  }
}


```

### Continued development

Still needing to get a better eye for sizes/colors.

### Useful resources

- [W3Schools](https://www.w3schools.com/) - general resource for coding, used it for :root clarifications.

## Author

- Website - [Github Profile](https://github.com/AlexdelCarmen)
- Frontend Mentor - [@AlexdelCarmen](https://www.frontendmentor.io/profile/AlexdelCarmen)
- Twitter - [@AlekBorchov](https://twitter.com/AlekBorchov)

## Acknowledgments

Thanks Wendigoon for ranting on the back for hours on end while I code.
