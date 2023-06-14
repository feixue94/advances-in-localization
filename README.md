# Advances in Visual Localization, Local Features, Matching and Rerieval

This repository shows recent papers about **visual localization**, **local featuers** and **matching method**. Papers of using **NeRFs**, **large-languge-model (LLM)** and **vision-language-model (VLM)** for visual localization will also be included.   

Feel free to add papers which are of your interest by pulling requests. 

## Contents

- [Visual localization]
    - [Visual localization with different maps (SfM, CADs, etc)]
    - [Absolute pose regression - APR]
    - [Scene coordinate regression - SCR] 
- [Local features]
- [Matching]
    - [Sparse matching between keypoints]
    - [Dense matching between pixels]
- [Retrieval] 

## 2023

### Visual Localization
- [2023 CVPR] Visual Localization using Imperfect 3D Models from the Internet [[paper](https://arxiv.org/abs/2304.05947)] [**Keywords - localization from CAD models; CADs**] 
- [2023 CVPR] Long-term Visual Localization with Mobile Sensors [[paper](https://arxiv.org/abs/2304.07691)] [**Keywords - GPS for retrieval; gravity for geometric verification; SfM**]
- [2023 CVPR] OrienterNet: Visual Localization in 2D Public Maps with Neural Matching [[paper](https://arxiv.org/abs/2304.02009)] [**Keywords - localization with OpenStreetMap**]
- [2023 CVPR] NeuMap: Neural Coordinate Mapping by Auto-Transdecoder for Camera Localization [[paper](https://arxiv.org/abs/2211.11177)] [[code](https://github.com/Tangshitao/NeuMap)] [**Keywords** - scene coordinate regression from hidden states]
- [2023 ICRA] NeRF-Loc: Visual Localization with Conditional Neural Radiance Field [paper](https://arxiv.org/abs/2304.07979)] [[code](https://github.com/TencentYoutuResearch/NeRF-Loc)] [**Keywords - rendering 3D descriptors from NeRFs; NeRFs**] 

### Local features
- [CVPR 2023] SFD2: Semantic-guided Feature Detection and Description [[paper](https://arxiv.org/abs/2304.14845)] [[code](https://github.com/feixue94/sfd2)] [**Keywords - implicit semantics embedding into features; automatic feature selection for localization**]
- [CVPR 2023] FeatureBooster: Boosting Feature Descriptors with a Lightweight Neural Network [[paper](https://arxiv.org/abs/2211.15069)] [[code](https://github.com/SJTU-ViSYS/FeatureBooster)] [**Keywords** - augmentation descriptors with transformers**]
- [CVPR 2023] D2Former: Jointly Learning Hierarchical Detectors and Contextual Descriptors via Agent-based Transformers [[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/He_D2Former_Jointly_Learning_Hierarchical_Detectors_and_Contextual_Descriptors_via_Agent-Based_CVPR_2023_paper.pdf)] [**Keywords - perceiver-like detector & descriptor**]

### Matching
- [CVPR 2023] IMP: Iterative Matching and Pose Estimation with Adaptive Pooling [[paper](https://arxiv.org/abs/2304.14837)] [[code](https://github.com/feixue94/imp-release)] [**Keywords - iterative matching and pose estimatin; training graph matcher from scratch; sparse matching**]
- [CVPR 2023] DKM: Dense Kernelized Feature Matching for Geometry Estimation [[paper](https://arxiv.org/abs/2202.00667)] [[code](https://github.com/Parskatt/DKM)] [**Keywords - global matcher; local warp; certainty estimation**]
- [CVPR 2023] PATS: Patch Area Transportation with Subdivision for Local Feature Matching [[paper](https://arxiv.org/pdf/2303.07700.pdf)] [[code](https://github.com/zju3dv/pats)] [**Keywords - patch division; dense matching**]
- [CVPR 2023] Adaptive Assignment for Geometry Aware Local Feature Matching [[paper](https://arxiv.org/abs/2207.08427)] [[code](https://github.com/AbyssGaze/AdaMatcher)] [**Keywords - one-many matching; sub-pixel refinement; dense matching**]
- [CVPR 2023] Adaptive Spot-Guided Transformer for Consistent Local Feature Matching [[paper](https://arxiv.org/pdf/2303.16624.pdf)] [**Keywords - spot-guided aggregation; dense matching**]
- [CVPR 2023] PMatch: Paired Masked Image Modeling for Dense Geometric Matching [[paper](https://arxiv.org/pdf/2303.17342.pdf)] [[code](https://github.com/ShngJZ/PMatch)] [**Keywords - masked image modeling; homography loss; dense matching**]
- [CVPR 2023] Progressive Neighbor Consistency Mining for Correspondence Pruning [[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Liu_Progressive_Neighbor_Consistency_Mining_for_Correspondence_Pruning_CVPR_2023_paper.pdf)] [[code](https://github.com/xinliu29/NCMNet)] [**Keywords - neghbor consistency; correspondence pruning**]


## 2021

### Visual Localization
- [2021 CoRL] LENS: Localization enhanced by NeRF synthesis [[paper](https://arxiv.org/abs/2110.06558)] [**Keywords - nerfs for generating more training images; NeRFs**] 



