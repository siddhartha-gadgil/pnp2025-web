---
title: "Strange Covers"
date: 2023-11-02T08:37:44+05:30
draft: false
---

Let `$Z$` be the closed _topologists sine curve_ `$$Z=\left\{(x, y) \in \R^2: 0< x \leq 1, y = sin(\frac{2\pi}{x})\right\} \cup \left\{(0, y)\in \R^2 : -1\leq y\leq 1\right\}.$$` Let `$X$` be the quotient of `$Z$` obtained by identifying the points `$(0, 0)\in Z$` and `$(1, 0)\in Z$`. Let `$$\widetilde{X} = \bigcup_{n\in\Z}\left\{(x + n, y): (x, y)\in Z\right\}.$$`

1. Show that `$X$` is path-connected but not locally path-connected.
2. Show that the fundamental group of `$X$` is trivial.
3. Define a function `$g: Z \to S^1$` by `$g(x, y) = e^{2\pi ix}$` for all `$(x, y)\in Z$`. Show that `$g$` induces a well-defined quotient function `$f: X \to S^1$`.
4. Let `$p_{S^1}: \R \to S^1$` be the universal covering map `$p_{S^1}(t)= e^{2\pi i t}$`. Show that there __does not exist__ a map `$F: X \to \R$` such that `$f = p_{S^1} \circ F$`.
5. Show that `$\widetilde{X}$` is connected.
6. Show that there is a covering map `$p: \widetilde{X} \to X$`.
7. Show that if `$\widehat{p}: \widehat{X} \to X$` is a covering map and `$\widehat{X}$` is connected, then there is a covering map `$\widehat{p}':\widetilde{X} \to \widehat{X}$` with `$p = \widehat{p} \circ \widehat{p}'$`.