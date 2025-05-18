# Chromosome Instance Segmentation with Cascade Mask R-CNN
---
This project uses **Cascade Mask R-CNN** for instance segmentation of metaphase chromosomes based on the **KaryoNet** dataset.

## Environment
This project is built upon the [MMDetection](https://github.com/open-mmlab/mmdetection?tab=readme-ov-file) framework. Please follow the official [MMDetection installation guide](https://mmdetection.readthedocs.io/en/latest/get_started.html) to set up your environment. Create a virtual-env Python environment to avoid version conflicts.


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

The implementation is based on the Cascade R-CNN framework and utilizes the AutoKary2022 dataset.Thank theses authors for their contributions to the community.
