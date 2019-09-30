# AI_Globe_Rubix_Solver

Imagine a spherical tile rotation puzzle similar to a Rubik’s Cube.
The puzzle presents as a globe with three intersecting rings containing 12 tiles each. The rings are arraigned perpendicularly to one-another with one ring corresponding to the equator, and the other two corresponding to lines of longitude. The rings rotate freely with each tile occupying 30◦ of either latitude or longitude.
We number the tiles around the rings as follows:
• Longitude 0/180: (0◦, 0◦), (30◦, 0◦), (60◦, 0◦), (90◦, 0◦), (120◦, 0◦), (150◦, 0◦), (180◦, 180◦), (150◦, 180◦), (120◦, 180◦), (90◦, 180◦), (60◦, 180◦), (30◦, 180◦)
• Longitude 90/270: (0◦, 0◦), (30◦, 90◦), (60◦, 90◦), (90◦, 90◦), (120◦, 90◦), (150◦, 90◦), (180◦, 180◦), (150◦, 270◦), (120◦, 270◦), (90◦, 270◦), (60◦, 270◦), (30◦, 270◦)
• Equator: (90◦, 0◦), (90◦, 30◦), (90◦, 60◦), (90◦, 90◦), (90◦, 120◦), (90◦, 150◦), (90◦, 180◦), (90◦, 210◦), (90◦, 240◦), (90◦, 270◦), (90◦, 300◦), (90◦, 330◦)

I have implemented three search algorithms to solve the puzzle: 
1. Breadth-First Search 
2. A* 
3. Best-First Search

To test the program, you can view the output for PathN-<N>.mb specify a puzzle with a guaranteed solution of exactly N steps.
