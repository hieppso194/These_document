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
  
