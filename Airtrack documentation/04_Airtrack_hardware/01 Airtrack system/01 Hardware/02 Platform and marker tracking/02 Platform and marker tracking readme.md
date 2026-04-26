# Part002, Platform and marker tracking

This was developed as a part of Airtrack, [URL] of main document.
Look there for more information on the context where this part was designed, as well as get information on the developers and the community.


### Hardware overview

This section is about the platform which is meant to float on the air table.
On top of the platform are walls with a plus maze shape to limit the area the mouse can walk to.
Additionally Aruco markers are placed on top in the non walking areas to track the platform position and orientation.
Above the air table a camera is placed to acquire the images for the marker tracking.



### Standard compliance

### Outputs: Products and data

A platform with a plus maze on top to use in the Airtrack.

### cost

### validation

## Cite this project



## Dependencies
indicate and cite projects this project is built on
For the software part, indicate the main component, use a dependency.txt files in the software folder when needed.

## License and rights

## Documentation structure

1. Description of the platform

2. Tracking of the platform

# Hardware details

## Bill of material

## material characteristics

## electrical design

## firmware/Software: Documentation of different parts

## Manufacturing instructions

3D printer required

- skills
- tools
- link to instructions

## Assembly instructions

Get a 30cm circle of a materials as thin and stable as possible. Slight bending over time will increase the friction significant. Carbon is recommended. On top of the platform glue the plus maze. Attached are the files for the walls and wall mounts. It is recommended to place the wall mounts or walls and wall mounts on a thin 3D printed layer of the full maze to have more glueing surface. The walls need to be glued if not directly printed together as mice learning to kick them out.

To track the platform 4 Aruco markers (7cm x 7cm, IDs: 1,2,3,4) need to be placed on the platform - one between each lane. To not change the corresponding scripts the markers need to be place 1,4,2 and 3 clockwise. 

2. Tracking of the platform

In order to track the platform place a Basler camera (ace acA1300-200um) central front and turn it to have the x axis along the long side of the air table. The x axis needs to be low at the front and high at the back. The camera should more or less capture only the air table.

3D part files:

l_Maze_X_wallmount.stl
l_Maze_X_walls.stl


- skills
- tools
- link to instructions