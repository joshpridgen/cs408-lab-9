# CS408 - Lab9.2

## Overview

This project is a simple interactive game where colorful balls bounce around the screen. The player controls an "Evil Circle" that can eliminate the balls by colliding with them. The game keeps track of the number of balls remaining on the screen and displays this count in real-time. The objective is to eliminate all the balls using the Evil Circle.

## How to play

I made two versions that you can play! If you find the commented code in `main.js`, you can switch between the keyboard and mouse control versions of the Evil Circle.

### Keyboard Control Version

1. Open `main.js`.
2. Find the commented code block under the `EvilCircle` class constructor.
3. Uncomment the lines that handle the keyboard events (`window.addEventListener('keydown', ...)`).
4. Comment out or remove the `window.addEventListener('mousemove', ...)` line.

### Mouse Control Version

1. Open `main.js`.
2. Find the commented code block under the `EvilCircle` class constructor.
3. Ensure the `window.addEventListener('mousemove', ...)` line is uncommented.
4. Comment out or remove the lines that handle the keyboard events (`window.addEventListener('keydown', ...)`).

## Sources and Credits

- [MDN Web Docs - Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
- [MDN Web Docs - Math.random()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random)
- [JavaScript.info - Animation](https://javascript.info/animation)
- [Eloquent JavaScript - Drawing on Canvas](https://eloquentjavascript.net/17_canvas.html)
- [HTML5 Rocks - High Performance Animations](http://www.html5rocks.com/en/tutorials/speed/high-performance-animations/)
- [Stack Overflow - How to draw a circle with HTML5 canvas?](https://stackoverflow.com/questions/1255512/how-to-draw-a-circle-with-html5-canvas)
- [Stack Overflow - How to detect collision in JavaScript?](https://stackoverflow.com/questions/2459298/how-to-detect-collision-in-javascript)
- [Stack Overflow - How to move an object with arrow keys in JavaScript?](https://stackoverflow.com/questions/5597060/detecting-arrow-key-presses-in-javascript)
- [Stack Overflow - How to make an object follow the mouse in JavaScript?](https://stackoverflow.com/questions/7790725/javascript-track-mouse-position)