# Vectors

I will say that I think irl vector math makes a lot of sense, but when I am adding velocity and acceleration in p5 I really have to think about it. But it is very cool to be able to make vectors because I am starting to see the power and flexablity they give you within your sketch. 
I started off just seeing if I could create some vectors and make them move randomly around that canvas. When creating a vector for each object like this.pos = createVector(random(-1, 1), random(-5,5)) all of my objects would fly off in different directions. Which was cool, so I then thought I would change the objects to be lines. This really made me think of the Matrix. 
I added in a Ones class and a Zeros class and then applied the velocity to each array of objects. This didn't give me quite the look I was going for because all of the ones and zeros flew off and there was no stopping them. 
[the matrix vectors](https://editor.p5js.org/gracywhelihan/sketches/MNwnTH2os)

<img width="529" alt="Screen Shot 2023-02-08 at 10 54 19 PM" src="https://user-images.githubusercontent.com/76453899/217714233-d386d0d1-ba52-490f-b61d-4da7f276e9f8.png">

To make the ones and zeros look more like the matrix I changed the velocity vector to be this.vel = createVector(0, random(-5, 5). I then thought it would be nice to add a little smiley face that was floating around in the matrix that accelerates towards the mouse. 
[emotional in the matrix](https://editor.p5js.org/gracywhelihan/sketches/L0PHLwwpY)

<img width="568" alt="Screen Shot 2023-02-08 at 10 43 55 PM" src="https://user-images.githubusercontent.com/76453899/217714792-9dcbeb0d-d800-438e-b529-4ffd5b2292ef.png">

I did notice that the smiley accelerates towards the mouse, but when the mouse goes off the canvas it gets stuck bouncing on the edge. I am not really sure why that is happening. I didn't put any constraints to keep the smiley on the canvas, but there some be somthing in my code to have it chillin there?

<img width="568" alt="Screen Shot 2023-02-08 at 11 04 15 PM" src="https://user-images.githubusercontent.com/76453899/217715169-ed177c43-6d14-49ce-a175-5b27e9a2d230.png">

<br></br>
I think it would be cute to add some more smiley faces that could bump into each other and maybe some hearts to fly off of them when they bump into each other. I feel like there are some many possiblities here and because I am still trying to understand exactly how changing each vector effects the whole behavior of the object I want to try a bunch of things out. 
