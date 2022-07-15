# Welcome! 👋

This is a solution to the challenge [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62)
of a preview stats card made to test my knowledge in `html` and `css`.
## Table of contents

- [Overview](#Overview)
  - [The challenge](#The-challenge)
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

- View the optimal layout depending on their device's screen size

### Screenshot

![gif of template](./design/ezgif.com-gif-maker.gif)

### Links

- [solution URL](https://github.com/MarcoFranca/challege-status-preview)
- [live site URL](https://marcofranca.github.io/challege-status-preview/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- desktop-first workflow

### What I learned

I reinforced the concepts of html `semantic tags` and `lists`

```html
<div class="card--text">
  <h1 class="title">Get <span>insights</span> that help your business grow.</h1>

  <p class="text">Discover the benefits of data analytics and make better decisions regarding revenue, customer
    experience, and overall efficiency.</p>
</div>
<div class="card--skill">
  <ul>
    <li class="skill--title">10k+</li>
    <li class="text skill--text">COMPANIES</li>
  </ul>
```
I reinforced my CSS knowledge in `flex-box` , `overflow`, `border radios`, `width` and `height`.
```css
.container{
  width: 100vw;
  height: 100vh;
  background-color: hsl(233, 47%, 7%);
  display: flex;
  justify-content: center;
  align-items: center;
}

.card{
  background-color: hsl(244, 38%, 16%);
  border-radius: 5px;
  height: 70%;
  width: 80%;
  display: flex;
  overflow: hidden;
}
```

### Continued development

I will dedicate myself to future projects using javascript concepts along with html and css which I am studying and improving myself


## Author

- Linkdin - [Marco Tullio Franca](https://www.linkedin.com/in/marco-franca/)
- Frontend Mentor - [@MarcoFranca](https://www.frontendmentor.io/profile/MarcoFranca)

