# Awesome CSS Variables [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

Making a list of awesome CSS Variable resources and libraries (and dashing it twice!)

## Table of Contents

- [Guides](#guides)
- [Demos](#demos)
- [Animation Engines](#animation-engines)
- [CSS (Processors)](#css-processors)
- [HTML Processing](#html-processing)
- [Scrolling](#scrolling)
- [SVG](#svg)

## Guides

### Getting Started

#### A Strategy Guide To CSS Custom Properties
* https://www.smashingmagazine.com/2018/05/css-custom-properties-strategy-guide/ 

This article outlines the basics of using CSS Variables by comparing them to variables found in pre-processors such as Sass.   

#### CSS Custom Properties and Theming
* https://css-tricks.com/css-custom-properties-theming/ 

This post shows how CSS Variables can be used to dynamically theme websites.  This is a common problem when "white labeling" digital content.

#### Using CSS custom properties (variables)
* https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables 

This is the definitive guide for getting started with CSS Variables. Like most of their other content, MDN continues to be the best place to learn in depth how web technology works short of reading the actual specifications.

#### Learn CSS Variables for free
* https://scrimba.com/playlist/ppYrcJ

This free video series takes the viewer through the basics of CSS Variables, how to use them in theming, and how to change them through JavaScript.

## Demos

### Easy Theming w/ the Color Picker (CodePen)
* https://codepen.io/bloqhead/pen/rJpMXR
* by [@bloqhead](https://codepen.io/bloqhead)

Tick the color you want to change the theme. The theme color switching is controlled via JS and simply changes a root CSS Variable's hex value. 

### Hover Highlight Effect (CodePen)
* https://codepen.io/shshaw/pen/MoxrPV
* by [@shshaw](https://codepen.io/shshaw)

Challenge by @DavidKPiano to recreate this effect: https://twitter.com/SergioPedri/status/885441708820975616.  Uses CSS variables, but still looks great without.

### Megaman READY! (CodePen)
* https://codepen.io/notoriousb1t/pen/vroZox
* by [@notoriousb1t](https://github.com/notoriousb1t)

Reproduces the famous "READY" from the Megaman games without using JavaScript.  This uses CSS Grid extensively and CSS Variables for timing and changing the end point of the exploding blocks

### Splitting: CSS vars for split words & chars (CodePen)
* https://codepen.io/shshaw/pen/XVjKrG
* by [@shshaw](https://codepen.io/shshaw)

Examples of text effects built with Splitting: https://splitting.js.org
These animations/transitions are all done with CSS after Splitting adds helper spans & CSS Variables.

### The Charmeleon from Null Island (CodePen)
* https://codepen.io/airnan/pen/gvBMPV
* by [airnan](https://codepen.io/airnan/)

This endangered chameleon species is usually spotted in the dense forests of Null Island.
With special abilities like camouflaging to background colors and reacting to DOM hovers, it has an appetite for Defaultae Pointericus insects.
Experimenting with the new lottie-api, CSS Variables and cursor possibilities.

## Animation Engines

### Flipping
* https://github.com/davidkpiano/flipping
* by [@davidkpiano](https://github.com/davidkpiano)

A library (and collection of adapters) for implementing FLIP transitions.  It has multiple strategies for completing FLIP transitions.  The CSS adapter supports using CSS Variables.

### GSAP
* https://github.com/greensock/GreenSock-JS 
* https://greensock.com 
* by [@greensock](https://github.com/greensock)

"Ultra high-performance, professional-grade animation for the modern web."  It recently added CSS variables to its arsenal of animation techniques.  Among animation engines, the team claims it to be the fastest and the most backward compatible.

### Just Animate 
* https://github.com/just-animate/just-animate
* https://just-animate.github.io/
* by [@notoriousb1t](https://github.com/notoriousb1t)

A general animation engine that uses the Web Animation API for style based animation and has its own animation engine with an extensible plugin system for animating SVG, CSS variables, etc.

## CSS (Processors)

### CSSPlus
* https://github.com/tomhodgins/cssplus
* https://csspl.us/
* by [@tomhodgins](https://github.com/tomhodgins)
 
CSSplus is a family of CSS reprocessing plugins that give you more power when writing CSS. It's called “CSSplus” because it's CSS plus JavaScript, the method most of these plugins use to add power to CSS is by having JavaScript dynamically update CSS variables with information about the browser and elements.

## HTML Processing

### Splitting 
* https://github.com/shshaw/Splitting
* https://splitting.js.org
* by [@shshaw](https://github.com/shshaw)

Splitting is a JavaScript microlibrary designed to split (section off) an element in a variety of ways, such as words, characters, child nodes, and more!

Most Splitting methods utilize a series of <span>s populated with CSS variables and data attributes unlocking transitions and animations that were previously not feasible with CSS.

## Scrolling

### BasicScroll 
* https://github.com/electerious/basicScroll
* https://basicscroll.electerious.com
* by [@electerious](https://github.com/electerious)

Standalone parallax scrolling for mobile and desktop with CSS variables.

basicScroll allows you to change CSS variables depending on the scroll position. Use the variables directly in your CSS to animate whatever you want. Highly inspired by skrollr and Reactive Animations with CSS Variables.

### ScrollOut 
* https://github.com/scroll-out/scroll-out
* https://scroll-out.github.io
* by [@notoriousb1t](https://github.com/notoriousb1t)

Install ScrollOut and decorate elements with the data-scroll attribute. As elements become visible, data-scroll will be set to in and when elements are scrolled out they will be set with out. Add your own CSS or JS to make a big impression when things come into view. That's it!

Use the `cssProps` to animate based on scroll position and to do parallax.

## SVG

### Lengthy 
* https://github.com/shshaw/lengthy-svg
* by [@shshaw](https://github.com/shshaw)

Lengthy is a JavaScript microlibrary (1.2kb min, 0.7kb gzipped) to get the length of SVG shapes. The length will automatically be added to the element as a CSS Var to make it easy to do CSS animations of SVG stroke-dashoffset for the wonderful line drawing SVG technique and other interesting animations.



## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Christopher Wallis](https://twitter.com/notoriousb1t) has waived all copyright and related or neighboring rights to this work.
