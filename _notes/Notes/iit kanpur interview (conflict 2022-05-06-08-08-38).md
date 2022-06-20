# Final year project
[[Structural engineering interview question]]

[[Steel structure question]]

https://www.iitk.ac.in/nicee/IITK-GSDMA/EBB_001_30May2013.pdf

https://youtu.be/RjgoCs9pNFo


We need high rised building because **space is limited** nowadays


# General


# Introduction
Our building was G+23

two things control seismic design 
	mass
	stiffness

Earthquake induces inertia force

Structures with **convex** geometries are preferred to those with **concave** geometries, as the former demonstrate superior earthquake performance. In the context of buildings, *convex shaped buildings have direct load paths* for transferring earthquake shaking induced inertia forces to their bases for any direction of ground shaking, while concave buildings necessitate bending of load paths for shaking of the ground along certain directions that result in **stress concentrations at all points** where the load paths bend

![[Pasted image 20220429143938.png]]

![[Pasted image 20220429143917.png]]

Buildings with rectangular plans and straight elevation stand the best chance of doing well during an earthquake, because inertia forces *are transferred without having to bend due to the geometry of the building*


# Energy Dissipation Mechanisms
During an earthquake, high energy is applied to the structure
it can be dealt with - **additional stiffness** (_increase size of columns_) can be provided to reduce the vibration period of a building. Secondly, **changes in mass** _(light structure_**)** of a building can be effective in reducing excessive wind-induced excitation. Finally, **aerodynamic modifications (convex shape)** to the building's shape
but still damping is very low as it is *passive* we can deal with it but then it is problem of cost, aesthetics ,space

**180 degree is out of phase**

## What is damper?
A damper is a device that deadens, restrains, or depresses some of the energy input to the structure will be absorbed, not by the structure itself

They are used in place of structural elements, like **diagonal braces**

partly absorb the seismic energy and reduces the motion of buildings

ideal damper should be able to simultaneously reduce both stress and deflection in the structure

Damping ratio tells us about how quickly energy is dissipated
The damping ratio is a measure describing **how rapidly the oscillations decay from one bounce to the next**.

**Transient**
A transient vibration is **one that dies away with time due to energy dissipation**

**Overdamped**
Damping ratio > 1
comes back to position without oscillation
ex - door in hospital, automatic closing door

**Underdamped**
Damping ratio < 1
return slowly

**Critically damped**
Damping ratio = 1
returns as quickly as possible

**Undamped**
oscilllation continues indefinitely 

$\zeta$ is damping ratio



#### Types of dampers

**Hydraulic**
	damping elements that convert the kinetic
	energy of moving parts into thermal energy

These systems dissipate energy by forcing a fluid through **orifice**
fluid can be oil or high molecular weight **polymer**

Example - silicon or bitumen. 
*Oil Not used* - Oil dampers require **frequent maintenance** so not commonly used

**Metallic dampers**
	utilise the [[hysteretic behaviour]] of metals The damping caused by the friction between the. internal planes that slip or slide as the material.

**A tuned mass damper**  
	mounted in structures to reduce the amplitude of mechanical vibrations
	
it moves out of phase
	
The advantages of tuned mass dampers include not depending on external power for their operation

Taipei 101 , 800 tonnes , takes days to come at rest position

**The tuned Liquid dampers** 
	tank, easy installation  , analysis of mass ratio on software

It imparts indirect damping to a structure via out of phase inertial forces

The design of a TLD involves tuning the frequency of wave sloshing to or near the natural frequency of the structure while energy is also dissipated through internal viscous action of the fluid, friction effects between the fluid and the walls of the container, slamming impacts of the fluid against the wall of the container, contamination of the free surface with floating particles, and wave breaking

**Base isolators** 
	separation of superstructure and foundation , when earthquake is there only base isolaters **displace very little amount of energy is transferred**

**Friction dampers**
	Leaves are placed over one another , ex- horse carriage in 1860
There is friction between these plates

### Chosen dampers

**FVD**   
	stainless steel
	Bronze orifice head
	Compressible fluid – non flammable, non toxic
	*Dissipation through heating of liquid*

