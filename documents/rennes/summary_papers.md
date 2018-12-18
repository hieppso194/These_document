# Comparison about techniques used in markerless approaches used in the motion capturing (or tracking) problem
## The machine learning based methods
- They usually formulate the pose tracking problem as  per-pixel labelling problem and solve it by applying some classification frameworks.
- Several probabilistic models have been applied, including the Gaussian Process (GP), Markov Random Fields (MRFs), Markov Chain Monte Carlo (MCMC), and randomized decision tree.
- The computation time for such kind of methods is usually short and with small variance, but the disadvantage is that
without large and comprehensive training data sets these methods may fail.
## Registration based methods
- The registration based methods use templates to repre-sent the tracked objects and attempt to align the templates with the observed data by minimizing certain energy functions.
- The templates here can be articulated simple objects or triangular meshes.
- Besides, there are also methods using cylinders attached with isotropic Gaussian functions to approximate the geometry of tracked object. Another method is using spherical harmonics functions equipped ellipsoids.


- read papers: 6,7 
- About datasets: Berkeley Multimodal Human Action Database (MHAD) (here)[http://tele-immersion.citris-uc.org/berkeley mhad/]
