# snap-frontend-mentor
# Frontend Mentor - Intro section with dropdown navigation solution

This is a solution to the [Intro section with dropdown navigation challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/intro-section-with-dropdown-navigation-ryaPetHE5). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the relevant dropdown menus on desktop and mobile when interacting with the navigation links
- View the optimal layout for the content depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution/Live site URL: [Add solution URL here][(https://your-solution-url.com)](https://mandilem.github.io/snap-frontend-mentor/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Bootstrap
- Flexbox

### What I learned

This was my first bootstrap build with no guidance, and it was quite challenging. I learned that keeping code clean is quite hard but very necessary. I learned that sometimes, regular 'ol flexbox is better than the almight Bootstrap grid. That said, Bootstrap was incredibly helpful, especially for the dropdown and mobile menu.

Here's some HTML I'm proud of. I decided to use a 7/5 .col ratio instead of the 6/6 which helped with the spacing and image sizing. I also use the .img-fluid Bootstrap class to make sure the image scaled with the parent.

```html
<section id="hero-section">
    <div class="row align-items-center">
      <div class="col-lg-7 hero-left align-self-end">
        <h1 class="mb-4">Make remote work</h1>
        <p class="mb-5">
          Get your team in sync, no matter your location. Streamline processes,
          create team rituals, and watch productivity soar.
        </p>
        <button type="button" class="btn btn-outline-dark btn-lg hero-button">Learn More</button>
        <div class="clients">
          <img src="images/client-databiz.svg" class="pe-4 client-logo" alt="databiz logo" />
          <img src="images/client-audiophile.svg" class="pe-4 client-logo" alt="audiophile logo" />
          <img src="images/client-meet.svg" class="pe-4 client-logo" alt="meet logo" />
          <img src="images/client-maker.svg" class="client-logo" alt="maker logo" />
        </div>
      </div>
      <div class="col-lg-5">
        <img src="images/image-hero-desktop.png" class="img-fluid hero-img" alt="Geometric shapes" />
      </div>
    </div>
  </section>
```

### Continued development

I defintely need to build out more sites like this one. It was challenging, but allowed me to stretch myself. I want to learn more about the combination of Bootstrap classes and regular CSS styling, because my code wasn't as readable as I would've liked.

## Author

- Website - Mandile (https://mandiledesign.webflow.io/)

## Acknowledgments

I'm currently going through this awesome course on Udemy https://www.udemy.com/course/the-complete-web-development-bootcamp/. I took a break after HTML, CSS, and Bootstrap to practice what I'd learned (which is why this project exists).
