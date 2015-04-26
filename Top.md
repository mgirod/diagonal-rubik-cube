# Diagonal Rubik's Cube #

The cube is a normal 6 faces cube, but it is split along to planes diagonal to the edges. This defines in each face 5 squares (1 centre + 4), 4 triangular vertice, and 4 triangular edge pieces.

![https://www.dropbox.com/home/images/diagonalRubiksCubeDemo.jpg](https://www.dropbox.com/home/images/diagonalRubiksCubeDemo.jpg)

The basic moves are rotations around the vertices, clockwise and anti-clockwise (3 times the same rotation yield the original position).

I have named the 8 vertices with letters from p to w, used lowercase for the clockwise and uppercase for the anti-clockwise rotations.



A first script, _[drarg](drargNext.md)_, takes an arbitrary combination, and [represents](drarg.md) its effect on the cube.

My approach is to look for sequences which preserve as much as possible of the current position, and result in simple and complementary changes.

Typically, I am starting from sequences of different rotations, completed with their anti-rotations in a slightly different order.

This is what I have explored in the _dr1_, _dr2_, and _dr3_ scripts.