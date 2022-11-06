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
        
   
  Given a graph $G$ with $n$ vertices and maximum degree $\Delta$, it
  is known that $G$ admits a vertex coloring with $\Delta + 1$ colors
  such that no edge of $G$ is monochromatic. This can be seen
  constructively by a simple greedy algorithm, which runs in time
  $O(n\Delta)$. Very recently, [Assdi et. al. SODA'19] presents a
  randomized algorithm for $\Delta + 1$-coloring in the query model
  making $\tilde{O}(n\sqrt{n})$ queries, improving over the greedy
  strategy. In addition, a lower bound of $\Omega(n\sqrt n)$ for any
  $O(\Delta)$-coloring, including $\Delta + 1$-coloring, is
  established on general graphs.
  In this work, we give a simple algorithm for $(1+ϵ)Δ$-coloring. This
  algorithm makes $O(\epsilon^{−1/2}n\sqrt{n})$ queries, which matches
  the best existing algorithms as well as the classical lower bound for
  sufficiently large $\epsilon$. Additionally, it can be readily adapted
  to a quantum query algorithm making $\tilde{O}(\epsilon^{-1}n^{4/3})$
  queries, bypassing the classical lower bound. Complementary to these
  algorithmic results, we show a quantum lower bound of $\Omega(n)$
  for $O(\Delta)$-coloring.
     
</details> 

[arXiv](https://arxiv.org/abs/2102.07089)
[Poster Here](https://jrexmo.github.io/Simple_Vertex_coloring_in_the_quantum_query_model__QIP_Poster_.pdf)
{% include base_path %}

