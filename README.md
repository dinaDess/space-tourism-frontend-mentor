# Frontend Mentor - Space tourism website solution - By Oshyeld

This is a solution to the [Space tourism website challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/space-tourism-multipage-website-gRWj1URZ3). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for each of the website's pages depending on their device's screen size
- See hover states for all interactive elements on the page
- View each page and be able to toggle between the tabs to see new information

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com) (Loading...)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com) (Loading...)

### Screenshot
Here is a screenshot of my landing page in Firefox Developer.
[Screenshot of the Landing Page](./myPreview.png)
<img src="./myPreview.png" alt="My Homepage Preview"/>

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned
  #### CSS backdrop-filter property
On the landing page, the main thing I learned is how to create a blurred background.
I first opted for **filter : blur(..px)** but the only result I got was the whole section and the text blurred instead of the
image in the background. 
And then I discovered **backdrop-filter: blur(..px)** who did the job pretty well until I realised that it wasn't supported on Firefox and no prefix can change that fact. 
So I did some quick fixes in my browser i.e **setting the layout.css.backdrop-filter.enabled and gfx.webrender.all preference to true in about:config** (Thanks to caniuse (https://caniuse.com/) and MDN). 


  #### Github Pages
Here, I learned how to setup Github Pages to host my static website.


### Continued development

Learn JS


### Useful resources

- [Custom CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/) - I used this resource for the CSS Reset.
- [Backdrop-filter](https://developer.mozilla.org/en-US/docs/Web/CSS/backdrop-filter) - This helped me a lot to create the blurred background on the mobile navigation (i.e. hamburger menu). Also, you need to make some tweaks in your Firefox browser in order to make it visible.


## Author

- Website - [Add your name here](https://www.your-site.com) (Still loading...)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername) (Loading...)
