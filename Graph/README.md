In the Graph project my work, in collaboration with a Czech collegue, was to create a graph composed by IDAuthor as nodes and Publications as edges. 

A glance to the data:

Once the graph has been created, the numbers of nodes were 900.000 while the edges were about 3 milion. That huge quantity of data, has influenced a lot in terms of computational complexity, expecially for the Dijkstra algorithm.




At first we had to calculate several measures like "Degree Centrality", "Closeness Centrality" and "Betweeness Centrality".


After that, we created a subgraph induced by the nodes that had "Hop Distance" at most equal to an integer "d" which indicated an IdAuthor.


Eventually, we implemented the Dijkstra algorithm by ourself. Thanks to this, we've been able to check which was the distance between a node and all the others.
