---
layout: archive
title: ""
author_profile: true
collection: publications
permalink: /publication/pf_utopia
---

## <span style="color:rgb(199, 21, 133)"> Large scale simulation of pressure induced phase-field fracture propagation using Utopia.</span>
<div style="text-align: justify">Non-linear phase field models are increasingly used for the simulation of fracture propagation problems. The numerical simulation of fracture networks of realistic size requires the efficient parallel solution of large coupled non-linear systems. Although in principle efficient iterative multi-level methods for these types of problems are available, they are not widely used in practice due to the complexity of their parallel implementation.
Here, we present Utopia, which is an open-source C++ library for parallel non-linear multilevel solution strategies. Utopia provides the advantages of high-level programming interfaces while at the same time a framework to access low-level data-structures without breaking code encapsulation.
Complex numerical procedures can be expressed with few lines of code, and evaluated by different implementations, libraries, or computing hardware.
In this paper, we investigate the parallel performance of our implementation of the recursive multilevel trust-region (RMTR) method based on the Utopia library.
RMTR is a globally convergent multilevel solution strategy designed to solve non-convex constrained minimization problems.
In particular, we solve pressure-induced phase-field fracture propagation in large and complex fracture networks.
Solving such problems is deemed challenging even for a few fractures, however, here we are considering networks of realistic size with up to 1000 fractures.
</div><br />


**Citation:** P. Zulian\*, A. Kopaničáková\*, M. G. C. Nestola, N. Fadel, A. Fink, J. VandeVondele, and R. Krause. Large scale simulation of pressure induced phase-field fracture propagation using Utopia. CCF Transactions on High Performance Computing, 2021.(\* Equal contribution) <br />
**Download:** <a href="https://doi.org/10.1007/s42514-021-00069-6" style="color:rgb(199, 21, 133,0.75);">Link to published article.</a> <br />
