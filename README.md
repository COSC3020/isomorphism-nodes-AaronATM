[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/AtNXzL3S)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Proof:

Let $G_{1}$ be any graph with size n, vertices $u_{1}$, $v_{1}$ and $G_{2} be any graph with size n - i, where i is any non-zero positive integer, and with vertices $u_{2}$, $v_{2}$,

For some edge $E_{1}$ in $G_{1}$, there only exists a function $f: u_{1} \rightarrow v_{1}$ such that $(u_{1}, v_{1}) \in E_{1}$ and $(f(u_{1}), f(v_{1})) \neq (u_{2}, v_{2})$

For at least one edge, $G_{1}$ and $G_{2}$ do not meet the definition of isomorphism.

Thus, two graphs of different sizes cannot be isomorphic.
