# p5.js
# Learning p5.js with Tutplus


#### Source
https://code.tutsplus.com/courses/how-to-program-interactive-art-with-p5js

### Basics
* Create a directory
* Create an index.html
* Delete the 8 pixels border
* Summon p5.js
* Create a sketch and console.log
* Review in browser if console prints

### Functions
1. Setup
For specifying the size of your canvas, background color, that sort of thing.

* You just have to call it, it comes with p5
* Try it with console.log!

2. Draw function

* Same as Setup.
* It will start looping if you console.log it after setup. As fast as it can

	Start drawing!
* To delete the scroll bars ->     

``` 
canvas {
        display: block;
      }
``` 

* Setup
 `createCanvas(600,200);`

or

  `createCanvas(window.innerWidth, window.innerHeight);`

* Setup
  `background('#CC0000');`

* Draw
``` 
  ellipse(50,50,300,250);
  ellipse(position w, position h, width,  height);

  stroke('white');
  fill('purple');

``` 



 
 
