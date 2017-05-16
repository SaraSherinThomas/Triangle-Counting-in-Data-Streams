# Triangle-Counting-in-Data-Streams

We present two space bounded random sampling algorithms 
that compute an approximation of the number of triangles
in an undirected graph given as a stream of edges. Our first
algorithm does not make any assumptions on the order of
edges in the stream. It uses space that is inversely related to
the ratio between the number of triangles and the number of
triples with at least one edge in the induced subgraph, and
constant expected update time per edge. Our second algorithm
is designed for incidence streams (all edges incident to
the same vertex appear consecutively). It uses space that is
inversely related to the ratio between the number of triangles
and length 2 paths in the graph and expected update time
O(log |V | · (1+s · |V |/|E|)), where s is the space requirement
of the algorithm. These results significantly improve over
previous work [20, 8]. Since the space complexity depends
only on the structure of the input graph and not on the number
of nodes, our algorithms scale very well with increasing
graph size and so they provide a basic tool to analyze the
structure of large graphs. They have many applications, for
example, in the discovery ofWeb communities, the computation of 
clustering and transitivity coefficient, and discovery
of frequent patterns in large graphs.
