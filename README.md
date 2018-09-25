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

<p align="center">
    <img src="img/overview.png" width="640" />
    <em>Figure 1. Overview of our shape estimation pipeline for deformable object manipulation.</em>
</p>


## Results

### Robustness to Noise
<iframe width="560" height="315" src="https://www.youtube.com/embed/IIMSPutWoto" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### Robustness to Occlusion
<iframe width="560" height="315" src="https://www.youtube.com/embed/nMKR7jPg6Oo" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/RiI5hOdgblw" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### Comparison with Single-frame Method for Feature Tracking
<iframe width="560" height="315" src="https://www.youtube.com/embed/XckgE5wMhI8" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

------
