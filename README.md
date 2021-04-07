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



## Overview

I have just started learning web development roughly 3 weeks ago. I have been going hard on tutorials, forums and articles (as well as my own coding, of course). I have just come across FrontendMentor.com which provides a number of challenges. This is my first attempt!

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![./screenshot_desktop-view.jpg]
![./screenshot_mobile-view.jpg]

### Links

- Solution URL: [https://github.com/steppan26/Challenge-01--3-column-preview-card]
- Live Site URL: [https://steppan26.github.io/Challenge-01--3-column-preview-card/]

## My process

My initial thought was to work on building out the HTML by adding in the corresponding elements, the great part of this design is that it is very modular, which means that i could focus on getting one card right and then apply the same structure to the other elements. I opted to use <section> tags for each card to help with accessibility, each section was then wrapped in a div element with a ".main" class. Naturally the I used <H1> tags for the titles, <p> tags for the main body of text and a <button> tag for the button.

My next thought was to work the CSS, but due to the responsive design of the project, I decided to start by building out mobile first, and to add complexity as I build up to the desktop size.
  I started by creating custom properties for the different colors and fonts which would be used in the project.
  I then started styling the fonts for the different elements and classes (fonts, sizes, colors, background colours).
  Next I worked on the cards styling, where I set the padding, colors and width, starting with the "card" backgrounds and then the other elements.
  Once I was happy with the spacing the next step was to style the button. I had a little bit of trouble with the borders, which appear on hover, causing the element to grow and break the increase the size of the card.
  The next step was to work on the desktop version, here I used a media querie (set to 800px) which would then apply seperate style at that higher resolution.
  This step is where I really benefited from my previous decision to wrap everything in a div (.main) which I can now change its display type to use flexbox with a row direction and and set to stretch vertically (to ensure all cards are always the same size).
  A few extra flair styles were added (mostly extra padding and margins) to match the style provided by the project manager.
  I then iterated back and forth tweaking numbers to more closely match the designs provided, followed by a clean up of the code.


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

I went into this project with the intention to think through the design and structure before jumping in, and to implement a mobile-first approach. These were constantly at the forefront of my mind whilst working on this project and, although it is a somewhat simple project, I can see how these techniques could make a huge difference when working on larger projects.

I also learned that adding a border to an element adds it the outside, causing the overall size of the element to increase. 

### Continued development

I would like to work on improving the quality of my code on first walk through, so as to reduce the amount of clean up needed at the end.

### Useful resources

- [W3Schools](https://www.w3schools.com) - I really like this site when I need a straight answer with demos to play with.
- [Stack Overflow](www.https://stackoverflow.com) - This site speaks for itself, you will usually find an answer for a question you have; and if not, you can ask it and someone will probably answer it for you. Brilliant community!
