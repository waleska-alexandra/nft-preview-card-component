# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](https://github.com/waleska-alexandra/nft-preview-card-component/blob/main/project-preview.png)


### Links

- Solution URL: [GitHub](https://github.com/waleska-alexandra/nft-preview-card-component)
- Live Site URL: [Web Page](https://waleska-alexandra.github.io/nft-preview-card-component/)
- Solution URL: [Frontendmentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U/hub/frontend-mentor-nft-preview-card-component-HJwapwQr5)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:


```css
 .overlay {
    position: absolute;
    top: 20px;
    bottom: 0;
    left: 25px;
    right: 0;
    width: 290px;
    height: 270px;
    opacity: 0;
    background-color: var(--cyan);
    border-radius: 10px;
  }
  
  .view {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
}
  
  .image-container:hover .overlay {
    opacity: 0.5;
    cursor: pointer;
}
  
  .image-container:hover .overlay + .view {
    display: block;
}
```


### Continued development

I think my biggest weakness is making responsive web. So this is my learning goal, along with javascript.



## Author

- Frontend Mentor - [@waleska-alexandra](https://www.frontendmentor.io/profile/waleska-alexandra)
- Twitter - [@rangelwaleska_](https://twitter.com/rangelwaleska_)

