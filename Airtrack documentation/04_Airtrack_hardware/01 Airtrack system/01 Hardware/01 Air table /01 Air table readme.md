# Part001, Air table

This was developed as a part of the Airtrack [URL] of main document.
Look there for more information on the context where this part was designed, as well as get information on the developers and the community.





### Hardware overview

The air table provides a surface with low fraction for a platform to move on it. The platform acts as environment for a mouse to move around.
It consists out of a rectangular box with several holes in the top, some borders at the top edges, aluminum profiles at the sides and connections for incoming air.

In the top holes, ball valves are placed to reduce the air flow if the platform is not above the hole.
The edge borders keep the platform on the air table and ensure that the platform is not shifting too much sideways. This is important for proper mouse movement.
The aluminium profiles are used to have multiple connection points to the setup table with variability in height. 







### Standard compliance

### Outputs: Products and data

The resulting hardware is an air table to be integrated in a research setup dedicated to the analysis of e.g. movement or decisions.

### cost

### validation

## Cite this project



## Dependencies

This project is build on the Airtrack which was first developed in 2016 and published with a paper titled "Air-Track: a real-world floating environment for active sensing in head-fixed mice". (https://journals.physiology.org/doi/full/10.1152/jn.00088.2016) 

indicate and cite projects this project is built on
For the software part, indicate the main component, use a dependency.txt files in the software folder when needed.

## License and rights

## Documentation structure

This document covers the requirements to build an Airtrack of the new version. 

1. Construction of the air table box

2. Mounting and head fixation

# Hardware details

## Bill of material

## material characteristics

## electrical design

## firmware/Software: Documentation of different parts

## Manufacturing instructions

Requirements:

- Drill rig

- Plexiglass cutter - precise straight cuts




## Assembly instructions


1. Construction of the air table box

The air table is a 480mm x 326mm x 80mm box with 35 equally spread holes (8mm diameter + 1mm sink drilling) in the top side. These holes will be filled with ball valves. The box also needs along both long sides 20mm x 20mm aluminium profiles to mount it later. Add holes in the sides therefore and add the aluminium profiles before glueing the box. The profiles should be places to have the upper side at the same level as the top plexiglas surface to add the side walls.

Further before glueing add at one of the short sides holes for incoming air and a pressure relieve valve. We have about 6bar incoming air pressure for our air table.

The top and bottom plexiglas should be 480mm x 326mm while the top plate is screwed and glued and the bottom is only glued. Pre-drill for screwing. In our case we used light sensitive glue for precise glueing.

This air table then needs to be mounted on some kind of board. We use a Newport table with M6 screw holes like a Thorlabs breadboard. Use four times two 1/2" Thorlabs rods and corresponding angles to mount the air table on the breadboard. All four connecting should be more placed to the edges of the box and must be used with a spirit level to make the air table perfectly horizontal. 

Finally add the ball valves to the holes. A detailed documentation of creating ball valves can be found here: https://open-make.github.io/airtrack-doc-website/ballvalve.html

- maybe make ball valves a part as it cannot be described precise with just some words


Additionally the air table needs a small wall (like 2cm in height) at all places we the platform could move out of the table at first. The corners don't need walls. (sideview_with_walls.jpg)


2. Mounting and head fixation

Head fixation: 

Use two Thorlabs rods like the 20cm ones with 3/2". Place the rods centrally beside the table on the breadboard. Add to both rods an 3/2" rod angle and connect both angles with a 1/2" Thorlabs rods and 1/2" rod angles. Centrally you now can add a head fixation. Our head fixation fits in the 1/2" Thorlabs angles. 

Angles:
https://www.thorlabs.com/item/RA90_M
https://www.thorlabs.com/item/C1515_M  


Additional mount structure:

For easier mounting and in our setup the Neuropixel 180 degree platform, we have an additional breadboard above the air table where also the lights and some cameras are mounted. The Neuropixel platform is mounted at the vertical rods. (whole_setup.jpg & view_top_breadboard.jpg).

Therefore use three times two 3/2" Thorlabs rods and a 60cm x 60cm Thorlabs breadboard. Place the rods in a triangle of your desire, we have 2 at the back and 1 central in the front. That suits well for the motor (central front) and Neuropixels (2 in the back). On top place the Thorlabs breadboard.


- skills
- tools
- link to instructions



























