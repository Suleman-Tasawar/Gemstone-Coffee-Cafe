# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- The users should click on the hamburger menu to see the navigation when on a small screen

### Screenshot

![ScreenShots of The Website in PC](Screenshots/screenShot(2).png>)
![ScreenShots of The Website in Mobile](Screenshots/screenShot(1).png>)

### Links

- Solution URL: [Link to the Github Repo of the Solution](https://github.com/Suleman-Tasawar/Gemstone-Coffee-Cafe)
- Live Site URL: [Link to the Live Site](https://suleman-tasawar.github.io/Gemstone-Coffee-Cafe/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

During working on this project i have learned so many things in a practical way.
I will mention a few of them
First i leaned how to create a hamburger menu on how it will display on small screens
Secondly i learned how to position text over an images in top and at center

```html
<div id="hamburger">
  <span class="lines"></span>
  <span class="lines"></span>
  <span class="lines"></span>
</div>
```

```css
#hamburger {
  display: none;
  z-index: 1;
  width: 40px;
  height: 40px;
}

.lines {
  display: block;
  width: 30px;
  height: 3px;
  margin: 5px;
  background-color: white;
  color: #fafafa;
}

.home-content {
  position: absolute;
  width: 350px;
  color: #fafafa;
  top: 25%;
  left: 15%;
}
```

```js
let ham = document.querySelector("#hamburger");
    let menu = document.querySelector(".nav");
    ham.addEventListener("click", () => {
      menu.classList.toggle("open");
      ham.classList.toggle("close");
    });
};
```

### Continued development

Note that i am still working on this Project this isnt a finished version of the Project.I still have a lot of things to add to this Website and alot of thing to optimize

## Author

- Website - [Suleman Tasawar](https://suleman-tasawar-portfolio.on.drv.tw/pages/)
