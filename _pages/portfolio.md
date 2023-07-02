---
layout: archive
title: ""
permalink: /portfolio/
author_profile: true
---

## <span style="color:rgb(199, 21, 133)"> Multilevel and domain-decomposition based training methods</span>
<head>
<style>
#wrapper_top {
	 display: flex;
}
#wrapper {
	 
}
#picture_half {
    display: inline-block;
    width:47%;
    height:auto;
}
#div_space {
    display: inline-block;
    width:4%;
    height:auto;
}
</style>
</head>
<body>	
	<div id="wrapper_top">
	    <div id="picture_half">  
	    	<img src="/images/resnet1.png">
	    </div>
		<div id="div_space"></div>    
	    <div id="picture_half">  
	    	<br/>
	    	 <img src="/images/resnet2.png">
	    </div>
	</div>

<div style="text-align: justify"><br/> Deep neural networks (DNNs) suffer from a computationally exhaustive training phase, which limits their applicability and hinders their development. During the training phase, the parameters of the network are determined by minimizing a highly non-convex loss function. My research objective is to enhance the training of DNNs by leveraging multilevel and domain-decomposition techniques. This entails developing novel optimization methods, which perform well in large-scale stochastic settings, thus which are memory and computationally efficient and convergence of which does not deteriorate in the presence of sub-sampling noise. Moreover, it is important to devise novel strategies for constructing the multilevel hierarchy and for partitioning the parameter/data space. This can be achieved by exploring the structure of the network's architecture, data representation, and the properties of the loss function. </div>


<span style="color:rgb(199, 21, 133, 0.75); font-size: 14px"> Related references: </span><br />
<span style="font-size: 12px">
[1] A. Kopaničáková, H. Kothari, G. Karniadakis and R. Krause. Enhancing training of physics-informed neural networks using domain-decomposition based preconditioning strategies. <br />	
[2] S. Gratton, A. Kopaničáková and Ph. L. Toint. Multilevel Objective-Function-Free Optimization with an Application to Neural Networks Training. <br />
[3] A. Kopaničáková and R. Krause. Globally Convergent Multilevel Training of Deep Residual Networks. <br />
[4] L. Gaedke-Merzhauser*, A. Kopaničáková*, and R. Krause. Multilevel minimization for deep residual networks. <br />
[5] C. von Planta, A. Kopaničáková, and R. Krause. Training of residual networks with stochastic MG/Opt. <br />
[6] V. Braglia*, A. Kopaničáková*, and R. Krause. A multilevel approach to training. <br />
</span>
</body>


## <span style="color:rgb(199, 21, 133)"> Nonlinear field-split and domain-decomposition based preconditioning</span>
<head>
<style>
#wrapper_top {
	 display: flex;
}
#wrapper {
	 
}
#picture_half {
    display: inline-block;
    width:47%;
    height:auto;
}
#div_space {
    display: inline-block;
    width:4%;
    height:auto;
}
</style>
</head>
<body>	
	<div id="wrapper_top">
	    <div id="picture_half">  
	    	<img src="/images/network_decomp.png">
	    </div>
		<div id="div_space"></div>    
	    <div id="picture_half">  
	    	<img src="/images/dd_constraints.png">
	    </div>
	</div>

<div style="text-align: justify"><br/> 
Nonlinear field-split or domain-decomposition preconditioners enable an efficient solution of large-scale nonlinear
multi-physics problems arising from finite element or finite difference discretization of nonlinear PDEs.
These methods enhance the convergence of nonlinear solution strategies by rebalancing the nonlinearities, or by transforming the basis of the solution space. This is achieved by decomposing either the computational domain or the physics of the coupled problems. Former is of particular interest in the field of scientific computing, as they allow for massive parallelization. My research goal is to enhance the class of nonlinear preconditioners by proposing novel algorithmic variants and by extending applicability of existent approaches to a wider range of nonlinear problems.</div>


