---
title: "Unsupervised Optical Flow Estimation with temporal smoothing"
excerpt: "Machine Learning for Engineers course project, Carnegie Mellon University"
header:
        teaser: unsup_temporal_loss.png
permalink: /projects/05_temp_loss_ml
collection: projects
---
Advisor: Prof. Amir Barati Farimani, Mechanical Engineering, Carnegie Mellon University
### System Overview:
![System Overview](/images/temp_loss_arch.png)
* Designed an unsupervised version of the Flownet-C architecture for optical flow estimation
* Formulated a temporal smoothing loss term which penalizes large changes in consecutive optical flow maps
* Generated temporally smoother optical flow maps producing more temporally consistent warped images.

### Results:



| Image Frame                             | Optical Flow Map                         |
| <img src="/images/temp_loss_img.png" /> | <img src="/images/temp_loss_flow.png" /> |



### Loss curves comparison on test dataset:
![comparision](/images/temp_loss_compare.png)

* The project report is available <a href="/files/ml_temp_loss.pdf">here</a>.
