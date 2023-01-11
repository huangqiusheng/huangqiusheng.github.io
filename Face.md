---
layout: page
title: Face editing
permalink: /Face/
---
## Overview
Diverse Image-to-Image Translation (I2IT), characterized with high resolution, diversity, and precise preservation, is amazing but challenging. Traditional methods can generate diverse results of attributes but with limited resolution, while most recent methods exploit pre-trained StyleGAN to achieve high-resolution but have limitations on attribute diversity due to the complicated latent space of the generator. To improve the attribute diversity of StyleGAN-based methods, in this paper, we propose a framework to locate regions corresponding to the same attributes in the latent space and  learn their distributions of diverse directions. In order to locate the diverse results of traditional methods in the latent space of StyleGAN, we first obtain their respective  codes  through inverse mapping. Based on just a few pairs of such samples and codes, we  train a lightweight network to capture the target distribution in the latent space, and propose different pipelines to further refine the results. Experiments in 3D and 2D verify its superiority  in diversity, resolution, and preservation of irrelevant areas. In addition, the proposed pipelines permit to generate segmentation masks of the bangs category for face datasets.

## Results
Face attributes editing (eyeglass)：

<video width="600" height="300" controls >
      <source src="/inversion_3.mp4" type="video/mp4">
</videos>
