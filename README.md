# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](images/screenshotDesktop.jpg)
![](images/screenshotMobile.jpg)

### Links

- Solution URL: ()
- Live Site URL: ()

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

```html
<main class="single-price-grid">
  <article class="single-price-website grid-col-span-2 article1">
    <h1>Join our community</h1>
    <h2>30-day, hassle-free money back guarantee</h2>
    <p>
      Gain access to our full library of tutorials along with expert code
      reviews. Perfect for any developers who are serious about honing their
      skills.
    </p>
  </article>
</main>
```

```css
/** Single Price Grid Styling **/

.grid-col-span-2 {
  grid-column: span 2;
}

.single-price-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  width: min(100%, 50rem);
  box-shadow: 0 0 25px -1px #888888;
  border-radius: 1rem;
}
```

### Continued development

I'm still not completely comfortable with and grid techniques.

### Useful resources

- (https://www.youtube.com/watch?v=rg7Fvvl3taU&list=PLZU50vs_8cjqQDfb2VLOynFY8vsu71FMT&index=2&t=1525s)
  This helped me with styling CSS Grid.
- (https://www.youtube.com/watch?v=9zBsdzdE4sM&list=PLZU50vs_8cjqQDfb2VLOynFY8vsu71FMT&index=4&t=928s)
  This helped me to understand structure of CSS Grid.

## Author

- Website - (https://doradada.github.io/cv/)
- Frontend Mentor - [@DorotaMroz](https://www.frontendmentor.io/profile/DorotaMroz)
