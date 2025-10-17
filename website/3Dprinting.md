# Peripherals part 5: Floating platform



>! **to add** 
>!
>! aruco marker and light conditions



{{BOM}}


There are several platforms you can use on the Airtrack. The size of the platform needs to be the same but the design of the upper part varies depending on your research question. Keep the weight of the platform mind when designing another maze like structure. 

The size of the platform needs to be in relation to the width of the air table, in particular the distance between both side borders. In the case of the mouse being close to the edge of the platform, the other side can heavily shift left and right if the platform has a way smaller diameter then the distance between the side borders. The diameter of the platform should not be more than 5 cm smaller.

In the following it is explained how to built the with a 3D printer which works but is not ideal. We get the platform without the marker done by the workshop which is not comparable to a self made platform. They use foamed PVC for the base and glue with double sided tape the maze structure as one part on top of it which is 3D printed on a very thin layer to have enough glueing surface.


#### Example platform for the large Airtrack


>!! **Warning** 
>!!
>!! Image of plaform with aruco marker





The platform base plate depends on the type or air table you are using. For small tables (not included in this guide), air is flowing directly and the platform needs to have a rim on its lower part. For large tables the platform should be completely flat because it presses down balls in the plexiglass surface. The balls are used to limit the air flow and by this the needed air flow is reduced to maintain the platform floating.

It's important to be aware about the influence of the material's surface to the mouse. The layer height in the print settings and the material used for the print are the main factors determining the surface's shape.
But a 3D printed platform has mostly a flat and slippery surface which doesn't allow the mouse to move as expected. It's recommended to attach some grips or slip-proof materials to allow the mouse to move naturally on the platform. A possible solution is a grip tape.

The mice will kick out the wall from time to time. If you don't need them to be exchanged it's recommended to fixate them. 

## Example platform

The components need to should printed independently and get glued afterwards. Use the STL-file of the hole platform as orientation.

We recommend to use a [plexiglass plate](plexiglass.yml#r300mmpg){Qty:1} with a diameter of 300mm as bottom plate. The other parts need to be glued on top of it as shown in the whole large platform STL. Instead of 3D printing, similar materials can be used, too.


>i **Note** 
>i
>i You might need to round the bottom corners of the platform to improve the mobility of the platform




#### Whole platform
![](models/l_Maze_all.stl){color: grey}

#### Ground of Platform
![](models/l_Maze_X_ground.stl){color: grey}
#### Walls mounts of platform 



>i **Directly after printing** 
>i 
>i Open the small gaps to ensure the wall fits in between later.



![](models/l_Maze_X_wallmount.stl){color: grey}
#### Walls of platform 
![](models/l_Maze_X_walls.stl){color: grey}



## Additional information: small platform

The components need to be printed independently and get glued afterwards.
Instead of 3D printing, similar materials can be used, too.


#### Whole small platform
![](models/s_Maze_X_all.stl){color: grey}
#### Rim
![](models/s_Maze_X_rim.stl){color: grey}
#### Ground of small Platform
![](models/s_Maze_X_ground.stl){color: grey}
#### Walls of the small platform
![](models/s_Maze_walls.stl){color: grey}
#### Wall mounts of the small platform
![](models/s_Mazewall_mount.stl){color: grey}







