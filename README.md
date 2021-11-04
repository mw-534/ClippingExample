# ClippingExample

Example App that demonstrates clipping of drawables to reduce graphical overhead and create some effects.
Also demonstrates the use of
canvas.save(), canvas.translate() and canvas.restore() 
to move the canvas - the local coordinate system - in order to draw elements to different regions of the screen. 
This is easier and more efficient than having to calculate offsets to x and y for each element that should be rendered.

Based on a lesson of the Udacity course Advanced Android with Kotlin
