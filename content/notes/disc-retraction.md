---
title: "Disc Retraction"
date: 2023-08-24T08:21:06+05:30
---

We sketch here some more details of the construction of a retraction `$\rho: D^2 \to S^1$` from the disc `$D^2$` to the circle `$S^1$` given a map `$f: D^2 \to D^2$` without fixed points. 

#### Geometric construction

1. For a point `$x\in D^2$`, let `$\lambda_x: [0, \infty) \to \mathbb{R}^2$` be the ray from `$f(x)$` through `$x$`, with `$\lambda_x(1)= 1$`.
2. By convexity, for `$\lambda_x(s)\in (0, 1)$`, `$\lambda(s)$` is in interior of the disc `$D^2$`.
3. Hence, there is a unique `$\sigma_x\geq 1$` so that`$\lambda_x(\sigma_x)$` lies on `$S^1$`. 
4. Define `$\rho(x) = \lambda_x(\sigma_x)$`.

#### Algebraic construction

1. Fix `$x\in D^2$`.
2. Define `$\lambda_x: [0, \infty) \to \mathbb{R}^2$` by `$\lambda_x(s) = (1-s)f(x) + sx$`.
3. By convexity, for `$\lambda_x(s)\in (0, 1)$`, `$\Vert\lambda(s)\Vert< 1$`.
4. Consider the equation `$\Vert\lambda_x(s)\Vert^2 = 1$`, i.e., `$\Vert (1-s)f(x) + sx\Vert^2=1$`.
5. This can be written as `$$\Vert x - f(x)\Vert^2 s^2 + 2\langle x - f(x), f(x)\rangle s - (1 - \Vert f(x)\Vert^2) = 0.$$`
which is of the form `$a_xs^2 + b_xs + c_x$ = 0` with `$a_x = \Vert x - f(x)\Vert^2$, $b_x = 2\langle x - f(x), f(x)\rangle$, $c_x = -(1 - \Vert f(x)\Vert^2)$`.
6. As `$f$` has no fixed points, `$a = \Vert x - f(x)\Vert^2 > 0$` for all `$x$`. Thus, the equation is a non-degenerate quadratic equation. Further, by compactness there exists `$\epsilon > 0$` such that `$\Vert x - f(x)\Vert^2 \geq \epsilon$` for all `$x$`. 
7. We will consider the larger real root of this equation. First we establish that there are distinct real roots.
8. The discriminant of the equation is `$$D = D_x = 4\langle x - f(x), f(x)\rangle^2 + 4\Vert x - f(x)\Vert^2(1 - \Vert f(x)\Vert^2)$$`.
9. As `$\Vert f(x)\Vert^2 \leq 1 1$`, both the terms of `$D$` are non-negative. Hence, `$D\geq 0$`.
10. Further, if `$D=0$`, then `$\langle x - f(x), f(x)\rangle = 0$` and `$\Vert f(x)\Vert^2 = 1$`. We deduce (by Pythagoras theorem or properties of inner products) that `$\Vert x\Vert^2 = \Vert f(x)\Vert^2 + \Vert x - f(x)\Vert^2 > 1 + \epsilon$`, which is a contradiction as `$x \in D^2$`.
11. We can thus define `$\sigma_x$` to be the larger real root of the equation `$\Vert\lambda_x(s)\Vert^2 = 1$` using the quadratic equation solution formula `$$\sigma_x = \frac{-b_x + \sqrt{D_x}}{2a_x}.$$`

12. This is continuous as both the denominator and the term under the square root are positive.
13. Define `$\rho(x) = \lambda_x(\sigma_x)$`. This is a composition of continuous functions and hence continuous.
14. By construction of `$\sigma_x$`, `$\rho(x)\in S^1$` for all `$x\in D^2$`.
15. Finally, if `$x\in S^1$`, then `$\sigma_x = 1$` as `$1$` is a root of the equation, and hence the unique root that is at least `$1$`. Hence, `$\rho(x) = x$` for all `$x\in S^1$`.