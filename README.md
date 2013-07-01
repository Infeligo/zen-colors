zen-colors
==========

Changing colors screen app

Check out these implementations:

####[Zen Colors (HTML5 Canvas)](http://htmlpreview.github.io/?https://github.com/Infeligo/zen-colors/blob/master/zen-colors-canvas.html)

Fills canvas with color using `window.setInterval` with a small interval

####[Zen Colors (CSS3)](http://htmlpreview.github.io/?https://github.com/Infeligo/zen-colors/blob/master/zen-colors-css.html)

Changes background color of `<div>` using CSS3 transitions

####[Zen Colors (JS)](http://htmlpreview.github.io/?https://github.com/Infeligo/zen-colors/blob/master/zen-colors-javascript.html)

Changes background color of `<div>` using `window.setInterval` with a small interval

####[Zen Colors (JS/RAF)](http://htmlpreview.github.io/?https://github.com/Infeligo/zen-colors/blob/master/zen-colors-javascript-raf.html)

Changes background color of `<div>` using `window.requestAnimationFrame`

Notes: 

1. `window.requestAnimationFrame` is [not supported](http://caniuse.com/#search=requestAnimationFrame) on Android yet (as of 4.2)
2. CSS transition and `window.setInterval` implementations flicker on my HTC One X. Could not test RAF version.
