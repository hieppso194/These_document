# multi cam topology:
- calibration
- cross pertubation
- synchnization
- multi computer
+ fusion data
+ less occlusion
+ skeleton

# motion capture clean-up (noisy, occuusion, unlabelled)
- about denoise, machine learning maybe the good ideao

# Openpose

# raw data cleanup
raw data (C3D unlabelled, noise, occlustio) -> NN -> true label

# Whole process
motion capture: capture all markers of each fream
skeleton fitting
2-cycles looping
retargeting on model: skinning, blenning from 1 character to another character

Jinxiang Chai
# Todolst
- make a short presentation about the papers: chai, multi kinect topology

# 1 kinect topology
- Due to the disadvantages of multi kinect topology (mentioned above), 1 kinect 
topology can be used but it is bad for bad side, we can propose some approaches
to solve it:
+ Brainstorming: We have the dance database, for some motions(such as turn 
around) we can learn from the db to produce the interpolation of missing 
points from the frames of front side (because the time of these motions is
not too big): such as at t-1 and t+1 the character in front of kinect and he back
to the kinect at t, we can predict him from frame t-1 and t+1 by interpolating
(can use ML from dance db)

# Calibration
- cyclic motion -> average depth cycle -> reduce noise
- 3D pose database with surface -> simulated depth image; reliability, bad reliability
-> optimal combination of examples (surface)-> increase quality of depth image + getting the angle
- traching a shape + skeleton on reliable depth infromation, Inverse kinematic (IK)
to solve the over constrained problem -> (chai paper)[https://ieeexplore.ieee.org/document/7390092]
