

Programming Assignment 4 | BFS


Programmer: Jay Montoya
UCSC ID: jaanmont | 1742317

  This project creates a Graph ADT capable of executing a Breadth-First
searching algorithm. The client FindPath reads in an input file in two
stages: first reading in the edges and number of vertices, then the source and
destination pairs to perform BFS with.

   The underlying data structure for the Graph ADT consists of 3 integer arrays
(the color, parent, and distance from source) and an array of integer lists
representing the adjacency list of the graph. The Graph ADT also contains int
data types for the order, size, and last used source.

Along with the following operations:

    Graph newGraph(int n);
    void freeGraph(Graph* pG);

    int getOrder(Graph G);
    int getSize(Graph G);
    int getSource(Graph G);
    int getParent(Graph G, int u);
    int getDist(Graph G, int u);
    void getPath(List L, Graph G, int u);

    void makeNull(Graph G);
    void addEdge(Graph G, int u, int v);
    void addArc(Graph G, int u, int v);
    void BFS(Graph G, int s);

    void printGraph(FILE* out, Graph G);

  This project passes the test script completely and free of memory leaks as of
11/29/2019.
