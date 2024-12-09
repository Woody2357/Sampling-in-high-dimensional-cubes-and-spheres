# Sampling-in-high-dimensional-cubes-and-spheres

This project estimates the volume of the intersection between the unit cube and the unit ball in higher dimensions using Monte Carlo integration.

The script calculates the volume of $B^d \cap C^d$ for dimensions $d = 5, 10, 15, 20$ using two methods:

1. Sampling in the Unit Cube:
   - Generates random points uniformly distributed within the unit cube $C^d$.
   - Estimates the volume based on the proportion of points that also lie inside the unit ball $B^d$.
  
2. Sampling in the Unit Ball:
   - Generates random points uniformly distributed within the unit ball $B^d$.
   - Estimates the volume based on the proportion of points that also lie inside the unit cube $C^d$.
