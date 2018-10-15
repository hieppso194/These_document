Summary of thesis:
- 3D multi-view reconstruction: there are main steps in this project:
  + Extract the template mesh from the first post (t = 1) of the input sequence
  + Compute the Poisson disk sampling on the template mesh
  + Comput EDT grids from t -> t+1
  + Compute the motion flow from t -> t+1
  + select anchor vertices
  + global deformation of the mesh
  + local optimization


Papers:
  + Surface based Motion Retargeting by Preserving Spatial Relationship
    - Based on source character to retarget to target character of our project. The constraint is preserving spatial relationship of these characters
  + Filtered pose graph for efficient kinect pose reconstruction. The main idea is that to correct reconstructed skeleton data
  based on a database of accurately captured human poses:
    - A filted pose graph structure
    - A customized search algorithm
   
  
