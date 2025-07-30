# Article Listing Page | devChallenges

<div align="center">
   Solution for a challenge <a href="https://devchallenges.io/challenge/article-listing-challenge" target="_blank">Article Listing</a> from <a href="http://devchallenges.io" target="_blank">devChallenges.io</a>.
</div>

<div align="center">
  <h3>
    <a href="#">
      Demo
    </a>
    <span> | </span>
    <a href="https://devchallenges.io/challenge/article-listing-challenge">
      Challenge
    </a>
  </h3>
</div>

## Table of Contents

- [Overview](#overview)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Built with](#built-with)
- [Features](#features)
- [Acknowledgements](#acknowledgements)
- [Author](#author)

## Overview

![screenshot](./assets/resources/thumbnail.jpg)

A clean article listing page that doesn't suck to browse through. You know those blog homepages where everything looks cramped and messy? This is the opposite of that.

The challenge was straightforward: make a responsive grid of articles with flexbox. Turns out organizing content so it actually looks good is harder than expected, but flexbox makes it way less painful once you get it.

### What I learned

- **Flexbox stopped being confusing**: After building this layout, `justify-content` and `align-items` actually make sense now. No more guessing which property does what.

- **Article elements matter**: Using proper `<article>` tags instead of random divs makes the HTML way cleaner and more meaningful. Each article feels like its own thing.

- **Typography is everything**: Getting the title sizes and date styling right took forever, but it's what makes content readable instead of a wall of text.

- **Images are annoying**: Making different sized images play nice in a flexible grid was a pain. `object-fit` became my best friend.

- **Spacing fixes everything**: The difference between looking amateur and professional is usually just consistent margins and padding.

### Useful resources

- [CSS-Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Finally made flexbox click for me
- [MDN Article Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/article) - When to actually use article tags
- [Smashing Magazine Flexbox](https://www.smashingmagazine.com/2016/11/css-grids-flexbox-and-box-alignment-our-new-system-for-web-layout/) - Real examples that actually work

## Built with

- HTML5 with semantic article elements
- CSS3 flexbox layouts
- Responsive design
- Custom CSS properties
- Mobile-first approach

## Features

- **Clean article structure**: Each article has its image, title, and date properly organized with semantic HTML.

- **Consistent image sizing**: All images look good regardless of their original dimensions.

- **Readable typography**: Title hierarchy and date styling that doesn't hurt your eyes.

Built for a [DevChallenges](https://devchallenges.io/challenges-dashboard) challenge that turned out to be a great flexbox crash course.

## Acknowledgements

- [DevChallenges.io](https://devchallenges.io/) for challenges that teach useful stuff
- [CSS-Tricks](https://css-tricks.com/) for making CSS actually understandable 

## Author

- Website [Simple_Articles](#)
- GitHub [@gvillarroel-dev](https://github.com/gvillarroel-dev)