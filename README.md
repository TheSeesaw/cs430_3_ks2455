# CS 430 project 3

Takes in a list of both physical and light objects and renders a scene that is output as a P6 ppm file.

Compiles with 'make'

Usage:$ ./raycast width height input_file output_file.ppm

Known Issues: Reads in light data, but does not yet perform light casting. Produces invalid shape error even with a valid file.

NOTE: I completely rebuilt my raycaster from scratch, and that was working prior to adding the parts of this project. Additionally, the git history for that rebuild is on a different git repository. I can prove both of the previous statements, please have mercy on me.
