# Awesome CSS Variables [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

Making a list of awesome CSS Variable resources and libraries (and dashing it twice!)

## Table of Contents

- [Guides](#guides)
- [Talks](#talks)
- [Demos](#demos)
- [Animation Engines](#animation-engines)
- [CSS (Processors)](#css-processors)
- [HTML Processing](#html-processing)
- [Scrolling](#scrolling)
- [SVG](#svg)

## Guides

### Getting Started

* **[A Strategy Guide To CSS Custom Properties](https://www.smashingmagazine.com/2018/05/css-custom-properties-strategy-guide)** – This article outlines the basics of using CSS Variables by comparing them to variables found in pre-processors such as Sass – by [Michael Riethmuller](https://www.smashingmagazine.com/author/michaelriethmuller/)
* **[CSS Custom Properties and Theming](https://css-tricks.com/css-custom-properties-theming/ )** – This post shows how CSS Variables can be used to dynamically theme websites.  This is a common problem when "white labeling" digital content – by [Chris Coyier](https://twitter.com/chriscoyier)
* **[Using CSS custom properties (variables)](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables)** – This is the definitive guide for getting started with CSS Variables. Like most of their other content, MDN continues to be the best place to learn in depth how web technology works short of reading the actual specifications.
* **[Learn CSS Variables for free](https://scrimba.com/playlist/ppYrcJ)** – This free video series takes the viewer through the basics of CSS Variables, how to use them in theming, and how to change them through JavaScript – by [Per Harald Borgen](https://twitter.com/perborgen)
* **[Individualizing CSS Properties with CSS Variables](https://danielcwilson.com/blog/2017/04/individualized-properties/)** – This article is an exploration of using CSS Variables in different CSS Properties such as animation-play-state, transforms, and in color channels. As usual, a great and thoughtful read – by [Dan C Wilson](https://twitter.com/dancwilson) 

### Theming

* **[CSS Custom Properties and Theming](https://css-tricks.com/css-custom-properties-theming/ )** – This post shows how CSS Variables can be used to dynamically theme websites.  This is a common problem when "white labeling" digital content – by [Chris Coyier](https://twitter.com/chriscoyier)

### Positioning

* **[Making Custom Properties (CSS Variables) More Dynamic](https://css-tricks.com/making-custom-properties-css-variables-dynamic)** – This article explains how changing CSS Variables' values using JavaScript and using CSS inheritence can result in very dynamic webpages – by [Dan C Wilson](https://twitter.com/dancwilson)

## Talks
* **[CSS Variables: var(--subtitle)](https://www.youtube.com/watch?v=kZOJCVvyF-4)** – This talk from CSSConf.Asia 2016 shows a variety of ways to use CSS Variables as well as well as a deep dive into the syntax – by [Lea Verou](https://twitter.com/LeaVerou)
* **[Interactive Web Apps with CSS Variables](https://youtu.be/D8PiSK35zjc)** – This meetup talk from September 2018 shows advanced CSS Variable techniques and how to use them – by [Christopher Wallis](https://twitter.com/notoriousb1t) 

## Demos

* **[Easy Theming w/ the Color Picker (CodePen)](https://codepen.io/bloqhead/pen/rJpMXR)** – Tick the color you want to change the theme. The theme color switching is controlled via JS and simply changes a root CSS Variable's hex value – by [Daryn St. Pierre](https://codepen.io/bloqhead)
* **[CSS Vars – A Collection by Shaw (CodePen Collection)](https://codepen.io/collection/AapJoR/)** – A collection of pens using CSS Variables – by [Stephen Shaw](https://codepen.io/shshaw)
* **[Megaman READY! (CodePen)](https://codepen.io/notoriousb1t/pen/vroZox)** – Reproduces the famous "READY" from the Megaman games without using JavaScript.  This uses CSS Grid extensively and CSS Variables for timing and changing the end point of the exploding blocks – by [Christopher Wallis](https://github.com/notoriousb1t)
* **[Splitting: CSS vars for split words & chars (CodePen)](https://codepen.io/shshaw)** – Examples of text effects built with Splitting: https://splitting.js.org.  These animations/transitions are all done with CSS after Splitting adds helper spans & CSS Variables – by [Stephen Shaw](https://codepen.io/shshaw/pen/XVjKrG)
* **[The Charmeleon from Null Island (CodePen)](https://codepen.io/airnan/pen/gvBMPV)** – This endangered chameleon species is usually spotted in the dense forests of Null Island. With special abilities like camouflaging to background colors and reacting to DOM hovers, it has an appetite for Defaultae Pointericus insects. Experimenting with the new lottie-api, CSS Variables and cursor possibilities – by [Hernan Torrisi](https://codepen.io/airnan/)
* **[Custom properties – A collection by Goiblas (CodePen Collection)](https://codepen.io/collection/XKqNPE/)** – A collection with examples of use – by [Jesús Olazagoitia](https://codepen.io/goiblas/)

## Animation Engines

* **[Flipping](https://github.com/davidkpiano/flipping)** – A library (and collection of adapters) for implementing FLIP transitions.  It has multiple strategies for completing FLIP transitions.  The CSS adapter supports using CSS Variables – by [David Khourshid](https://github.com/davidkpiano)
* **[GSAP](https://greensock.com/gsap)** – "Ultra high-performance, professional-grade animation for the modern web."   Among animation engines, the team claims it to be the fastest and the most backward compatible – by [Greensock](https://github.com/greensock)
* **[Just Animate ](https://just-animate.github.io/)** – A general animation engine that uses the Web Animation API for style based animation and has its own animation engine with an extensible plugin system for animating SVG, CSS variables, etc – by [Christopher Wallis](https://github.com/notoriousb1t)


## CSS (Processors)

* **[CSSPlus](https://csspl.us/)** – A family of CSS reprocessing plugins that give you more power when writing CSS. It's called “CSSplus” because it's CSS plus JavaScript, the method most of these plugins use to add power to CSS is by having JavaScript dynamically update CSS variables with information about the browser and elements – by [Tom Hodgins](https://github.com/tomhodgins)

## HTML Processing

* **[Splitting](https://splitting.js.org)** – A JavaScript microlibrary designed to split (section off) an element in a variety of ways, such as words, characters, child nodes, and more! Most Splitting methods utilize a series of <span>s populated with CSS variables and data attributes unlocking transitions and animations that were previously not feasible with CSS – [Stephen Shaw](https://github.com/shshaw)

## Scrolling

* **[BasicScroll](https://basicscroll.electerious.com)** – Standalone parallax scrolling for mobile and desktop with CSS variables. basicScroll allows you to change CSS variables depending on the scroll position. Use the variables directly in your CSS to animate whatever you want. Highly inspired by skrollr and Reactive Animations with CSS Variables – by [Tobias Reich](https://github.com/electerious)
* **[ScrollOut](https://scroll-out.github.io)** – Install ScrollOut and decorate elements with the data-scroll attribute. As elements become visible, data-scroll will be set to in and when elements are scrolled out they will be set with out. Add your own CSS or JS to make a big impression when things come into view. That's it! Use the `cssProps` to animate based on scroll position and to do parallax – by [Christopher Wallis](https://github.com/notoriousb1t)

## SVG

* **[Lengthy](https://github.com/shshaw/lengthy-svg)** – A JavaScript microlibrary (1.2kb min, 0.7kb gzipped) to get the length of SVG shapes. The length will automatically be added to the element as a CSS Var to make it easy to do CSS animations of SVG stroke-dashoffset for the wonderful line drawing SVG technique and other interesting animations – [Stephen Shaw](https://github.com/shshaw)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Christopher Wallis](https://twitter.com/notoriousb1t) has waived all copyright and related or neighboring rights to this work.
