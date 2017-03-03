Emily Gonzalez-Holland 
IDS 6938
Homework #1 

Part 1 
a) y= e^-x/2 sin  (5x) + C1/e^-x 

Part 2

Implemented Euler Integration 
Implemented Midpoint Integration
Implemented RK4 Integration
Implemented Verlet Velocity forces 
Implemented LeapFrog
Implemented Symplectic Euler 
Implemented Cylinder Collisions 
Implemented Floor Collisions
Implemented Sphere Collisions
Implemented Cube Collisions
Implemented center of cylinder calculations
Implemented range check for cylinder 
Implemented Shear springs
Implemented Bend springs 

Part 3

1)The effects of the Ks and Kd parameters on the jello are that if Ks is set to 0, there is no spring between the particles. Ks defines the springs stiffness, increasing Ks makes the spring more stiff. Decreasing Ks leads to the spring being less stiff and stretching more. Kds effect on the parameters of the jello is to dissapate the energy of the springs. Kd being large leads to a large dampening force, Kd being small leads to the energy going down slowly. 

2)The benefits of the  collision system are that they make the system more stable in some circumstances. It also simulates the real world, producing a more realistic scene. However, due to the collision systems not being literal/real, it does have drawbacks, for example, the jello exploding more easily. Therefore, one must ensure that the parameters of the jello are balanced. A way to improve the system is to add a feature where when the jello stops moving, the ks for the virtual spring becomes zero. 

3) A few examples of systems one could model with Mass-spring simlations are: string or cloth. To simulate string, each particle must be linked to two particles, springs would link these particles, using a force to define the resting and length of the particles. 

4) By fiddling with the parameters of the jello one could eventually achieve a realistic jello. The following integration methods were employed to make a stable jello: Euler, RK4, Midpoint. 

5) One would model and simulate water, in terms of continuous simulation, by creating a flow system, defined by spring forces, that would require a continuous, stable, simulation. 