<span style="color:rgb(199, 21, 133, 0.75); font-size: 14px"> Related references: </span><br />
<span style="font-size: 12px">
[1] A. Kopaničáková, H. Kothari, G. Karniadakis and R. Krause. Enhancing training of physics-informed neural networks using domain-decomposition based preconditioning strategies. <br />		
[2] H. Kothari, A. Kopaničáková and R. Krause. Nonlinear Schwarz preconditioning for nonlinear optimization problems with bound constraints. <br />		
[3] A. Kopaničáková, H. Kothari, and R. Krause. Nonlinear Field-split Preconditioners for Solving Monolithic Phase-field Models of Brittle Fracture. <br />
[4] C. Bilgen, A. Kopaničáková, R. Krause, and K. Weinberg. A detailed investigation of the model influencing parameters of the phase-field fracture approach.<br />
</span>	
</body>



## <span style="color:rgb(199, 21, 133)"> Multilevel trust-region methods</span>
<head>
<style>
#wrapper_top {
	 display: flex;
}
#wrapper {
	 
}
#picture_half {
    display: inline-block;
    width:47%;
    height:auto;
}
#div_space {
    display: inline-block;
    width:2%;
    height:auto;
}
</style>
</head>
<body>	
	<div id="wrapper_top">
	    <div id="picture_half">  
	    	<img src="/images/rmtr.png">
	    </div>
		<div id="div_space"></div>    
	    <div id="picture_half">  
	    	<img src="/images/rmtr2.png">
	    </div>
	</div>

<div style="text-align: justify"><br/> 
Multilevel methods have been originally designed for solving elliptic partial differential equations. Their applicability to non-convex optimization problems was extended by utilizing the trust-region globalization strategy, giving rise to recursive multilevel trust-region methods (RMTR) [Gratton et al. ’08]. I have contributed to the development of RMTR methods by proposing several novel variants that take into account the structure of the underlying optimization problem in order to construct multilevel hierarchy and transfer operators. These methods are unique as they allow for the solution of complex non-convex minimization problems with multigrid efficiency. Moreover, they are also provably globally convergent, thus guaranteeing the success of the nonlinear iteration process.</div>


<span style="color:rgb(199, 21, 133, 0.75); font-size: 14px"> Related references: </span><br />
<span style="font-size: 12px">
[1] S. Gratton, A. Kopaničáková and Ph. L. Toint. Multilevel Objective-Function-Free Optimization with an Application to Neural Networks Training. <br />	
[2] A. Kopaničáková. On the use of hybrid coarse-level models in multilevel minimization methods. <br />	
[3] A. Kopaničáková and R. Krause. Globally Convergent Multilevel Training of Deep Residual Networks. <br />
[4] F. Chegini, A. Kopaničáková, R. Krause, and M. Weiser. Efficient identification of scars using heterogeneous model hierarchies. <br />
[5] A. Kopaničáková and R. Krause. Recursive multilevel trust region method with application to fully monolithic phase-field models of brittle fracture. <br />
[6] A. Kopaničáková, R. Krause, and R. Tamstorf. Subdivision-based nonlinear multiscale cloth simulation. <br />
[7] F. Chegini, A. Kopaničáková, M. Weiser, and R. Krause. Quantitative analysis of nonlinear multifidelity optimization for inverse electrophysiology. <br />
[8] A. Kopaničáková and R. Krause. Multilevel Active-Set Trust-Region (MASTR) Method for Bound Constrained Minimization. <br />
</span>	
</body>






## <span style="color:rgb(199, 21, 133)"> Large-scale phase-field fracture simulations</span>
<head>
<style>
#wrapper_top {
	 display: flex;
}
#wrapper {
	 
}
#picture_half {
    display: inline-block;
    width:47%;
    height:auto;
}
#div_space {
    display: inline-block;
    width:4%;
    height:auto;
}
</style>
</head>
<body>	
	<div id="wrapper_top1">
	    <div id="picture_half">  
	    	<img src="/images/frac_net1.png">
	    </div>
		<div id="div_space"></div>    
	    <div id="picture_half">  
	    	<img src="/images/frac_net2.png">
	    </div>
	</div>
