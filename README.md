# GPUSandbox
An exploration of GPU processing

Published on [GitHub Pages](http://kyleheadley.github.io/GPUSandbox/)

This is a 'game' I made for a class project. Each commit so far has been an interesting change of visuals or mechanics.

The current project direction is to build some kind of abstract art generator. Use mouse to draw, keyboard keys change mode.

The main technical interest here is that I'm doing all the main computation on the GPU. The script sends mouse commands to be drawn, then the whole image is processed to create the next image. Processing is done by fragment shader from one texture to another. 
