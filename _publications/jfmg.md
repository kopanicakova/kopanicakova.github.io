---
layout: archive
title: ""
author_profile: true
collection: publications
permalink: /publication/jfmg
---

## <span style="color:rgb(199, 21, 133)"> A Matrix-free Multigrid Preconditioner for Jacobian-free Newton-Krylov Methods. </span>
<div style="text-align: justify">In this work, we propose a multigrid preconditioner for Jacobian-free Newton-Krylov (JFNK) methods. Our multigrid method does not require knowledge of the Jacobian at any level of the multigrid hierarchy. As it is common in standard multigrid methods, the proposed method also relies on three building blocks: transfer operators, smoothers, and a coarse level solver. In addition to the restriction and prolongation operator, we also use a projection operator to transfer the current Newton iterate to a coarser level. The three-level Chebyshev semi-iterative method is employed as a smoother, as it has good smoothing properties and does not require the representation of the Jacobian matrix. We replace the direct solver on the coarsest-level with a matrix-free Krylov subspace method, thus giving rise to a truly Jacobian-free multigrid preconditioner. We will discuss all building blocks of our multigrid preconditioner in detail and demonstrate the robustness and the efficiency of the proposed method using several numerical examples.
</div><br />


**Citation:** H. Kothari, A. Kopaničáková, and R. Krause. A Matrix-free Multigrid Preconditioner for Jacobian-free Newton-Krylov Methods. In: Brenner, S.C., Chung, E., Klawonn, A., Kwok, F., Xu, J., Zou, J. (eds) Domain Decomposition Methods in Science and Engineering XXVI. Lecture Notes in Computational Science and Engineering, vol 145. Springer, Cham. https://doi.org/10.1007/978-3-030-95025-5_38. 2022. <br />
**Download:** <a href="https://arxiv.org/abs/2203.13738" style="color:rgb(199, 21, 133,0.75);"> Preprint.</a> <br />







