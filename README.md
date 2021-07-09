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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Github](https://github.com/aimdexter/3-column-preview-card-component-main)
- Live Site URL: [Demo](https://aimdexter.github.io/3-column-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- Sass
- Mobile-first workflow

### What I learned

- Sass : variables

$breakpoint-mobile: 375px;
$breakpoint-desktop: 376px;
$Brange: hsl(31, 77%, 52%);
$Dark: hsl(184, 100%, 22%);
$Very_dark: hsl(179, 100%, 13%);

- Sass : Mixins
@mixin button{
        background-color: white;
        font-family: 'Lexend Deca', sans-serif;
        border-radius: 3rem;
        padding: 1rem 2rem;
        margin-top: 10px;
        border-width: 0rem;
        font-size: 15px;
    }
.grid-item-suvs{
        padding: 3rem;      
        background-color: $Dark;
        button{
            @include button;
            color: $Dark;
        }
    }

### Useful resources

- [Sass cheatsheet](https://devhints.io/sass)
- [Grid cheatsheet](https://grid.malven.co/)

## Author

- Website - [Aimdexter] (https://github.com/aimdexter)
- Frontend Mentor - [@aimdexter](https://www.frontendmentor.io/profile/aimdexter)

## Acknowledgments

Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
Coded by <a href="https://github.com/aimdexter/">Your Name Here</a>.
