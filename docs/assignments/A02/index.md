# A2 – Truss Stress Analysis

## Objective
-Design a truss using A500 steel
-Create free body diagrams
-Determine pin sizes based on shear forces with a safety factor.
-Solve equations symbolically and numerically for both truss and pin design.
-Estimate the total weight of the truss and pins.
-Create a CAD model with accurate dimensions and connections.
-Compare CAD weight predictions with hand calculations.
The main goal is design and create a truss that fits the given scenario, along with creating the truss we also want to make it as light as possible. Point A is pin support and Point B is a roller support, the P values I choose was 25 kN. When modeling in solidworks I created a custom material that fit the specifications of A500 steel.
## Decide
 ![](truss1.png)
The first step was to design a truss for this situation, since we were instructed to keep it as simple as possible, along with keeping weight down, I choose a simple planar truss. This achieves both goals as it uses the least amount of members and joints (7 members and 5 joints) keeping weight down and leaving the design to be quite easy on the eyes. It is also still quite strong as all the shapes are triangles, which are the strongest shape. I labeled the dimensions using the variables given and added a legend to the side. Note I labeled each point with a corresponding number that will be refrenced later.
## Analyze
### Joints of the Truss
![](truss2.png)
Firstly we must analyze each joint of the truss to figure out how the forces and intermember forces act upon one another. Note every force that acts on a join is labeled in red, whereas each member itself is black.
![](truss3.png)
Secondly we were instructed to solve for each join symbolically so that is what I have done here.
![](truss34.png)
Finally we were instructed to numerically solve for each member and there forces. To find A<sub>y</sub>, A<sub>x</sub>, and B<sub>y</sub> I calculated the total moment of the truss as a whole at points A and B. I would then go on to use these values to solve the rest of the forces in each member. Note: my calculations for θ and	Φ on the left side.

## Communicate
