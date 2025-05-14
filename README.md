# Frontend Mentor - Skilled e-learning landing page solution

This is a solution to the [Skilled e-learning landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/skilled-elearning-landing-page-S1ObDrZ8q). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

This project design really had me in a twirl. The background-image was a hassle! I couldn't get it to work, that's until I used @media queries but I feel this was a bit messy since my design ended up being very glitchy. 

I managed to somewhat make it work but in the end I need to find a better approach and/or I need to figure out how to correctly use @media queries w/ background-size and position.

Another mistake of mine was not making my text and text containers responsive. I accidnetly added px instead of %, so it could size correctly with the viewport. 

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

<img src="./desktop skilled elearning design.png"/>
<img src="./mobile skilled elearning design.png"/>


### Links

- Live Site URL:

## My process

HTML: 
--Process began with grouping and naming the classes accordingly. 
--Double checking for any redundancy within the class names making sure everyhting makes sense semantically 

CSS: 
--Began with the universal and body selectors assiging their respective values 
--used the CSS custom properties i.e., :root / var()
--sized and positioned the main container 
--stylize the card design
--proceeded designing the navigation header, main header, grid container, and then footer
--added all font weights, size and colors
--finished  with the buttons and their hover effects

### Built with

- Semantic HTML5 Markup
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

Coming into this project, I learned that setting up a background image can be very difficult. I struggled to position the image correctly within all the viewports, which meant not having fluidity when changing throughout all the viewport sizes instead it had a glitchy small-to-big change in size. 

I somewhat got some good responsiveness after I used the % and vw to get a responsive outcome. 

I also made the mistake of not using px instead of %  on my .main-header, which created an unresponsive box.

## Author

--Website: (https://www.rarroyoharo.com)<a href="https://www.rarroyoharo.com" target="_blank">rarroyoharo.com</a> 
--Frontend Mentor - [@RiickyRiick]<a href="https://www.frontendmentor.io/profile/RiickyRiick" target="_blank">@RiickyRiick</a> 

