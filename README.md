![Screenshot 2021-07-13 at 12-19-42 Frontend Mentor 3-column preview card component](https://user-images.githubusercontent.com/84665360/125435740-234fece9-440f-443e-bb86-8d3b178a80de.png)
![Screenshot 2021-07-13 at 12-19-42 Frontend Mentor 3-column preview card component](https://user-images.githubusercontent.com/84665360/125435767-d917ab58-4e8e-4cb9-b62f-5b1776960c34.png)
![Screenshot 2021-07-13 at 12-20-05 Frontend Mentor 3-column preview card component](https://user-images.githubusercontent.com/84665360/125435780-25b618de-2a60-4864-94b5-bbf300d48286.png)
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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

#### Desktop View

![Screenshot 2021-07-13 at 12-20-05 Frontend Mentor 3-column preview card component](https://user-images.githubusercontent.com/84665360/125435842-db241edf-3c02-418d-85a9-19aa23418b8a.png)

#### Mobile view

![Screenshot 2021-07-13 at 12-19-42 Frontend Mentor 3-column preview card component](https://user-images.githubusercontent.com/84665360/125435871-4e836fff-4374-497b-beda-cef41cbfe850.png)

### Links

- Solution URL: [Challenge Solution](https://your-solution-url.com)
- Live Site URL: [Live Site](https://zaidmarrie.github.io/3-column-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

In this challenge I learnt how to use CSS Grid implicit row/column properties as well as made use of the auto-fit property to automatically resize and change the layout of my grid as the screen size changes.

Below I added code snippets, see below:

```css
.card-container{
        margin: 150px 20%;
        grid-template-rows: 1fr;
        grid-template-columns: auto(auto-fit, minmax(250px, 350px));
        grid-auto-flow: column;
    }
}
```

### Continued development

I would like to continue focusing on CSS Grid in future projects. This property is very powerful and I am not completely comfortable with it. In future projects I want to refine and perfect how I use this particular property.

### Useful resources

- [Resource 1](https://youtu.be/cMWnIX3ukLI) - This helped me for css grid implicit properties. I really found this useful as it helped me better understand these concepts.
- [Resource 2](https://cssgridgarden.com/) - This is an amazing site which enabled me to explore and experiment with css grid.

## Author

- Frontend Mentor - [@ZaidMarrie](https://www.frontendmentor.io/profile/ZaidMarrie)

## Acknowledgments

I would like to give thanks to Kevin Powell for his great work of helping us learn and understand how to use css and html as well as his teachings of good practices. I am very grateful for all his help and assistance.
