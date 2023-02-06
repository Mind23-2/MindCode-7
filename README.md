# [Auto-DeepLab Description](https://gitee.com/mindspore/models/blob/r1.6/research/cv/Auto-DeepLab/README.md#contents)

DeepLab is a state-of-art deep learning model for semantic image segmentation,
where the goal is to assign semantic labels.
we propose to search the network level structure in addition to the cell level structure, which forms a hierarchical architecture search space. We present a network level search space that includes many popular designs, and develop a formulation that allows efficient gradient-based architecture search.

[Paper](https://gitee.com/link?target=https%3A%2F%2Farxiv.org%2Fabs%2F1901.02985v2): Chenxi Liu, Liang-Chieh Chen, Florian Schroff, Hartwig Adam, Wei Hua, Alan L. Yuille, Li Fei-Fei; Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2019, pp. 82-92

# [Model Architecture](https://gitee.com/mindspore/models/blob/r1.6/research/cv/Auto-DeepLab/README.md#contents)

Searched architecture as encoder, with ASPP and reuse Decoder from DeepLabV3+

The whole model is trained from scratch.

[RepoLink](https://gitee.com/mindspore/models/tree/r1.6/research/cv/Auto-DeepLab)