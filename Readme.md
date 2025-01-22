# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Project Screenshot](/Assets/Screenshot.png)


### Links

- Live Site URL: (https://wizdev0.github.io/NFT.com/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Position
- Media Quaries

### What I learned

I learnt how to make a card and also how to make an overlay with transitions and animations.

```css
.card-header .overlay{
    position: absolute;
    top: 45%;
    left: 50%;
    width: 90%;
    height: 80%;
    background: rgba(0, 200, 150, 0.5);
    display: flex;
    justify-content: center;
    align-items: center;
    opacity: 0;
    transition: opacity 0.3s ease;
    transform: translate(-50%, -50%);
    border-radius: 10px;
}

.card-header .overlay img{
    width: 40px;
    height: 40px;
    z-index: 10;
    opacity: 1;
}


.card-header:hover .overlay{
    opacity: 1;
}


.card-header:hover img{
    opacity: 0.3;
}
```


### Continued development
In the future am still going to learn more about transitions, Positioning, animations, flexbox and grid.

### Useful resources

- [ChatGpt](https://chat.openai.com) - This AI model really helped me a lot when I was on the project, it helped me to Write the code in an orderly manner and also helped me to remember certain things I can recall.
- [Google font](https://fonts.google.com) - Google fonts really helped me with the font required for the project and also the boldness of the font.


## Author

- Frontend Mentor - [@Wizdev0](https://www.frontendmentor.io/profile/Wizdev0)
- Twitter - [@otutech](https://www.twitter.com/otutech)

