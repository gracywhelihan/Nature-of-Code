# Soft Bodies


[sketch](https://editor.p5js.org/gracywhelihan/sketches/piqCtvIbo)

Using the toxiclibs.js library I started off by creating a chain of springs - which let me to want to try to create an actual chain. This turned out to acutally be a really hard for me. I wanted to use ellipses instead of circles so that it looked more like a chain in real life, but then I noticed that I would need to apply a rotation to ellipses to have them stay connected from top to bottom. Using the [seek a target](https://www.youtube.com/watch?v=p1Ws1ZhG36g&ab_channel=TheCodingTrain) coding train example, I tried to have each spring rotate by the heading of the velocity, but it still didn't look the way I wanted it to. I also tried to have the springs rotate by the heading of the velocity of the particle in front of them, but it did not give me the result I was looking for. Finally I just decided to make a custom shape for the chain links (springs) becasue I knew the lines would turn the way I wanted them to. 

After all of that chain building I had come up with an idea for what to do with the chain... make a Flail. My friends have recently gotten into forging metal and actually made a flail with a basketball on the end of it instead of a spikey ball. So I thought I would make one for them with my chain on p5.

The next issue I ran into was getting the flail to move in the y direction with the mouse. This is probably becasue of the way I drew it - with the x and y at the top left of the rectangle. So, for now it only moves in the x direction. 

I also wanted to make the basketball into a soft body and I started off using the [force directed graph](https://editor.p5js.org/natureofcode/sketches/_tbPaFqVX) example. But I kind of ran out of time so I wasn't able to figure out how to attach it to the chain and to draw the basketball over the top of the structure. But that would be a good next step! Also, it would be great to add some collision detection and more forces into the sketch. Maybe some things for the basketball to hi too.
