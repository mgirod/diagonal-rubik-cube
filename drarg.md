# Representation and drarg #

Trivial example of using drarg:

```
$ ./drarg P
P
                         -     -     - 
                            -     -    
                         -     -     - 
                            -     -    
                       4/11    -     - 
     -     -   0/12     3/9    -     -       -     -     - 
        -    0/3           3/4    -             -     -    
     -    0/0   0/7     3/5   3/0    -       -     -     - 
       0/1   0/2           3/1   3/2            -     -    
   0/10   0/6  0/11    3/10   3/6  3/11    5/10    -     - 
                       2/12   2/7  2/11
                           2/3   2/2   
                        2/8   2/0    - 
                           2/4    -    
                        2/9    -     - 
                       1/11    -     - 
                            -     -    
                         -     -     - 
                            -     -    
                         -     -     - 
--------------------------------
```

The argument, _P_, is the anti-clockwise rotation around the vertice (0/11, 2/12, 3/10).<br>
In these pairs of numbers, the former identifies the face (0-5), the latter the element in the face (0-12).<br>
In the textual representation, face 0 is in the center, face 1 above it, 2, 3, and 4 around it in anti-clockwise order, face 5 below.<br>
In every face (upright in the representation), 0 is the centre, 1 the north-west square, 2, 3, 4 the remaing squares in counter-clockwise order, 5 the top triangular  edge, 6, 7, 8, the other edges in counter-clockwise order, 9, the north-east vertice, 10, 11, and 12, the other vertices, counter-clockwise.<br>
<br>
<hr />
<a href='Top.md'>Top</a> <a href='drargNext.md'>Next</a>