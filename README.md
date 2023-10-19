# CubeTracking
The aim of this project is to realize a positional recovery model of a cube (which could be a robot of any form) in a room. 
The cube is connected to the surrounding room with ropes that span from the robots corners to the room corners.
This allows the robot to move freely in all directions and even rotate to a limited degree.
The difficulty resides within the distances of the cube corners to room corners being the only allowed positional inputs besides room and cube size.
The project is structured in increasing degrees of complexity starting with a very basic non-rotating 80x80x80 cube in a 1000x1000x1000 room.
Ultimately a generalized, reliable, real world positional recovery of rope suspended machines with all the additional difficulties of noise and inaccurate measurements on the data is the vision.
For now, however, it is a learning project.

##1 Grid Search for non-rotating cubes

The very first approach to get familiar with the simplified problem and a possible solution.
Uses a least square error approach to iteratively find the best fit solution.

##2.1 Empty Search for cornerless cubes

In a second step the dependence of the first algorithm on the knowledge of the corner position was targeted.
Generalizes the cube to a sphere that fills the room between the ropes.
