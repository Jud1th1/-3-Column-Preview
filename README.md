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

This challenge involved me building out this 3-column preview card component and getting it to look as close to the design as possible.
I designed for a responsive mobile and desktop look. 

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot
   <img src="images/Dev Screenshots.png">
    <img src="images/Dev Screenshots (1).png">

### Links

- Solution URL: https://github.com/Jud1th1/-3-Column-Preview
- Live Site URL: https://cheerful-shortbread-bd3083.netlify.app/

## My process

- I worked this through by following along with a YouTube tutorial from TSbSankara. I would make the attempt first and then compare his process to mine. 
- To begin with I created an external stylesheet and moved the contents of the internal stylesheet over. I formatted my html with the appropriate semantic elements and class names. I then added the icon images to the html and uploaded my Google fonts provided by the style sheet. In CSS I added the primary colors to my root element for easy access and then set up font sizes, colors, etc. Once it closely matched the original design I added the button and padding, fonts, colors and hover states for each button. I added some padding to the container and each section until I was happy with the end result. Then I used the media query to translate my mobile code for desktop view. I knew a flex box was needed here however I could not get my container to center on the page. I also had to adjust my border radius placements to be on the outer corners of the container since they shifted into the wrong place. 


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Tutorial used: https://www.youtube.com/watch?v=2Wy_MJPDfCw 


### What I learned

- Prior to starting I watched some recommended videos on when to use which CSS units: 
  https://www.youtube.com/watch?v=N5wpD9Ov_To
  And I even found a helpful convertor on W3Schools to assist me along the way
  https://www.w3schools.com/cssref/css_pxtoemconversion.php
- Besides that practicing my hand at mobile design first to desktop and using flexbox  seemed easier this time around. 



 CSS code that I am proud of (Adding an ease transition to my button): 
```css
button{
    font-family: "Lexend Deca", sans-serif;
    color: hsl(0, 0%, 95%);
    border: 2px solid hsl(0, 0%, 95%);
    border-radius: 2em;
    padding: 10px 20px;
    transition: all 0.4s ease-in-out;
}
```


### Continued development

- More practice with flexbox would be useful since it did not display how I was hoping in the end. https://flexboxfroggy.com/



