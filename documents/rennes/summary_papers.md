# Comparison about techniques used in markerless approaches used in the motion capturing (or tracking) problem

| Features  	| The machine learning based methods     	       | Registration based methods                              |    
| ---------- 	| ---------------------------------------------  | ------------------------------------------------------  |
| Definition  | They usually formulate the pose tracking    	 | They use templates to represent the tracked objects and 
|		          | problem as a per-pixel labelling problem and   |attempt to align the templates with the observed data by | minimizing certain   |
|		| solve it by applying some classification framw |energy functions						        |
|		|- Some approaches applied: Gaussian Process,	 |- The templates care be articulated simple objects or triangular      | 
|		|Markov Random Fields, Markov Chain Monte Carlo, |meshes. The first one don't capture the geometry details of the       |
|		|, randomized decision tree			 |tracked objects thus limit motion tracjing accuracy. The later capture|
|		|						 |the geometry details better, but computing the deformation of 	|
|		|						 |triangular meshes is time-consuming. Besides, there are also methods  |
|		|						 |using cylinders attached with isotropic Gaussian functions to approxi |
|		|						 | the geometry of tracked object. Another method is using spherical    |
|		|						 | harmonics functions equipped ellipsoids 				|
|-------------- |----------------------------------------------- | -------------------------------------------------------------------- |
| Limitations   | - Require large and comprehensive traning data | 									|
|		| sets						 |									|
| ------------- | ---------------------------------------------  | -------------------------------------------------------------------  |				
| Advantages    | - Computation time for them is usually short   | - no need large and comprehensive traning data sets			|
|		| and with small variance 			 |									|
