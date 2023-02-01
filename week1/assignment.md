# assingment 1 - random walk

The random walk assignment reminded me a lot of maze generation algorithms. Last year I read [Vizualizing Algorithms](https://bost.ocks.org/mike/algorithms/) by Mike Bostock and in this paper he visualized multiple different maze generation algorithms, which I thought were super interesting. There is a "random walk" visualization which uses Wilson’s algorithm and loop-erased random walks to generate a uniform spanning tree. It can take a really long time the the maze to be fully generated with this algorithm, but it's pretty coool to watch. 

<p>&nbsp;</p>

When I was thinking about what kind of random walk I wanted to create for this weeks assingment I orignally thought I would like to create a random walk like the one vizualized by Wilson's Algorithm or the [Coding Train Self Avoidng Walk](https://thecodingtrain.com/challenges/162-self-avoiding-walk). But after watching the video and looking at the code, I figured I should maybe start with a more simple version of a random walk and work my way up.

<p>&nbsp;</p>
The first random walker is a simple walker that uses a walker class to walk from the center of the canvas. 

<p>&nbsp;</p>

[random walker 1](https://editor.p5js.org/gracywhelihan/sketches/eVCv9CQkX)

<img width="401" alt="Screen Shot 2023-01-29 at 3 14 26 PM" src="https://user-images.githubusercontent.com/76453899/216093705-793dc323-f910-45db-a7d1-9c5764116192.png">

<p>&nbsp;</p>
The Second random walker is my attemped at creating a maze generator. Like Bostocks visualization of Wilson's algorithm, the random walker spreads out across the canvas. When the walker runs into itself (back to a path it has already taken) it turns white. While it is "exploring new territory, it is red. Unlike a maze generator, this turns out to make a full grid. 

<p>&nbsp;</p>
[random walker 2](https://editor.p5js.org/gracywhelihan/sketches/gEWERp0sP)
<img width="400" alt="Screen Shot 2023-01-30 at 4 12 03 PM" src="https://user-images.githubusercontent.com/76453899/216093658-a79501d7-edbf-4ff1-b35b-04628f3b5d61.png">
<img width="400" alt="Screen Shot 2023-01-31 at 8 56 01 AM" src="https://user-images.githubusercontent.com/76453899/216093670-a67ee0de-1b68-4ae5-84ca-4e4b0dc1f7a3.png">
