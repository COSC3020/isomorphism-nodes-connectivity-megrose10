# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

With this formal definition, we can argue with it to prove that these two graphs are isomorphic. Within each graph, they have the same number of nodes, no matter if it is A or B. They are also completely connected, hence for every vertice there is an edge going to another vertice. Each graph contains this. If we wanted to map them in another way, we still have the same amount of nodes, so the same amount of vertices crossing over. So, within this bjection, mapping f in another way will still contain the same structure of the graph before the change of shape. If we add another node, no matter how we move this graph, it will not be isomorphic to the other unless another node is added becuase we can not mirror the structure becuase of the extra elements. Mapping f can only be a bijection with the nodes connected. 

I used the class slides on graphing. I also got help from the TA in lab.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
