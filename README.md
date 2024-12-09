# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Using the definition above to map to graphs of size n, we would use:

$$α:V(V1) \rightarrow V(V2)$$

$$α: (1,2,3,4,...,n), (1,2,3,4,...,n)$$

First we need the equation for the edges:

$$E = n/2 = (n(n-1))/2$$

Next we need to  make it clear that each vertex in G2 is paired with one vertex in G1. But also, every vertex in G1 is connected to every other vertex through $$(u,v) ∈ V1: (u,v) ∈ E1 -> (f(u),f(v)) ∈ E2$$

Since both matrices are similar, they can be mapped onto each other. This is where nodes are paired together.

With this definition there exists a permutation matrix P so that $$A_(G1) = P * A_(G2) * P^T$$

Therefore, A and B must be isomorphic because of their connected nodes, and having the same amount of nodes.

Sources:

https://courses.grainger.illinois.edu/cs173/sp2024/ALL-lectures/Lectures/graphs1.html

https://www2.math.upenn.edu/~mlazar/math170/notes05-2.pdf

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
