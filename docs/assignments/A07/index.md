# A7 – FEA On A Bracket

## Objective
The main obejctive of this assignment is to use FEA to improve upon a design. In our case we had to improve upon a design of a bracket and link, making it stronger or lighter than previous designs.
## Bracket Loads
Firstly, for our tests with the bracket I chose the whole inside of the bracket as a fixed structure when testing, and a I used a parabolic force distribution on the pin. The force used was the same as calculated from A5. (1300 lbs) As shown below
![](BRACKET_1.png)
![](BRACKET_2.png)

As for mesh density I would first start with a low density, then medium and then the max density. (if needed) They are shown below, from low to high.

![](MESH_LOW.png) 

![](MESH_MID.png) 

![](MESH_HIGH.png)

They would come out looking like this on the bracket.

![](BRACKET_MESH.png)

# Performing Simulations on Bracket
## Bracket Design One
In order to save space I will only show the last set of simulations with the highest mesh density, however I have recorded all the data into an excel spreadsheet that also auto calculates the % convergence between tests. Shown below (in this order) are the stress, deflection, and factor of safety calculations.

![](BRACKET_F1.png)
![](BRACKET_F2.png)
![](BRACKET_F3.png)
![](EXCEL_1.png)

I did not get under the 7% difference however I did run it three times, so my final table will be using the third attempt with the smallest mesh. Due to the bracket failing under load my first improvement was to increase the thickness of feature B as it kept snapping. I would increase the thickness to .35 inches. as shown below. I would also increase the length of feature A as now the shaft was too short to support the full width of the strap describe in A5.

## Bracket Design Two

![](BRACKET_D2_1.png)
![](BRACKET_D2_2.png)

I then performed the same test as I did on design one, starting with a low mesh density then going to a finer mesh density. (same density for each test as in the first design.) Here are the results of the final run (finest mesh density)

![](BRACKET_D2_3.png)
![](BRACKET_D2_4.png)
![](BRACKET_D2_5.png)
![](EXCEL_2.png)

I again did not get under the 7% convergence difference but I again would run it three times, so my final table will be using the third attempt. The bracket still failed under load, even after increase the thickness of feature B. So I would add extra support behind feature B along with an extra truss on each side of it to give it extra strength. (As shown below)

## Bracket Design Three

![](BRACKET_D3_1.png)
![](BRACKET_D3_2.png)

I then, once again, preformed the same simulation as I did for design one and two. These are the results.

![](BRACKET_D3_3.png)
![](BRACKET_D3_4.png)
![](BRACKET_D3_5.png)
![](EXCEL_3.png)

Same as design one and two I couldn't get below the 7% convergence difference so I again ran the simulation three times, using my final run as the numbers shown in the table below. Even after adding more supports and trusses the bracket would still fail under load, so a major redesign needs to be done. 
## Final Table of Numbers for Bracket Designs

![](BRACKET_CHART.png)

# Performing Simulation on Link
## Link Loads

Firstly, for the simulation of the link, the fixed point will be the .6320 inch hole where it's suppose to slide onto the bracket, then the load was simulated along the 1 inch hole. A simulated load of 650 lbs was used, as calculated in A5. (settings shown below)

![](LINK_STUFF.png)
![](LINK_4.png)
![](LINK_MESH.png)

## Link Design One
Again to save space I will only upload the final simulated run that I performed, as shown below. My first run used the medium mesh density from the bracket and my second run used the fine mesh density.

![](LINK_1.png)
![](LINK_2.png)
![](LINK_3.png)
![](EXCEL_4.png)

Here I did get under a 7% difference between my first and second run which means I only performed two load simulations. Due the link failing under load I decided to increase the thickness of the link to allow it be able to handle the loads required. 

## Link Design Two
Here is what the increased link thickness looked like.
![](LINK_4.png)

I then preformed the same simulated loads as I did for design one, again starting from a medium density then a high density mesh. Results shown below.

![](LINK_5.png)
![](LINK_6.png)
![](LINK_7.png)
![](EXCEL_5.png)

I again was below the 7% convergence difference so I only ran two load simulations. After increasing the thickness of the link, it can now survive the loads specified in A5 with a factor of safety of 2.836. Now instead of increasing the strength, as it can properly hold the load needed, I wanted to decrease the weight. To do this I got rid of the bulky middle section as it added unnecessary weight that didn't add much to the strength of the part. (Design shown below)

## Link Design Three

![](LINK_8.png)
![](LINK_9.png)

I then preformed the same simulated loads as I did for design one and two, starting from a medium density then a high density mesh. Results shown below.

![](LINK_10.png)
![](LINK_11.png)
![](LINK_12.png)

## Decide


## Communicate

