# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

This is a simple recipe page which includes ingredients, instructions and nutrition.

### Screenshot

![](./Solution%20Screenshot.png)

### Links

- Solution URL: [Add solution URL here](http://127.0.0.1:3000/Basics-HTML&CSS/Recipe%20page/recipe-page-main/index.html)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Styled Components](https://fonts.google.com/) - For Typography styles

### What I learned

This project is mostly about the correct usage of margins and paddings. I have learnt a new way of changing the color of list elements bullets with ChatGPT, and also how to concise my CSS code. Moreover, I have also made my website responsive from the small screens to large 4k screens.

```html
<h1>Some HTML code I'm proud of</h1>
<ol class="list order">
<strong>Total: </strong>
<article>
          <p class="nutrient">Calories</p>
          <p class="calories">277kcal</p>
</article>
```
```css
#preparation li:last-child { padding-bottom: 0; }
.prepare-list-style li::marker { color: hsl(332, 51%, 32%); }
.order {
    list-style: none; counter-reset: step;
}
.order li::before {
    content: counter(step) ". "; font-weight: bold;
}
```

### Continued development

I want to continue focusing on the correct usage of padding and margin properties because I think this is where I spend more time on it. Furthermore, I want to learn more about how I can concise my CSS codes.

## Author

- GitHub - [Biru Basfore](https://github.com/BiruMJ)
- Frontend Mentor - [@BiruMJ](https://www.frontendmentor.io/profile/BiruMJ)
- LinkedIn - [@biru-basfore-8b52262a4](www.linkedin.com/in/biru-basfore-8b52262a4)

## Acknowledgments

I use ChatGPT and Copilot whenever I feel I am stucked. Also, I view some related websites for inspiration and make my coding more good.
