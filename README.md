# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). 

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

- View the optimal layout on desktop (with a screen size of 144rem) and on mobiles(with a screen size of 37.5rem)

### Screenshot

![](./screenshot.jpg)

Two screeshots of the design have been added to the folder, one for desktop and the other one for mobile.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup to structure the whole document 
- Used sass for practice purposes and the fact that it makes coding css easier.
- Flexbox has been used to help with the layout
- Desktop-first then I decided to make the code responsive for mobile screen size of 37.5rem
- Google fonts to add any font I needed

### What I learned

I learned to use sass mixins to write media queries, and the use of variables for the color which is in my opinion a good practice, it makes the process much easier.

```css
@mixin respond($breakpoint) {
    @if ($breakpoint == phone) {
        @media (max-width: 23.44em) {@content};
    }
}
```


### Continued development

I will dive deeper to understand the process of picking the right size for project or website that I build. I will focus on the best practices to make my code responsive, but also the good practice in html to make my code more accessible by picking the right tags when structuring my html.


### Useful resources

MDN (https://developer.mozilla.org/)

## Author

- Website - [Gael Souleymane Nongnogo]
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)

## Acknowledgments

Thank you to frontend mentor for doing the work they do. 
