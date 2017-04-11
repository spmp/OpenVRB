# OpenVRB
The Open Vanadium Redox Battery ([VRB]) aims to develop a working residential scaled VRB in a public space using open tools and technologies.

## Introduction
![two cell stack][two cell stack]

VRB's are unlike traditional battery technologies in that they separate the chemical to electrical conversion from the energy storage.
The chemical to electrical conversion (and visa versa) occurs in a _cell stack_ which the storage chemicals are cycled through from storage containers.
This allows the storage capacity to be cheaply scaled as the need arises, unlike traditional batteries where to increase storage capacity a whole set of batteries may need to be purchased.
Another less explored advantage for off grid users is the ability to charge the battery at any of the cell stack voltages, not just at the final voltage, and in this way VRB's can also act as DC transformers.

VRB's may be one of the easier batteries to manufacture _at home_, with _relatively_ safe and simple chemistry, with the majority of the _problem_ being the manufacture of leak free cell stacks.

A great impediment to home manufacture is the cost and availability of the _membrane_. The most common membrane material is [Nafion 117], which although being available could be prohibitively expensive to most would be battery makers.

In this project we will focus on using FDM 3D printing technology to print the cell stack, investigating different materials and designs to optimise fluid flow.
We will investigate various battery configurations to minimise self discharge and the need for expensive proprietry membranes.
Finally the control gear and metrics reporting will be developed.

## How VRB's work
![how a vrb works][how a vrb works]

A VRB is a special case of a [redox flow battery], using Vanadium ions in both half cells.
What makes an 
![test][test]

### Chemistry


### Cell stack


### Electrical properties


#### Voltage (VPC)
#### Current
#### Storage capacity

## Project roadmap

1. Investigate suitable materials
2. Trial various flow frames and gaskets for
    a. _Water_ tightness
    b. Fluid dispersion into felt
    c. Maximum flow rate
## 3D printing considerations



[images]: # (Below be the images)
[two cell stack]: images/cell.jpg "Simplified two cell stack"
[initial frame prints]: images/F4.medium.gif "Published prints for 3D printed VRB frame"
[initial frame model]: images/F8.medium.gif  "Published CAD model for 3D printed VRB frame"
[spiral flow]: images/F9.medium.gif "Published CAD model for 3D printed spiraling fluid flow chamber"
[how a vrb works]: images/how-does-a-vrfb-work.png "Detailed chemical model of VRB"
[wikipedia-image]: images/Redox_Flow_Zelle_Deutsch_Farbverlauf.png

[links]: # (Below be links)
[redox flow battery]: https://en.wikipedia.org/wiki/Flow_battery
[VRB]: https://en.wikipedia.org/wiki/Flow_battery
[Nafion 117]: http://www.sigmaaldrich.com/catalog/product/aldrich/274674
[earliest]: http://www.arizonaenergy.org/Analysis/FuelCell/Vanadium%20Battery/recent_progress_with_the_unsw_va.htm