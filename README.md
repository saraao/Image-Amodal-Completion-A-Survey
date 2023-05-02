# Image-Amodal-Completion-A-Survey

This repository categorises computer vision research papers about single image-based amodal completion techniques according to their target task. The classification is based on our survey: ["Image Amodal Completion: A Survey"](https://arxiv.org/abs/2207.02062). By leveraging our repository and survey, researchers and practitioners alike can gain a comprehensive insight into the latest developments in image amodal completion and make informed decisions about which techniques/datasets to apply in their own work.


> SURVEY ABSTRACT: Existing computer vision systems can compete with humans in understanding the visible parts of objects, but still fall far short of humans when it comes to depicting the invisible parts of partially occluded objects. Image amodal completion aims to equip computers with human-like amodal completion functions to understand an intact object despite it being partially occluded. The main purpose of this survey is to provide an intuitive understanding of the research hotspots, key technologies and future trends in the field of image amodal completion. Firstly, we present a comprehensive review of the latest literature in this emerging field, exploring three key tasks in image amodal completion, including amodal shape completion, amodal appearance completion, and order perception. Then we examine popular datasets related to image amodal completion along with their common data collection methods and evaluation metrics. Finally, we discuss real-world applications and future research directions for image amodal completion, facilitating the reader's understanding of the challenges of existing technologies and upcoming research trends.

## Summary

1. [Amodal Shape Completion](#1)  
2. [Amodal Appearance Completion](#2)  
3. [Order Perception](#3)
4. [Amodal Datasets](#4)  

## Content
### 1. Amodal Shape Completion  <a name="1"></a>
#### (1) Amodal instance segmentation
##### Traditional methods
[Euler spiral for shape completion](https://www.cs.bgu.ac.il/~ben-shahar/ftp/papers/Edge_Completion/2003:Kimia_Frankel_and_Popescu:Euler_Spiral_for_Shape_Completion.pdf)(IJCV03)

[An improved Euler spiral algorithm for shape completion](https://ieeexplore.ieee.org/abstract/document/4562116)(Canadian Conference on Computer and Robot Vision 08)

[A contour completion model for augmenting surface reconstructions](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/depth_completion_eccv_email.pdf)(ECCV14)

[A computational model of topological and geometric recovery for visual curve completion](https://dc.tsinghuajournals.com/cgi/viewcontent.cgi?article=1054&context=computational-visual-media)(Computational Visual Media 16)

[In the shadows, shape priors shine: Using occlusion to improve multi-region segmentation](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Kihara_In_the_Shadows_CVPR_2016_paper.pdf)(CVPR16)

##### CNN-based methods
[Amodal Completion and Size Constancy in Natural Scenes](https://arxiv.org/abs/1509.08147)(ICCV15)

[Amodal instance segmentation](https://arxiv.org/abs/1604.08202)(ECCV16)

[Semantic amodal segmentation]()(CVPR17)

[Segan: Segmenting and generating the invisible]()(CVPR18)

[Amodal Instance Segmentation With KINS Dataset](https://openaccess.thecvf.com/content_CVPR_2019/papers/Qi_Amodal_Instance_Segmentation_With_KINS_Dataset_CVPR_2019_paper.pdf)(CVPR19)

[Learning to see the invisible: End-to-end trainable amodal instance segmentation]()(WACV 19)

[Seeing behind things: Extending semantic segmentation to occluded regions]()(IROS19)

[Sail-vos: Semantic amodal instance level video object segmentation-a synthetic dataset and baselines]()(CVPR19)

[Deep Occlusion-Aware Instance Segmentation with Overlapping BiLayers](https://arxiv.org/abs/2103.12340)(CVPR21)

[Amodal Segmentation Based on Visible Region Segmentation and Shape Prior]()(AAAI21)

##### CompositionalNets Variants

[Robust object detection under occlusion with context-aware compositionalnets]()(CVPR20)

[Robust Instance Segmentation Through Reasoning About Multi-Object Occlusion]()(CVPR21)

[Amodal Segmentation Through Out-of-Task and Out-of-Distribution Generalization With a Bayesian Model]()(CVPR22)

##### Weakly/Self supervied learning
[Self-supervised scene de-occlusion]()(CVPR20)

[Variational amodal object completion]()(NeurIPS20)

[A Weakly Supervised Amodal Segmenter With Boundary Uncertainty Estimation]()(ICCV21)

[WALT: Watch and Learn 2D Amodal Representation From Time-Lapse Imagery]()(CVPR22)

#### (2) Semantics-aware distance maps
[Learning semantics-aware distance map with semantics layering network for amodal instance segmentation](https://arxiv.org/abs/1905.12898) (ACMMM19) 
#### (3) Amodal semantic/panoptic segmentation
[Amodal Cityscapes: A New Dataset, its Generation, and an Amodal Semantic Segmentation Challenge Baseline](https://arxiv.org/abs/2206.00527) (IV22)

[Amodal Panoptic Segmentation](https://openaccess.thecvf.com/content/CVPR2022/papers/Mohan_Amodal_Panoptic_Segmentation_CVPR_2022_paper.pdf) (CVPR22)

[Perceiving the Invisible: Proposal-Free Amodal Panoptic Segmentation](https://arxiv.org/abs/2205.14637) (RA-L22)

#### (4) Amodal scene layouts

[Monolayout: Amodal scene layout from a single image](https://arxiv.org/abs/2002.08394) (WACV20)

[Seeing the un-scene: Learning amodal semantic maps for room navigation](https://arxiv.org/abs/2007.09841) (ECCV20)

[Weakly but Deeply Supervised Occlusion-Reasoned Parametric Road Layouts](https://arxiv.org/abs/2104.06730) (CVPR22)

### 2. Amodal Appearance Completion <a name="2"></a>
#### Object-centric Representations for Toy Datasets
#### Category-specific Studies
#### Methods for Complex Scenes

### 3. Order Perception <a name="3"></a>
#### Occlusion Order
#### Layer Order

### 4. Amodal Datasets <a name="4"></a>
