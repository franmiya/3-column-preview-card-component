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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot
Desktop: 1440px

![Desktop: 1440px](https://github.com/franmiya/3-column-preview-card-component/assets/154415965/3434198a-6306-4bd9-a88b-8919eb567ce2)

Mobile: 375px

![Mobile: 375px](https://github.com/franmiya/3-column-preview-card-component/assets/154415965/a24ca930-b1bd-4c6e-8e8e-d068c51efe3c)

### Links

- Solution URL: https://github.com/franmiya/3-column-preview-card-component.git
- Live Site URL: https://franmiya.github.io/3-column-preview-card-component/

## My process

### Built with

- Semantic HTML5 markup
- Bootstrap Framework
- SASS preprocessor

### What I learned

```html
 <div class="container mt-5 p-3 p-md-4 p-lg-5">
        <div class="row align-items-center">
            <div class="col-md-6 col-lg-4 first-column p-3 p-md-4 p-lg-5">
            </div>
            <div class="col-md-6 col-lg-4 second-column p-3 p-md-4 p-lg-5">
            </div>
            <div class="col-md-6 col-lg-4 third-column p-3 p-md-4 p-lg-5">
            </div>
        </div>
    </div>

```
```css
@media screen and (max-width: 992px) {
    p {
        margin-bottom: 15px;
    }
}
@media screen and (max-width:600px) {
    p {
        margin-bottom: 15px;
    }
}

```

### Continued development

I will continue learning bootstrap columns and implementing media query

### Useful resources

- [Example resource 1](https://www.w3schools.com/css/css3_mediaqueries_ex.asp) - This helped me for adding a responsive margin in paragraph.
- [Example resource 2](https://getbootstrap.com/docs/5.0/layout/columns/) - This helped me to create a column


## Author

- Frontend Mentor - [@franmiya](https://www.frontendmentor.io/profile/franmiya)
