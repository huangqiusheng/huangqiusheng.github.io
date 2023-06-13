---
layout: page
title: 3D reconstruction (CaRecon)
permalink: /CaRecon/
---

## Overview
Multi-view reconstruction of real-world objects is essential for various applications, such as autonomous driving and virtual reality. However, the inaccurate annotations, camera parameter deviations, and lens distortions in real-world data often pose significant challenges to the reconstruction quality. Synthetic datasets provide accurate annotations and pose a more manageable reconstruction problem, but they lack the realistic style of real-world objects. Further, most existing methods for categorical reconstruction, where a network is trained to reconstruct all instances of an object category, can only handle synthetic data.
In this paper, we propose a novel pipline to address the challenge of categorical reconstruction of real-world objects under wild conditions. Our approach leverages a camera pose refinement technique and the compensation code in signed distance function (SDF) to handle uncontrolled camera settings and inaccurate annotations. We also introduce a multi-resolution tri-planes LOD network architecture to achieve accurate categorical reconstruction.
We evaluate our approach on the Multi-View Major Car (MVMC) dataset, which contains a limited number of real-world car instances with imprecise annotations. Experimental results show the effectiveness of our approach for the reconstruction of objects under difficult conditions. The proposed pipeline can handle real-world datasets without accurate pose and mask annotations, achieving accurate categorical reconstruction with state-of-the-art performance.
![test](/CaRecon.png)

## Results

<video width="600" height="300" controls >
      <source src="/nuScenes.mp4" type="video/mp4">
</videos>

CO3D(origin):
<video width="600" height="300" controls >
      <source src="/co3d.mp4" type="video/mp4">
</videos>

CO3D(unsupervised pose alignment reconstruction):
<video width="600" height="300" controls >
      <source src="/co3d_2.mp4" type="video/mp4">
</videos>