# Frontend Mentor – Huddle landing page with a single introductory section

This is my solution to the [Huddle landing page with a single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). A responsive two-column landing page built with semantic HTML5 and CSS Flexbox.

## Table of contents

- [Built with](#built-with)  
- [What I learned](#what-i-learned)  
- [Continued development](#continued-development)  

## Built with

- **Semantic HTML** for clear document structure and accessibility  
- **CSS**  
  - Custom properties for theming  
  - Flexbox for layout (`flex: 1 1 60%` / `flex: 1 1 40%`) 
- Mobile-first workflow with a single media-query breakpoint  

## What I learned

1. **Precision with Flexbox**  
   Defining `flex-grow`, `flex-shrink`, and `flex-basis` (the three parts of the `flex` shorthand) helped me control how each column expands, shrinks, and sets its starting width. I use flex box a lot but not very often `flex-grow`, `flex-shrink`, and `flex-basis` seperate or even together so good practice to use. Example from my project. 
   ```css
   .left-side  { flex: 1 1 60%; }
   .right-side { flex: 1 1 40%; }
