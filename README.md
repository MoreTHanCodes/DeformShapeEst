Robust Shape Estimation for 3D Deformable Object Manipulation
======

<p align="center">
  <b>Tao Han, Xuan Zhao, Peigen Sun and <a href="https://sites.google.com/site/panjia/">Jia Pan</a></b>
</p>
<p align="center">
  <b><a href="https://www.cityu.edu.hk/">City University of Hong Kong</a></b>
</p>

## Abstract
Existing shape estimation methods for deformable object manipulation suffer from the drawbacks of being off-line, model dependent, noise-sensitive or occlusion-sensitive, and thus are not appropriate for manipulation tasks requiring high precision. In this paper, we present a real-time shape estimation approach for autonomous robotic manipulation of 3D deformable objects. Our method fulfills all the requirements necessary for the high-quality deformable object manipulation in terms of being real-time, model-free and robust to noise and occlusion. These advantages are accomplished using a joint tracking and reconstruction framework, in which we track the object deformation by aligning a reference shape model with the stream input from the RGB-D camera, and simultaneously upgrade the reference shape model according to the newly captured RGB-D data. We have evaluated the quality and robustness of our real-time shape estimation pipeline on a set of deformable manipulation tasks implemented on physical robots.

![][overview]
**Figure 1.** Overview of our shape estimation pipeline for deformable object manipulation. **Top row** is the entire control loop for deformable object manipulation. In this work, we focus on solving the shape estimation problem, as highlighted in the red-dashed box. An ideal shape estimation approach should fulfill the requirements of being real-time, model-free and robust to noise and occlusion. **Bottom row** illustrates the pipeline of our shape estimation system. Our system takes the frame sequence captured by a RGB-D camera as input. It is composed of two parallel threads, namely, *tracking* and *reconstruction*. These two threads estimate and update the deformation model and the shape model iteratively when new RGB-D frames are streaming into the system.

## Results

### Robustness to Noise
<iframe width="560" height="315" src="https://www.youtube.com/embed/IIMSPutWoto" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### Robustness to Occlusion

### Comparison with Single-frame Method for Feature Tracking

------
[overview]:img/overview.png
