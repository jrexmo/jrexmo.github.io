---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /research
---

Here is some of my work (click for abstract):

<details>
  <summary>1. Simple vertex coloring algorithms - with Fang Song, QIP 2021</summary>  
        
 Given a graph G with n vertices and maximum degree $∆$, it is known that $G$ admits a vertex coloring
with $∆ + 1$ colors such that no edge of $G$ is monochromatic. This can be seen constructively by a
simple greedy algorithm, which runs in time $O(n∆)$.
Very recently, a sequence of results (e.g., [Assadi et. al. SODA’19, Bera et. al. ICALP’20,
AlonAssadi Approx/Random’20]) show randomized algorithms for $(1 + ε)∆$-coloring in the query
model making  $\tilde{O}(n√n)$ queries, improving over the greedy strategy on dense graphs. In addition, a
lower bound of $Ω(n√n)$ for any $O(∆)$-coloring is established on general graphs.
In this work, we give a simple algorithm for $C$-coloring where $C > ∆ + 1$. This algorithm makes
$O(\frac{n}{C−∆})$ queries. This matches the classical lower bound for $C ≥ c∆$ with $c ≫ 1$ and a new upper
bound of $O(n^{\frac{k+2}{k + 1}})$ for $C = ∆^k ≥ ∆^2$. Additionally, it can be readily adapted to a quantum query
algorithm making $\tilde{O}(n^{\frac{k + 3}{k + 2}})$ queries, bypassing the classical lower bound when $C = c∆$ for $c ≫ 1$.
Further, we show that the algorithm presented in Assadi et. al. SODA’19 for ($∆ + 1)$-coloring can be adapted to a quantum algorithm making  $\tilde{O}(n^{4/3})$ queries.
We also show initial upper and lower bounds for the very closely related problem of $\textit{verifying}$
whether or not a given graph coloring is valid.
</details> 

arXiv version slightly outdated, here [arXiv](https://jrexmo.github.io/simple_vertex_color.pdf) is an up to date PDF
[arXiv](https://arxiv.org/abs/2102.07089)
[Poster](https://jrexmo.github.io/Simple_Vertex_coloring_in_the_quantum_query_model__QIP_Poster_.pdf)

