# Dijkstra-Algorithm
Implement Dijkstra, using the same input files as Kruskal. In this program, compute the distance from vertex 0 to all the other vertices. All edges are un-directed; if you see an edge from X to Y of length Z, assume that you have an edge going from Y to X of the same length (the input file will not tell you both directions; you'll have to take care of that in your code.
Use a graph data structure that lets you have an arbitrary number of edges per vertex. Do not try to do this with a matrix. Seriously, don't do that. It will only end in tears.
Use a binary heap to maintain the vertices, based on distance. Dijkstra's algorithm uses a priority queue; a binary heap will make an excellent priority queue. Write this code on your own; do not use a built-in library. When you update the distance to a vertex during the run of Dijkstra's algorithm, you will also need to update the position of this vertex in your heap. Doing this correctly will require some careful data structure work. Think carefully about how you implement this.
Your program should print out the distance to the most distant vertex (relative to vertex 0), and the vertex number. If vertex is not connected to vertex 0, ignore it entirely....
Here are a few more sample files to test with
•	Dijkstra1, most distant vertex is 40
•	Dijkstra2, most distant vertex is 4
•	Dijkstra3, most distant vertex is 4
