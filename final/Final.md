#Final - little guy game

[code](https://glitch.com/edit/#!/outgoing-kaput-toast?path=public%2Fsketch.js%3A127%3A13)
[play](https://outgoing-kaput-toast.glitch.me/) (on mobile only!)

To be honest, I was not able to get as far with this project as I wanted to. I ran into some trouble technically, and with all of the things I needed to get done with thesis, I didn't have as much time to work on it as I would have liked to. But, I do think it turned out okay :)

The idea is that when you tilt your phone to be more verticle the gravitational force will be be applied to the little guys. And tilting your phone from left to right will apply a wind force.

I originally wanted to use [p5play](https://p5play.org/) to help me with collisions with irregular shapes, but I found the the p5play library blocked the device orientation permission, which I needed becasue the forces acting on the little guy are based off of the oreintation of the users phone. So that wasted a bit of time, and if I were smart I would have realized that I could have tried using matter.js, but I didn't do that. I decided to just track the collisions on my own. To do this I limited the shapes I used to be circles so it was easy to detect. The small rectangles at the top are actually 4 circles in a row. This was a little bit of a bummer becasuse I wanted to add more complex shapes, but that is something I can do in the future. 

![IMG_4257](https://github.com/gracywhelihan/Nature-of-Code/assets/76453899/0f74da5e-f187-44f6-86fb-4251c6040f5b)


 Another thing I wanted to do was add sockets into the sketch so that multiple people could be on the same screen getting their little guys down to the bottom of the screen. I ended up not doing this becasue with all of my other collision detection, I noticed that the sketch was getting really laggy. I was having some trouble with the spinner class. I tried to use inheritance (like Spinner extends Pole) but was having trouble getting the detection to work with that. And it was proably because my brain was total mush at this point. So I just made it another class (which I know is not the best practice :| ). So maybe this is why the sketch is lagging. Either way, after showing it in class Dan said that there is probs something in the code that is causing that. Which is great because that means I can fix it and make it smoother! 
 
(link to video example)[https://vimeo.com/826276849?share=copy]
 
 I also wanted to make the little guy into a soft body character, but I really just ran out of time. I think this would be a really fun project to continue with and I thing maybe combining it with my simulation project and having it be longer and the screen could scroll in different directions as he goes along. So I def want to keep working on it. 
 
 Thank you!!
