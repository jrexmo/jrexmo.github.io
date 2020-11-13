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
  <summary>1. Vertex coloring and related problems in the quantum query model - 2020, with Fang Song</summary>  
        
   
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
  \begin{math}
   
  \end{math}
  The main result of this paper is a quantum algorithm in the query
  model that bypasses the classical lower bound. Specifically for any
  $\delta > 0$ satisfying $\delta^{-1} = O(1)$, our algorithm makes
  $\tilde{O}(\epsilon^{-3/2}n^{4/3 + \delta/2})$ quantum queries and
  returns a valid $(1 + \epsilon)\Delta$-coloring with high
  probability. By similar techniques, we also give a quantum algorithm form
  maximal-matching in the quantum query model that makes
  $\tilde{O}(n^{3/2 + \delta/2})$ queries, bypassing the classical lower
  bound $\Omega(n^2)$. Complementary to these algorithmic results, we
  prove quantum lower bounds of $\Omega(n)$ for both
  $2\Delta$-coloring and maximal matching.
     
</details>
{% include base_path %}