<div style="text-align: justify"><br/>  Predicting damage and crack propagation is a long-lasting challenge in computational mechanics. The phase-field approach to fracture allows for predicting crack evolution without the need to explicitly model crack paths and therefore has become very popular. The development of an efficient phase-field fracture simulation framework requires scalable implementation of an underlying mathematical model and robust solution strategy. I have contributed to both aspects by implementing the finite-element phase-field fracture models and by proposing novel solution strategies for solving arising non-convex coupled constrained minimization problems. The developed simulation framework has been used to simulate brittle, conchoidal, and pneumatic fractures. More recently, it has been also employed for pressure-induced fracture propagation of stochastic fracture networks in 2D/3D, considering realistic scenarios with up to 1 000 fractures.</div>


<span style="color:rgb(199, 21, 133, 0.75); font-size: 14px"> Related references: </span><br />
<span style="font-size: 12px">
[1] A. Kopaničáková, H. Kothari, and R. Krause. Nonlinear Field-split Preconditioners for Solving Monolithic Phase-field Models of Brittle Fracture. <br />
[2] C. Bilgen, A. Kopaničáková, R. Krause, and K. Weinberg. A phase-field approach to pneumatic fracture. <br />	
[3] P. Zulian*, A. Kopaničáková* et al. Large scale simulation of pressure induced phase-field fracture propagation using Utopia.<br />
[4] C. Bilgen, A. Kopaničáková, R. Krause, and K. Weinberg. A detailed investigation of the model influencing parameters of the phase-field fracture approach.<br />
[5] A. Kopaničáková and R. Krause. Recursive multilevel trust region method with application to fully monolithic phase-field models of brittle fracture. <br />
[6] C. Bilgen, A. Kopaničáková, R. Krause, and K. Weinberg. A phase-field approach to conchoidal fracture. <br />
[7] C. Bilgen, A. Kopaničáková, R. Krause, and K. Weinberg. A phase-field approach to pneumatic fracture. <br />
</span>
</body>



## <span style="color:rgb(199, 21, 133)"> Scientific software</span>
<head>
<style>
#wrapper_top {
	 display: flex;
}
#wrapper {
	 
}
#picture_half {
    display: inline-block;
    width:47%;
    height:auto;
}
#div_space {
    display: inline-block;
    width:4%;
    height:auto;
}
</style>
</head>
<body>	
	<!-- <div id="wrapper_top1">
	    <div id="picture_half">  
	    	<img src="/images/frac_net1.png">
	    </div>
		<div id="div_space"></div>    
	    <div id="picture_half">  
	    	<img src="/images/frac_net2.png">
	    </div>
	</div> -->
<div style="text-align: justify">
<!-- <br/>  -->
I actively contribute to the development of scientific software libraries with a particular focus on the development of large-scale, parallel simulations, and efficient nonlinear optimization strategies.</div>


<span style="color:rgb(199, 21, 133, 0.75); font-size: 14px"> Software libraries: </span><br />
<span style="font-size: 12px">
<b> Utopia: </b> Open-source C++ embedded domain specific language designed for parallel nonlinear solution strategies and finite element analysis. <a href="https://bitbucket.org/zulianp/utopia/src/master/" style="color:rgb(199, 21,133,0.75);">Code repository.</a> (Core developer) <br />
<b> ROOK: </b> Large-scale finite-element framework for (pressure-induced) phase-field fracture
simulations. (Solo developer) <br />
<b> MultiscAI: </b> Stochastic multilevel optimization framework for training ODE-based deep neural
networks. (Solo developer) <br />
<b> DistTraiNN: </b> Model parallel framework for distributed training of deep neural network (Core developer) <br />
<b> Heart: </b> Parallel framework for inverse problems in electrophysiology. (Contributor)<br />
</span>
</body>

