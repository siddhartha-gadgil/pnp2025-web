---
title: "Homotopy as Path of Paths"
date: 2023-08-23T05:52:22+05:30
draft: false
---

The [Compact-open topology](https://en.wikipedia.org/wiki/Compact-open_topology) is a topology defined on the space $C(X, Y)$ of continuous functions between two topological spaces $X$ and $Y$. The compact-open topology is the topology with sub-basis consisting of sets of the form $$V(K,U) = \\{f: X \to Y: \textrm{$f$ continuous, $f(K)\subset V$}\\},$$ 
where $K$ is a compact subset of $X$ and $U$ is an open subset of $Y$.

In particular, the compact-open topology gives a topology on the space of paths $\Omega(X) = C([0,1], X)$ in a topological space $X$.

1. Show that if $H: [0, 1] \times [0, 1] \to X$ is continuous (i.e., a homotopy), then the map $h: [0, 1] \to C([0, 1], X)$ defined by $h(t)(s) = H(s, t)$ is continuous.

2. Show that if $h: [0, 1] \to C([0, 1], X)$ is continuous, then the map $H: [0, 1] \times [0, 1] \to X$ defined by $H(s, t) = h(t)(s)$ is continuous.

Observe that functions $h: [0, 1]\to C([0, 1], X)$ are functions $h: [0, 1]\to \Omega(X)$ with $h(t)$ the path $h_t: s \mapsto  H(s, t)$.