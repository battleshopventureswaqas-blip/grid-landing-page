# Frontend Mentor - Grid landing page solution

This is a solution to the [Grid landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/grid-landing-page). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- Open and close the navigation menu at any screen size



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

This project reinforced my understanding of CSS Grid and responsive design. Because the layout relies entirely on spacing and hairline dividers rather than images, setting up the exact grid fractions (`1.2fr 1fr 1fr`) was critical for matching the desktop design. 

I am particularly proud of implementing the mobile navigation menu without using any JavaScript. By utilizing the CSS Checkbox Hack, I was able to toggle the menu visibility and swap the hamburger/close icons dynamically:

```html
<!-- Hidden Checkbox for CSS-only menu toggle -->
<input type="checkbox" id="menu-toggle" class="menu-toggle-checkbox">

<!-- Label controlling the checkbox -->
<label for="menu-toggle" class="nav-menu-btn">
  <img src="assets/images/icon-menu.svg" alt="menu icon" class="icon-open">
  <img src="assets/images/icon-close.svg" alt="close icon" class="icon-close">
</label>

```css
Swapping icons based on checkbox state 
.menu-toggle-checkbox:checked ~ .navbar .icon-open { display: none; }
.menu-toggle-checkbox:checked ~ .navbar .icon-close { display: block; }

```



If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.



### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

[Gemini](https://gemini.google.com/app) - I used Gemini for minor code corrections, troubleshooting small issues, and making a few improvements while working on the project. It helped me understand and fix small problems during development.




### AI Collaboration

During this challenge, I used Gemini as an AI coding assistant for minor corrections, small code improvements, and occasional changes. The main HTML and CSS structure, layout, and implementation were developed by me, with AI assistance used only when needed to fix small issues or refine certain parts of the project.


The CSS Grid layout worked well for organizing the different sections of the page and making the design responsive. Using a mobile-first approach also helped me create a layout that works well on smaller screens and adapts to larger screen sizes. I also improved my understanding of CSS positioning, media queries, and the CSS Checkbox Hack while working on this challenge.





## Author


- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/battleshopventureswaqas-blip)


## Acknowledgments

I completed this challenge independently. I used Gemini as an AI assistant for minor corrections, small improvements, and troubleshooting when needed. The main design, HTML structure, CSS, and implementation were completed by me.
