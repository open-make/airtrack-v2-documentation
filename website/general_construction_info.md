
# General information about the setup and construction


>!! **Warning** 
>!!
>!! General info


like:
- breadboard
- used parts which just been around
- professional construction
- excluded documentation like camera setup wiring pathing at the table
- thorlabs expensive but why used

take some info from first page and spread more


- recommend to buy [M6 Cap Screw and Hardware Kit ](thorlabs_parts.yml#hwkit2m){Qty: 1}
    - used for air table fixation at breadboard and generally needed to mount stuff to breadboard






## Overview of the setup

The airtrack system consists out of a central air table with the possibility of modification.
In this version, a mouse moves on a floating lightweight plus maze, while being head fixed in the center above the platform.
Above the table a camera tracks the movement of the plus maze with different Aruco markers on the bottom side of the platform.
At one side of the table a moveable reward system is placed with two licking spots.
To detect if a spot was licked, a capacitive sensor is used which was designed by the Charité workshop.

The lanes on the maze are equipped with different features to distinguish them and correspond with the tasks. They can either be smooth or with gratings etched.
Further for the performed tasks, a LED (and buzzer) are installed to provide position feedback.


>! **Caution** 
>!
>! no buzzer anymore

The position tracking is done with a Basler ace acA1300-200um by detecting Aruco markers on the top side of the platform. 

The central table consists out of a plexiglass box with air flowing through. On the upper side many holes are placed to create an air cushion on the surface the platform can float on.
The table is mounted on aluminium legs and fixed on a solid aluminum optical breadboards.
On the breadboard is a lot space to place e.g. further tracking devices.
The computational tasks are performed with a Bpod r2+ and computer.




### Disclaimer: Construction complexity

Some parts are more difficult to construct than others. Mainly the central plexiglass box is difficult to build with an improvised work place. Precise cutting of the plexiglass is needed to ensure airtight manufacturing. Further, a workshop might use UV glue for the box which provides a higher quality.

If you have access to a workshop, we recommend you to get the air table constructed there. In general, it's better to have a large fraction of the Airtrack manufactured professionally. 


### Disclaimer: Bpod / Matlab code complexity

I order to fully use the Airtrack, you need to debug and write code for the Arduino. The provided code works but you need to adjust it at some places to adapt it to your circumstances. 


### Advice: Further development

If you want to use the base hardware of the Airtrack and want to use it for other research questions, we recommend you to have a good understanding of the Bpod and possible peripherals. Besides you need sufficient coding experience with Matlab (mostly used) to develop a good working code. 


The previous Airtrack was first published in 2016, with a paper titled [Air-Track: a real-world floating environment for active sensing in head-fixed mice](https://doi.org/10.1152/jn.00088.2016).

References: [Nashaat MA, Oraby H, Sachdev RN, Winter Y, Larkum ME. Air-Track: a real-world floating environment for active sensing in head-fixed mice. J Neurophysiol. 116(4):1542-1553, 2016](https://pubmed.ncbi.nlm.nih.gov/27486102/)

