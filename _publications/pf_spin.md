---
layout: archive
title: ""
author_profile: true
collection: publications
permalink: /publication/pf_spin
---

## <span style="color:rgb(199, 21, 133)"> Nonlinear Field-split Preconditioners for Solving Monolithic Phase-field Models of Brittle Fracture.</span>
<div style="text-align: justify">One of the state-of-the-art strategies for predicting crack propagation, nucleation, and interaction is the phase-field approach.
Despite its reliability and robustness, the phase-field approach suffers from burdensome computational cost, caused by the non-convexity of the underlying energy functional and a large number of unknowns required to resolve the damage gradients.
In this work, we propose to solve such nonlinear systems in a monolithic manner using the Schwarz preconditioned inexact Newton's (SPIN) method.
The proposed SPIN method leverages the field split approach and minimizes the energy functional separately with respect to displacement and the phase-field, in an additive and multiplicative manner.
In contrast to the standard alternate minimization, the result of this decoupled minimization process is used to construct a preconditioner for a coupled linear system, arising at each Newton's iteration.
The overall performance and the convergence properties of the proposed additive and multiplicative SPIN methods are investigated by means of several numerical examples.
Comparison with widely-used alternate minimization is also performed and we show a reduction in the execution time up to a factor of $50$.
Moreover, we also demonstrate that this reduction grows even further with increasing problem size and larger loading increments.
</div><br />


**Citation:** A. Kopaničáková, H. Kothari, and R. Krause. Nonlinear Field-split Preconditioners for Solving Monolithic Phase-field Models of Brittle Fracture. Under review in Computer Methods in Applied Mechanics and Engineering, 2022. <br />
**Download:** <a href="https://arxiv.org/abs/2203.13738" style="color:rgb(199, 21, 133,0.75);">Preprint.</a> <br />