# Prim-s-Algorithm-for-Minimum-Spanning-Tree
This is an implimentation of Prim's algorithm for finding the minimum spanning tree of a set of connected undirected graph.

The 'w' variable is a 2-d array that holds the weights of each vertice edge connection. It is initialized by default with the value 
w = [[0, 1, 3, ifn, ifn],
     [1, 0, 3, 6, ifn],
     [3, 3, 0, 4, 2],
     [ifn, 6, 4, 0, 5],
     [ifn, ifn, 2, 5, 0]
       ]
  For example, the vertex V1 is represented by the first array in the 2-d array. V1 to V2 costs 1, V1 to V3 costs 3, and there are no connections from V1 to either V4 or V5

There are no added preperations to run the program. Simply download it and run.
It will run the default w value as shown above and return the minimum spanning tree of it.

To test other vertices, simple replace w's value with a 2-d array representing the new vertices and edges

*WARNING the new one must have valid edges. If the changed w does not represent a valid set of connected vertices, errors may occur.


Another example vertices to test with:
[[0, ifn, 4, 1, ifn],
[ifn, 0, 3, 1, 3],
[4, 3, 0, ifn, ifn],
[1, 1, ifn, 0, 2],
[2, 3, ifn, 2, 0]
 ]
