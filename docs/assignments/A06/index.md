# A6 – [Topic]

## Objective
Build a parametric 3D CAD model of the bracket and generate a fully dimensioned engineering drawing with standard ANSI fit tolerances.

## Analyze
#### Parametric Sheet List
![Work for Step 2 Part 1](paramee.jpg)
![Work for Step 2 Part 1](parameters6.jpg)

#### CAD Files
https://a360.co/4z5pkbE
https://a360.co/4hyQT6b

## Decide


## Communicate
To control the radius of Feature A, I used the maximum bending stress equation. I established global variables for the applied load F = 300, cantilever span L = 2, and allowable stress Sigma = 10000. The dimension for the cylinder's radius was defined in the sketch using the expression =( (2 * F * La) / (pi * Sigma) )^(1/3).
On the engineering drawing, I applied a .005 tolerance to the internal height of the slot. This dimension defines a functional mating surface requiring a close running fit to ensure accurate location and minimal play. I applied a looser .02 tolerance to the overall exterior width of the bracket housing. The exterior width is a non-critical feature that does not interface with any other mechanical components.  A stricter approach would increase tool wear, inspection time, and overall manufacturing cost no benefit.   
