---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /research
---

Here is some of my work (click for abstract):

Quantum Advantage from Sampling Shallow Circuits: Beyond Hardness of Marginals
https://arxiv.org/abs/2510.07808
<details>
  <summary>1. Quantum Advantage from Sampling Shallow Circuits: Beyond Hardness of Marginals - with Daniel Grier, Daniel Kane, Anthony Ostuni, and Kewen Wu </summary>  
We construct a family of distributions $\{\mathcal{D}_n\}_n$ with $\mathcal{D}_n$ over $\{0, 1\}^n$ and a family of depth-$7$ quantum circuits $\{C_n\}_n$ such that $\mathcal{D}_n$ is produced exactly by $C_n$ with the all zeros state as input, yet any constant-depth classical circuit with bounded fan-in gates evaluated on any binary product distribution has total variation distance $1 - e^{-\Omega(n)}$ from $\mathcal{D}_n$. Moreover, the quantum circuits we construct are geometrically local and use a relatively standard gate set: Hadamard, controlled-phase, CNOT, and Toffoli gates. All previous separations of this type suffer from some undesirable constraint on the classical circuit model or the quantum circuits witnessing the separation.
    
Our family of distributions is inspired by the Parity Halving Problem of Watts, Kothari, Schaeffer, and Tal (STOC, 2019), which built on the work of Bravyi, Gosset, and K\"onig (Science, 2018) to separate shallow quantum and classical circuits for relational problems.

</details> 

[arXiv](https://arxiv.org/abs/2510.07808) 



<details>
  <summary>1. Quantum Threshold is Powerful - with Daniel Grier, CCC 2025 - <span style="color:red">Best Paper Award</span>, TQC 2025 </summary>  
In 2005, Høyer and Špalek showed that constant-depth quantum circuits augmented with multi-qubit Fanout gates are quite powerful, able to compute a wide variety of Boolean functions as well as the quantum Fourier transform. They also asked what other multi-qubit gates could rival Fanout in terms of computational power, and suggested that the quantum Threshold gate might be one such candidate. Threshold is the gate that indicates if the Hamming weight of a classical basis state input is greater than some target value.
We prove that Threshold is indeed powerful--there are polynomial-size constant-depth quantum circuits with Threshold gates that compute Fanout to high fidelity. Our proof is a generalization of a proof by Rosenthal that exponential-size constant-depth circuits with generalized Toffoli gates can compute Fanout. Our construction reveals that other quantum gates able to "weakly approximate" Parity can also be used as substitutes for Fanout.

</details> 

[arXiv](https://arxiv.org/abs/2411.04953) [video](https://www.youtube.com/watch?v=nZ-0kmC9j5U&t=6s)

<details>
  <summary>2. Simple vertex coloring algorithms - with Fang Song, QIP 2021</summary>  
        
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

arXiv version slightly outdated, up to date version [here](https://jrexmo.github.io/simple_vertex_color.pdf)
[arXiv](https://arxiv.org/abs/2102.07089)
[Poster](https://jrexmo.github.io/Simple_Vertex_coloring_in_the_quantum_query_model__QIP_Poster_.pdf)

