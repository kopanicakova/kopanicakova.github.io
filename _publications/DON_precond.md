---
layout: archive
title: ""
author_profile: true
collection: publications
permalink: /publication/DON_precond
---

## <span style="color:rgb(199, 21, 133)"> DeepONet Based Preconditioning Strategies for Solving Parametric Linear Systems of Equations. </span>
<div style="text-align: justify">We introduce a new class of hybrid preconditioners for solving parametric linear systems of equations. The proposed preconditioners are constructed by hybridizing the deep operator network, namely DeepONet, with standard iterative methods. Exploiting the spectral bias, DeepONet-based components are harnessed to address low-frequency error components, while conventional iterative methods are employed to mitigate high-frequency error components. Our preconditioning framework comprises two distinct hybridization approaches: direct preconditioning (DP)
and trunk basis (TB) approaches. In the DP approach, DeepONet is used to approximate an action
of an inverse operator to a vector during each preconditioning step. In contrast, the TB approach
extracts basis functions from the trained DeepONet to construct a map to a smaller subspace, in
which the low-frequency component of the error can be effectively eliminated. Our numerical results
demonstrate that utilizing the TB approach enhances the convergence of Krylov methods by a large
margin compared to standard non-hybrid preconditioning strategies. Moreover, the proposed hybrid
preconditioners exhibit robustness across a wide range of model parameters and problem resolutions.
</div><br />


**Citation:** A. Kopaničáková, and G. Karniadakis. DEEPONET BASED PRECONDITIONING STRATEGIES FOR
SOLVING PARAMETRIC LINEAR SYSTEMS OF EQUATIONS. arXiv:2401.02016, 2023.  <br />
**Download:** <a href="https://arxiv.org/pdf/2401.02016.pdf" style="color:rgb(199, 21, 133,0.75);">Preprint.</a> <br />


