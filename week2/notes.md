# Vectors
## vectors
vecors --> magnitude/direction
- magnitude - distance
- direction - angle

createVector(4, 3) --> magnitude = 5

<br></br>

## vector math!
How to pick a random direction with a fixed magnitude --> UNIT VECTOR
- v = p5.Vector.random2D() -- unit vector
- v.mult(5) --> gives a vector magnitude of 5

<br></br>
## static functions
random2D() --> static function
Add 2 vectors together to make a NEW vector:
- p5.Vector.add(vec1, vec2);

<br></br>
## unit vector
Normalizing vectors
- take any vector of any length and direction --> make it into the unit vector
- nomalize a vector by dividing by the mag
- v.setMag(5) --> normalizes the vector and then scales it

<br></br>
## acceleration
f = m*a
- position relative to origin
- velocity - change in position in time
- acceleration - chang in velocity over time
limit() --> caps a vectors magnitute 
- make it look like a random walk 
