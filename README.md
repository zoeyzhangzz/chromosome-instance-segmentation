# Chromosome Instance Segmentation with Cascade Mask R-CNN

This project uses **Cascade Mask R-CNN** for instance segmentation of metaphase chromosomes based on the **KaryoNet** dataset.

## Method

- **Model**: Cascade Mask R-CNN  
- **Backbone**: ResNet-50  
- **Framework**: MMDetection  

Based on the method proposed by:  
> Cai & Vasconcelos, *Cascade R-CNN: Delving into High Quality Object Detection*, CVPR 2018.  
> [Paper Link](https://openaccess.thecvf.com/content_cvpr_2018/html/Cai_Cascade_R-CNN_Delving_Into_CVPR_2018_paper.html)

## Dataset

Images and annotations come from:  
> Xu et al., *KaryoNet: Chromosome Recognition With End-to-End Combinatorial Optimization Network*, IEEE TMI 2022.  
> [Paper Link](https://ieeexplore.ieee.org/document/9704970)

Thanks to the authors for making the dataset and methods publicly available.

## Results

- Successfully segmented individual chromosomes, including overlaps
- Enables further analysis for chromosome abnormality detection

## TODO

- [ ] Add evaluation metrics  
- [ ] Upload sample visualizations  

---

**Acknowledgment**:  
This work is built upon the efforts of the KaryoNet and Cascade Mask R-CNN authors — sincere thanks for their contributions.
