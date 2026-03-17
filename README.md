# CR2Former
CR2Former: Contour-relation aware representation learning for fine-grained bird image classification via Transformers

## 📑 Abstract
Fine-grained bird image classification (FBIC) has attracted increasing attention in image processing due to its critical role in protecting endangered birds. Previous studies faced several challenges, such as complex environments, multifarious postures and backlight scenarios. To effectively address these challenges, we propose a novel contour token learning network (CR2Former) to learn discriminative features by explicitly incorporating contour structural information alongside critical visual cues. Specifically, the approach begins with a contour token construction module to estimate the bird contour and extract contour tokens. Then, a contour relationship mining module is developed to fuse visual and contour tokens and capture long-dependent between them. In addition, to learn bird distinctive features at multiple levels, a key cues awareness module is embedded within CR2Former. The performance of CR2Former was evaluated on two bird datasets: CUB200–2011 and NABirds. The framework demonstrates significant improvements over existing state-of-the-art methods. Furthermore, experiments on other fine-grained datasets demonstrate the framework's strong generalization capabilities across different classification tasks. The source code will be available upon request.

## 🌟 Key Contributions
•A novelcontour relation aware network (CR2Former) is developed to efficiently combine contour information and visual cues for fine-grained classification of birds.

•A contour relationship mining (CRM) module is designed to mine the spatial semantic relationship between contour information and visual information, as well as the long-dependent between visual and contour information.

•The key cues awareness (KCA) module is designed to enhance the perception of subtle and discriminative features. This module extracts semantic information of different sizes from each stage feature map and obtains the feature weights corresponding to different stages through stage attention.

•Comprehensive experiments were conducted on two FBIC-related datasets, CUB-200–2011 and NABirds. Compared with the existing state-of-the-art methods, our proposed CR2Former demonstrates superior results, validating the effectiveness of incorporating contour information for accurate bird classification.

## 📊 Datasets
Comparative experiments were conducted on two widely used fine-grained classification datasets, NABirds and CUB-200-2011. All datasets followed the official training/test splits, and all images were uniformly resized to a resolution of 224×224.

## Citation
```bibtex
@article{LIU2026132724,
title = {CR2Former: Contour-relation aware representation learning for fine-grained bird image classification via Transformers},
journal = {Neurocomputing},
volume = {671},
pages = {132724},
year = {2026},
issn = {0925-2312},
doi = {https://doi.org/10.1016/j.neucom.2026.132724},
url = {https://www.sciencedirect.com/science/article/pii/S0925231226001219},
author = {Hai Liu and Hao Zheng and Tingting Liu and Yu Song and Xiaolan Yang and Zhaoli Zhang},
keywords = {Fine-grained bird image classification, Contour-relation representation, Image understanding, Transformers, Computer vision}
