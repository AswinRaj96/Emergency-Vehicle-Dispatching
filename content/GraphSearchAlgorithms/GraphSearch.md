
# Graph Search

A graph is a mathematical way to represent road networks. Graphs consist of 3 sets: 

- vertices/nodes
- edges
- a set representing relations between vertices and edges 

The nodes represent intersections, and the edges represent the roads themselves. A `route` is a sequence of edges connecting the `origin node` to the `destination node`. <br><br>

`Searching` is the systematic examination of states to find a path from the start state to the goal state. Mathematically speaking, a graph can be represented by $G$, where 

$G=(V,E)$
<br><br>

For a graph $G$, vertices are represented by $V$, and edges by $E$.
 
Each edge is a tuple $(v,w)$, where 

$w$, $v \in V$

Weight can be added as a third component to the edge tuple.<br><br>

Search algorithms can be broadly classified into `deterministic` algorithms and `stochastic` algorithms. 

In the former, the search algorithm follows a rigorous procedure and its path and values of both design variables and the functions are repeatable. For the same starting point, the algorithm will follow the same path whether you run the program today or tomorrow. 

In the latter, the algorithm always has some randomness and the solution is not exactly repeatable. Based on the availability of information about the search space (e.g. the distance from the current state to the goal), deterministic search algorithms can be broadly classified into `blink/uninformed` and `informed` search.

![Graph Search](../../images/GraphSearch.png)