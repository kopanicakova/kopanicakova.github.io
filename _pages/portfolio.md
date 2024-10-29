---
layout: archive
title: ""
permalink: /portfolio/
author_profile: true
---

## <span style="color:rgb(199, 21, 133)"> Multilevel training methods</span>
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

<div style="text-align: justify"><br/> Deep neural networks (DNNs) suffer from a computationally exhaustive training phase, which limits their applicability and hinders their development. During the training phase, the parameters of the network are determined by minimizing a highly non-convex loss function. My research objective is to enhance the training of DNNs by leveraging multilevel and domain-decomposition techniques. This entails developing novel optimization methods, which perform well in large-scale stochastic settings. Thus, developing methods thus which are memory and computationally efficient and convergence of which does not deteriorate in the presence of sub-sampling noise. Moreover, it is important to devise suitable strategies for constructing the multilevel hierarchy. This can be achieved by exploring the structure of the network's architecture, data representation, and the properties of the loss function. </div>
</body>


## <span style="color:rgb(199, 21, 133)"> Nonlinear preconditioning</span>
<head>
<style>
#wrapper_top {
	 display: flex;
}
#wrapper {
	 
}
#picture_half {
    display: inline-block;
    width:50%;
    height:auto;
}
#picture_half2 {
    display: inline-block;
    width:30%;
    height:auto;
}
#div_space {
    display: inline-block;
    width:20%;
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
	    <div id="picture_half2">  
	    	<img src="/images/dd_constraints.png">
	    </div>
	</div>

<div style="text-align: justify"><br/> 
Nonlinear field-split or domain-decomposition preconditioners enable an efficient solution of large-scale nonlinear
multi-physics problems. The idea behind these methods is to enhance the convergence of nonlinear solution strategies by rebalancing the nonlinearities, or by transforming the basis of the solution space. This can be achieved by decomposing either the computational domain or the physics of the coupled problems. Former is of particular interest in the field of scientific computing, as it allows for massive parallelization. My research goal is to enhance the class of nonlinear preconditioners by proposing novel algorithmic variants and by extending the applicability of existent approaches to a wider range of nonlinear problems. </div>
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
</body>



## <span style="color:rgb(199, 21, 133)"> Scientific software</span>
<body>	
<div style="text-align: justify">
I actively contribute to the development of scientific software libraries with a particular focus on the development of large-scale, parallel nonlinear optimization strategies and simulation frameworks.</div>

<span style="color:rgb(199, 21, 133, 0.75); font-size: 14px"> Software libraries: </span><br />
<span style="font-size: 12px">
<b> Utopia: </b> Open-source C++ embedded domain specific language designed for parallel nonlinear solution strategies and finite element analysis. <a href="https://bitbucket.org/zulianp/utopia/src/master/" style="color:rgb(199, 21,133,0.75);">Code repository.</a> (Core developer) <br />
<b> ROOK: </b> Large-scale finite-element framework for (pressure-induced) phase-field fracture
simulations. (Solo developer) <br />
<b> MultiscAI: </b> Stochastic multilevel optimization framework for training ODE-based deep neural
networks. (Solo developer) <br />
<b> DistTraiNN: </b> Model parallel framework for distributed training of deep neural networks (Core developer) <br />
<b> Heart: </b> Parallel framework for inverse problems in electrophysiology. (Contributor)<br />
</span>
</body>


