# URCA: 3D video & 3D performance capture virtual & augmented Reality
The big task is data processing from data from unreliable sources.

## The problem:
- Due to using cheap and easy-to-use systems, such as depth cameras, it is quite 
difficult to capture the styles on site, such as: calibration, sensor positioning. I need answer:
  + Why is it difficult to capture?
  + How about the data from easy-to-use systems?

. Hence, my tasks aim at developing innovative approaches to make a 
system be available for normal users and helping them to capture the styles.
Besides, it is hoped that future users can experiment this dance in our equipment
as if being presented by particular dancer. Our proposed method would be based
on the previous works at UR2 and URCA. They uses the data from several sources, such as: raw depth images, RGB images and reconstructed skeleton data delivered by one or a set of depth cameras. I need understand:

  + What are the previous works? How to apply it to our work?

- Besides, another big question:

  + Which are the requirements of outputed data from the raw data after being processed?

There are some sub-tasks:
- develop new approaches to fuse between the various available information and previously collected data. it
aims at correcting the inaccurate data from the depth cameras. And then we will be able to adapt the
resulting data to compatible with the DanceDB database, also used in the other WPS. The big question here is :

  + What is the requirements of data in the task and the quality of DanceDB database'
  
- explore multi-Kinect capture by designing a simple calibration method and fusion of information
- enrich partial data by using priors existing data from the dance DB 
- build a large set of experiments with APs can enable to evaluate the weakness of th resulting system. From those, backwards of the resulting system
can be reveals and we can specific the specification to other tasks
- exploit the avaibility of additional data, such as the surface information and RGB images. Besides address the complexity of the dancing motion. Key tool: the 
example-based Kinect data correction developed in UR2
- enrich that database to correct unreliable data by asking colloborating with expert
dancers
- generate representative geometric models with their associated skeletal representation from above data
- find the best-fitted geometric model (what is the best one) to match multi-kinect
data
- improve the positioning accuracy of the skeleton
- evaluation step by users, especially expert dancers.

## Key word
- depth cameras
[An overview of depth sensors](https://blog.cometlabs.io/depth-sensors-are-the-key-to-unlocking-next-level-computer-vision-applications-3499533d3246)
- previous task in UR2 and URCA.
[Thesis of Ludovic](../documents/reference_thesis/45687_BLACHE_2016_archivage.pdf)

