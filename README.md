
# Neurocomputing-BCNet

This repo is the official implementation of ["BCNet: Bidirectional Collaboration Network for Edge-Guided Salient Object Detection"](https://www.sciencedirect.com/science/article/abs/pii/S0925231221000552). 



## 1. Introduction

The boundary quality is a key factor determining the success of accurate salient object detection (SOD). A number of edge-guided SOD methods have been proposed to improve the boundary quality, but shown unsatisfactory performance due to the lack of a comprehensive consideration of multi-level feature fusion and multi-type feature aggregation. To resolve this issue, we propose a novel Bidirectional Collaboration Network (BCNet), which integrates effective multi-level feature fusion and multi-type feature aggregation into a unified edge-guided SOD framework. Specifically, we first utilize multiple Consistency Saliency Maximization (CSM) modules to propagate the highest level semantic representations in a top-down progressive pathway to generate both global edge representations and a series of region representations. Multiple Bounded Feature Fusion (BFF) modules are then utilized to refine the region features with the edge features. The CSM and BFF modules enable robust multi-level feature fusion and multi-type feature aggregation with only little extra computation, which allows a high computational efficiency. Finally, BCNet is jointly trained with edge and region losses in an end-to-end manner. Extensive comparisons are conducted with 17 state-of-the-art methods on five challenging benchmark datasets. Thanks to the use of CSM and BFF modules, our BCNet outperforms existing deep learning based SOD methods, including the latest edge-guided ones, in terms of both detection accuracy and processing speed.



## 2. Framework Overview
![](https://github.com/dongbo811/Neurocomputing-SOD/blob/main/bcnet_net.png)


## 3. Results
![](https://github.com/dongbo811/Neurocomputing-SOD/blob/main/results.png)

 
## 4. FAQ:
The source code, data and results can be find at [link](https://pan.baidu.com/s/1PE53Pd95gF3Mm30JX5EMWA?pwd=5axs)[5axs]

If you want to improve the usability or any piece of advice, please feel free to contact me directly (bodong.cv@gmail.com).

## 5. Citation:
```
@article{dong2021bcnet,
  title={BCNet: bidirectional collaboration network for edge-guided salient object detection},
  author={Dong, Bo and Zhou, Yan and Hu, Chuanfei and Fu, Keren and Chen, Geng},
  journal={Neurocomputing},
  volume={437},
  pages={58--71},
  year={2021},
  publisher={Elsevier}
}
```
## 6. License
The source code is free for research and education use only. Any comercial use should get formal permission first.
