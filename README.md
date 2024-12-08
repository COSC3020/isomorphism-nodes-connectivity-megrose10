# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

With this formal definition, we can argue with it to prove that these two graphs are isomorphic. Within each graph, they have the same number of nodes, no matter if it is A or B. They are also completely connected, hence for every vertex there is an edge going to another vertex. Each graph contains this. If we wanted to map them in another way, we still have the same number of nodes, so the same number of vertices crossing over. For example, if we have two nodes from graph A and try to map those to all the nodes in graph B if graph B had 10 nodes, this would not be a bijection. The reason for this is because they do not have a one-to-one mapping, resulting in these two graphs not being isomorphic. In this problem however, since graph A and graph B have the same number of nodes, mapping each node to the other will allow for pairs of nodes to be connected not leaving any out and no nodes being mapped multiple times. Hence, these two graphs are isomorphic. Looking into the graph lecture, we can find if two nodes are connected by the degree. For instance if two nodes contain an edge, are connected, we will see an e with a subdegree showing they are connected. If both graphs contain the same degrees through the same nodes that are connected they are isomorphic. So, like in the slides, we can ignore vertex names and if they have the same node pairings as descriped in the above e subdegree statement, they have the same structure. 

I used the class slides on graphing. I also got help from the TA in lab.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
