# Chromosome Instance Segmentation with Cascade Mask R-CNN
---
This project uses **Cascade Mask R-CNN** for instance segmentation of metaphase chromosomes based on the **KaryoNet** dataset.

## Installnation

- **Model**: Cascade Mask R-CNN  
- **Backbone**: ResNet-50  
- **Framework**: MMDetection  

Based on the method proposed by:  
> Cai & Vasconcelos, *Cascade R-CNN: Delving into High Quality Object Detection*, CVPR 2018.  

## Dataset

Images and annotations come from:  
> Xu et al., *KaryoNet: Chromosome Recognition With End-to-End Combinatorial Optimization Network*, IEEE TMI 2022.

## Cite & Acknowledgements

```
@article{liu2023autokary,
  author    = {Liu, Chuanqi and Hu, Xianxu and Li, Jiazhao and He, Dongrui and Song, Shuai and Sun, Zhenan},
  title     = {{AutoKary2022}: A Large-Scale Densely Annotated Dataset for Chromosome Instance Segmentation},
  journal   = {IEEE Transactions on Medical Imaging},
  year      = {2023},
  doi       = {10.1109/TMI.2023.3241234}
}

@article{cai2019cascade,
  author    = {Cai, Zhaowei and Vasconcelos, Nuno},
  title     = {Cascade R-CNN: High Quality Object Detection and Instance Segmentation},
  journal   = {IEEE Transactions on Pattern Analysis and Machine Intelligence},
  year      = {2019},
  volume    = {43},
  number    = {5},
  pages     = {1483--1498},
  doi       = {10.1109/TPAMI.2019.2908669}
}
```

The implementation is based on the Cascade R-CNN framework and utilizes the AutoKary2022 dataset.
Thank theses authors sincerely for their contributions to the community.

This work is built upon the efforts of the KaryoNet and Cascade Mask R-CNN authors — sincere thanks for their contributions.
