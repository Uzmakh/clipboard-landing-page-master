# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

### The challenge

Set the layout of the page.
Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

- Completed the semantic markup structure of the page.
- Set the style.css according to style-guide.md
  . set the color-theme in root selector
  . set the html font-size to 18px
  . import the google-fonts link for the Bai+Jamjuree font for weights 400-regular and 600-semibold
  . used fontawesome link in html-head for font-icons(No use of fontawesome icon library as all icons are given in images in svg form in images folder.)
  .reset the browser-default css
  .set the utility classes for section, container, buttons for spacing and font-sizes.
  .and set the hover states of the buttons
  . used flexbox for the layout
  .used media queries for mobile screen.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

This webpage layout is the good practice source for basic tech like semantic tags of markup,css custom properties and flexbox properties. Moreover the use of media queries for responsiveness is the additional learning piece in this project.

### Continued development

(Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.)

I faced a little bit problem in creating footer-links layout.So I arranged them in divs to have three columns. (I could either use grid properties. I my try them also. )

 <div class="footer-links">
          <div>
            <ul>
              <li><a href="#">FAQs</a></li>
              <li><a href="#">Contact Us</a></li>
            </ul>
          </div>
          <div>
            <ul>
              <li><a href="#">Privacy Policy</a></li>
              <li><a href="#">Press Kit</a></li>
            </ul>
          </div>
          <div>
            <ul>
              <li><a href="#">Install Guide</a></li>
            </ul>
          </div>
        </div>
      </div>

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)
