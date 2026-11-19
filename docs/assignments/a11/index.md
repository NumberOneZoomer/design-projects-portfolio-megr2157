# A11 – Motor Selection

## Objective


## Motor Selection
The motor we have selected is the HT23-598D-GBA NEMA 23 from Applied Motion Products. It can produce sufficient torque and has capabilities such as an encoder so we can calculate exactly how much force is being applied. 
![](Motor_torque)

Afterwards we must design a mounting bracket for this motor, what we choose to do was to have the lead screws and motor sit off axis from the main structure for ease of assembly and maintenance. This is configuration is commonly seen on 3d printers. To solve for the thickness of the bracket I first listed all knowns and unknowns and also drew and FBD. 

![](A11_1)
![](A11_2)

Afterwards We solved for thickness symbolically, then I solved for it numerically. This would lead to a minimum thickness of 14.52mm based on a max deflection of .1mm.

![](A11_3)

After that we solved/designed for the coupler that connects the motor to the lead screw. To start we listed all knowns and unknowns and drew and FBD to get a better understanding of the problem.

![](A11_4)
![](A11_5)

Then we listed all equations relevant and then solved for the outer diameter symbolically. By solving for outer diameter we can then find the minimum thickness needed to withstand the torque. After symbolically solving I then solved numerically, doing so found a outer diameter of 7.867mm. leaving a thickness of 1.517mm. Assuming the material is 6061 Aluminum, Since this is very thing almost any coupler found on the market would do. We settled on this 6.35mm-6.35mm flexible coupling from StepperOnline.

## Frame Analysis

To decide on what connectors to use for the frame we must perform a stress analysis on the top crossbeam based upon the torque generated from the motors. To do this we first listed all knowns and unknowns and FBD. 

![](A11_6)
![](A11_7)

I then solved for it symbollically, then numerically, this would show us that the total force acting on each connector is very little. Since the number is quite small almost any L bracket will do. In the end we chose a Corner Bracket from Grainger.




## Floating Bearing Mount

We were tasked to design a holder for the bearing that the lead screw will screw into. To do this we must first look at the design of the motor bracket to see how far the bearing needs to stick out. We made .625 inch hole that is .2 inches deep for the bearing to sit in. The tolerances described in the drawing follows the RC-3 Running class fit for that size of hole. The two holes right of it is where the bolts will screw through, they also follow the RC-3 Running fit class for that size (.25 in) bolt. The total block is 2 inches long by 1 inch wide and .25 inches tall. 

![](A11_8)


## Communicate
