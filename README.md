# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

### Screenshot

![Desktop - version](./assets/images/desktop_solution.png)
![Desktop - version](./assets/images/desktop_solution2.png)
![Desktop - version](./assets/images/desktop_solution3.png)
![Desktop - version](./assets/images/desktop_solution4.png)

### Links

- Solution URL: [(https://github.com/ElijahOluwasegun/recipe-page-coding-challenge)]
- Live Site URL: [(https://elijaholuwasegun.github.io/recipe-page-coding-challenge/)]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Media Queries

### What I learned

During this project, I learned how to use multiple classes on a single HTML element, as shown below:

```html
<ul class="list meal-ingredients"></ul>
<ol class="list meal-instructions"></ol>
```

```css
.list {
  padding: 0.625em 1.563em;
}

.list li {
  padding: 0.625em 1.25em;
  color: hsl(30, 10%, 34%);
}

ul.meal-ingredients li::marker {
  color: hsl(14, 45%, 36%);
}

ol.meal-instructions li::marker {
  color: hsl(14, 45%, 36%);
}
```

I also explored the nth-child selector for styling specific table columns:

```css
td:nth-child(1) {
  font-weight: normal;
  color: hsl(24, 5%, 18%);
}

td:nth-child(2) {
  color: hsl(14, 45%, 36%);
  font-weight: 600;
}
```

### Continued development

I want to improve my understanding of HTML and CSS table properties, as they were challenging to work with in this project. Additionally, I aim to enhance my skills in writing effective media queries for better mobile responsiveness.

### Useful resources

- [MDN](https://developer.mozilla.org/en-US/) - This helped me to create the table for nutritional values.
- [W3schools](https://www.w3schools.com/) - This is an amazing website which helped me to change the color of the list bullets and to make my website responsive. I'd recommend it to anyone beginning their web journey.
- [Geeks for geeks](https://www.geeksforgeeks.org/) - This is an amazing website which helped me to apply borders within the table cells for nutritional values.
- [Neko Calc](https://nekocalc.com/) - An valuable resource that supported me to make my solution responsive. I really liked the simplicity in using the website and recommend it to anyone trying to convert pixel or other values to a required format.
- [CSS Unit Converter](https://cssunitconverter.vercel.app/) - A valuable resources that supported me in converting css units.

## Author

- Frontend Mentor - [@ElijahOluwasegun](https://www.frontendmentor.io/profile/ElijahOluwasegun)

## Acknowledgments

I would like to acknowledge [@ajasmine94](https://www.frontendmentor.io/profile/ajasmine94) from Frontend Mentor with the knowledge of centering elements in a page.
