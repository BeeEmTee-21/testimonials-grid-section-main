# Frontend Mentor - Testimonial Grid Section Solution

This is my solution to the [Testimonial Grid Section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help me improve my coding skills by building realistic projects.

## Table of contents

* [Overview](#overview)

  * [The challenge](#the-challenge)
  * [Screenshot](#screenshot)
  * [Links](#links)
* [My process](#my-process)

  * [Built with](#built-with)
  * [What I learned](#what-i-learned)
  * [Continued development](#continued-development)
  * [Useful resources](#useful-resources)
  * [AI Collaboration](#ai-collaboration)
* [Author](#author)
* [Acknowledgments](#acknowledgments)

## Overview

### The challenge

The challenge was to build a responsive testimonial grid section based on the design provided by Frontend Mentor.

Users should be able to:

* View the optimal layout for the site depending on their device's screen size.
* See the testimonial cards arranged correctly on both mobile and desktop screen sizes.

### Screenshot

![Desktop testimonial grid](./images/Desktop%20Frontend%20Mentor%20Testimonials-grid-section-main.png)

![Mobile testimonial grid](./images/Mobile%20Frontend%20Mentor%20Testimonials-grid-section-main.png)

### Links

* Solution URL: **Add your Frontend Mentor solution URL here**
* Live Site URL: **Add your live site URL here**

## My process

I started the project by building the HTML structure and then worked on the styling and layout of the testimonial cards.

I used a combination of CSS Grid and Flexbox to create the overall layout. I started with the mobile layout and then used media queries to adjust the design for larger screens.

During the development process, I experimented with different ways of positioning the testimonial cards and their contents. This helped me understand how different CSS layout techniques can work together rather than relying on only one layout method.

One of the things I discovered was how to handle elements that should appear on one screen size but not another. I used `display: none` to hide an image in the mobile layout and then used a media query to make the image visible again on the desktop layout.

I also spent time working with positioning and `z-index`. This helped me understand how elements can be layered and positioned relative to their containing elements.

### Built with

* Semantic HTML5 markup
* CSS custom properties
* Flexbox
* CSS Grid
* Mobile-first workflow
* Media queries

### What I learned

This project taught me a lot about combining different CSS layout techniques.

One of the biggest things I learned was how **Flexbox and CSS Grid can be used together**. Grid was useful for creating the main structure of the testimonial section, while Flexbox helped with arranging and aligning content inside individual cards.

I also learned more about responsive design and how elements can be shown or hidden depending on the screen size. For example, I learned that `display: none` can be used to remove an element from the layout on mobile and then a media query can be used to display it again on larger screens.

Another major area I learned about was **positioning and z-index**. I gained a better understanding of how `position: relative` and `position: absolute` work together when positioning an element inside a container.

I also learned that `z-index` works within the context of positioned elements and can be used to control which elements appear above or below others. This was particularly useful when working with images and overlapping elements in the testimonial cards.

Overall, this project gave me a much better understanding of how different CSS properties interact with each other to create more complex layouts.

### Continued development

I want to continue improving my understanding of CSS Grid and Flexbox, especially when using them together to create responsive layouts.

I also want to practice positioning and stacking contexts more so that I can confidently work with overlapping elements without relying on trial and error.

Another area I want to continue developing is responsive design. I want to become faster at looking at a design and identifying how its layout should change between mobile, tablet, and desktop screen sizes.

As I continue working through Frontend Mentor challenges, I also want to improve my ability to translate a visual design into a clean HTML and CSS structure while reducing the amount of time I spend figuring out individual layout problems.

### Useful resources

* [Frontend Mentor](https://www.frontendmentor.io/) - This challenge provided the design and requirements for the project.
* [MDN Web Docs](https://developer.mozilla.org/) - Useful for understanding HTML and CSS concepts and checking CSS properties.
* [CSS-Tricks](https://css-tricks.com/) - Useful for learning CSS layout techniques, particularly Flexbox and Grid.

### AI Collaboration

I used AI during this project as a learning and troubleshooting aid.

I used AI to help me understand CSS concepts that I was still learning, particularly around Grid, Flexbox, positioning, responsive layouts, and `z-index`.

AI was also used to help me create and structure this README based on the work I completed during the project.

I used AI to explain concepts and help me understand problems rather than having it build the project for me. The project itself was developed by me, while AI helped me better understand the CSS concepts I encountered during development.

## Author

* Website - **Add your website here**
* Frontend Mentor - **Add your Frontend Mentor profile here**
* GitHub - **Add your GitHub profile here**

## Acknowledgments

Thanks to Frontend Mentor for providing the challenge and design that I used to practice my HTML and CSS skills.
