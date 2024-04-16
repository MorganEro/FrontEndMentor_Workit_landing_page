# Frontend Mentor - Workit landing page solution

This is a solution to the [Workit landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/workit-landing-page-2fYnyle5lu). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Workit landing page solution](#frontend-mentor---workit-landing-page-solution)
  - [Table of contents](#table-of-contents)
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

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./assets/images/Screen%20Shot%202024-04-16%20workit%20landing%20page.png)

### Links

- Solution URL: (https://github.com/MorganEro/FrontEndMentor_Workit_landing_page)
- Live Site URL: (https://morganero.github.io/FrontEndMentor_Workit_landing_page/)

## My process

I attempted to use github projects and issue tickets to help come up with a solution. This was my first attempt to tackle the challenges in a more strategic and linear manner.

I began with creating issue tickets and adding them to a project. Then I made the css variables and some other reusable css.
Next was the html. After that, I attacked each section based on the mobile view. When I finished all sections, I made the media queries for each.
T

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

During this project, I learned a lot about using media queries and adjusting sizes for different screen views. At first, I set a media query for screens smaller than 928 pixels, trying to match it with the layout I designed in Figma for a 1440-pixel view. But this caused some big problems when switching between different screen sizes. So, I changed it to a query for screens smaller than 1024 pixels, which meant I had to tweak things to make sure everything looked right across different screen sizes. I'm thinking in future projects, I might try building each section and its media queries before moving on to the next one, to see if that works better for me. It was really satisfying to finish the mobile view before moving on to the others.

I also learned that the units you use for positioning can really affect how your layout looks on different screens. Using "vw" and "vh" can totally change things if you're not careful. I found a helpful website by Kevin Powell that helps you decide which units to use, called "https://whatunit.com/."

I also had to spend some time understanding stacking context. I found a useful YouTube video tutorial by Deeecode The Web that helped me out, which you can watch here: "https://www.youtube.com/watch?v=vUCWrPAsWic&t=1s". These were all important lessons that helped me improve my front-end development skills.

### Continued development

I had a great time trouble shooting with stacking context, z-indexing and positioning. I look forward to future challenges and seeing how quickly I can tackle more difficult challenges with the knowledge gained from this project.

### Useful resources

- [Kevin Powell's Unit guide](https://whatunit.com/) - This helped me with deciding which units to use when I was facing problems with massive position shifts in responsive view.
- [Deeecode The Web](https://www.youtube.com/watch?v=vUCWrPAsWic&t=1s) - This is a well explained and simplified explanation of Z-index and solving problems with stacking context.

## Author

- Website - [Morgan Ero] (https://github.com/MorganEro)
- Frontend Mentor - [Morganero](https://www.frontendmentor.io/profile/MorganEro)

## Acknowledgments

I want to express my gratitude to Kevin Powell for the fantastic content he provides on YouTube. His tutorials have been invaluable in simplifying CSS and frontend development.

A big thank you goes to Deeecode The Web for his insightful YouTube video. I look forward to returning to his channel for more learning opportunities.

I'd also like to extend my thanks to a Peter Bachman, a member of the Fronted Mentor community. When I hit a roadblock while trying to create the curves for the bottom of the top and middle sections, I found inspiration in his solution. Although I ultimately devised a different approach, his example provided valuable insight and reassurance.