The damper with $\alpha$  = 1 is known as linear FVD in which damper force is proportional to the velocity  **Reduces base shear**

The damper with $\alpha$ < 1 is called a nonlinear FVD (Force -velocity)

**Damping force -** **The resistive force**

Velocity - relative velocity between the two ends of the damper

**Alpha greater than 1 impractical** ..for a sudden change in velocity sudden rise in resisting force which might **yield**

- out of phase
- advantages -- easy installation and replacement as well as coordination to with structural members

**The tuned mass damper**
	device consisting of a mass, a spring, and a damper

- dissipation by the damper inertia force
- A tuned mass damper is preferably placed where the deflection of the structure is **greatest**. The advantages of tuned mass dampers include not depending on external power for their operation
- require large mass or large space

**Tuned Liquid Damper (TLD)**
dissipated through
internal viscous action of the fluid,

friction effects between the fluid and the walls

A particular advantage of the TLD is that it may be added onto any existing structure with ease.

**Base isolation ----** separation of superstructure and foundation, when earthquake is there only base isolators **displace very little amount of energy is transferred**

**VALIDATION**

 **FVD**
A single story, single bay frame structure , impulse  load suddenly applied

Length and height – 3 m

25000 kg

9869 kN/m

A half sine shock impulse is created when the shock machine table accelerates downward, then impacts a rubber material and changes direction abruptly. This abrupt change in direction causes a rapid velocity change which creates the shock impulse

Centre of rigidity—centre of stiffness (shear walls) torsion is produced around the centre of rigidity

_Process – select slabs and select diaphragm_

**TMD**

Is 1893

Table 2 - soil type medium soil

Table 3 – seismic zone factor 0.36

Table 6 – importance factor

Table 7 – R (response reduction factor)

Response spectrum is used for determining the maximum displacement for a building for a given ground acceleration when time history data is not available

**Max response vs undamped natural period**

Define seismic load in load patterns

Assignments of soil type and zone factor

Clause no 7.8.2.1 – 5 percent damping (RCC)

Studies have shown that the maximum efficiency of TMD is obtained by placing it at the highest storey



**TLD**

**Vortex shedding**
when the wind blows from one side to another it creates alternate low pressure zones resulting in suction which gives rise to fluctuating force at right angles

water without overtaking valuable rentable floor space is a major challenge.

Mode participation factor--- amount of mass moving in each direction for each mode

Modal analysis – a technique used to determine a structures vibration

Eigen values represents shape of mode

Process – table>analysis>results>model participation ratio>gives  table **choose mode 1**

# Centre of mass and centre of rigidity

## Centre of Stiffness

**The point through which the resultant ofthe restoring forces of a system acts**

**Show table > analysis > result > Structure results > Centre of mass and Rigidity-----it shows coordinate wrt origin**

If it doesn’t show ---

Go to analyze > set load cases to run > tick the option of center of rigidity

Select the slabs of structure > assign > shell > diaphragm > rigid

·       The mass of the building being designed controls seismic design in addition to the building stiffness, because earthquake induces inertia forces that are proportional to the building mass.

·       Structures with convex geometries are preferred to those with concave geometries, as the former demonstrate superior earthquake performance. In the context of buildings, convex shaped buildings have direct load paths for transferring earthquake shaking induced inertia forces to their bases for any direction of ground shaking

·       Response reduction factor -the factor by which actual base shear should be reduced

·       Based on occupancy -  1.5 for telephone exchange, railway station

Diaphragm – structural element which transmits lateral loads to the vertical resistance elements

# How to calculate time period of building

![[Pasted image 20220501165355.png]]

# How FVD were arranged ?
- along the perimeter of all story
- along the inner of all the floors
- long the corner of all the storey
- along the perimeter of alternate storey
- he inner side of alternate storey
From the results, it is concluded that damper along the perimeter gives the least storey response.

# How TMD was calculated ?
- research shows best at the top of building
- considered various mass ratio

# Final result 
- FVD was the most efficient almost 48 percent