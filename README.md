# Awesome Box-supervised Instance Segmentation.
NOTE: If I miss some paper, plese feel free to submit a Pull Request.

## 2023

| Methods | Publication | Supervision | paper | code | dataset|
| :----: | :----: | :----: | :----: | :----: |:----:|
| BoxSnake| ArXiv| Box |  [paper](https://arxiv.org/pdf/2303.11630.pdf) | [code](https://github.com/Yangr116/BoxSnake) | COCO, Cityscapes|
| SIM    | CVPR2023| Box |  [paper](https://arxiv.org/abs/2303.08578) | [code](https://github.com/lslrh/SIM) | COCO, VOC|
| BoxTeacher   |  CVPR2023 | Box | [paper](https://arxiv.org/abs/2210.05174#) | [code](https://github.com/hustvl/BoxTeacher) | COCO, VOC, Cityscapes|
| Mask Auto-Labeler | ArXiv2023 | Box | [paper](https://arxiv.org/pdf/2301.03992.pdf) | [code](https://github.com/NVlabs/mask-auto-labeler)  | COCO, LVIS|

## 2022
| Methods | Publication | Supervision | paper | code | dataset|
| :----: | :----: | :----: | :----: | :----: |:----:|
| Box2Mask      | ArXiv2022 | Box | [paper](https://arxiv.org/pdf/2212.01579.pdf) | [code](https://github.com/LiWentomng/boxlevelset)  | COCO, VOC, iSAID, LiTS|
| AsyInst       | ArXiv2022 | Box | [paper](https://arxiv.org/pdf/2212.03517.pdf) | - | Cityscapes, iSAID |
| Zhang et al.  |  PR2022| Box/Scribble |[paper](https://www.sciencedirect.com/science/article/pii/S0031320322006446)| - |COCO, VOC|
| BoxLevelSet  |  ECCV2022 | Box | [paper](https://link.springer.com/chapter/10.1007/978-3-031-19818-2_1) | [code](https://github.com/LiWentomng/boxlevelset) | COCO, VOC, iSAID, etc|

## 2021
| Methods | Publication | Supervision | paper | code |dataset|
| :----: | :----: | :----: | :----: | :----: |:----: |
| DiscoBox  |  ICCV2021 | Box | [paper](https://openaccess.thecvf.com/content/ICCV2021/html/Lan_DiscoBox_Weakly_Supervised_Instance_Segmentation_and_Semantic_Correspondence_From_Box_ICCV_2021_paper.html) | [code](https://github.com/NVlabs/DiscoBox) | COCO,VOC|
| BoxInst|  CVPR2021 | Box | [paper](https://openaccess.thecvf.com/content/CVPR2021/html/Tian_BoxInst_High-Performance_Instance_Segmentation_With_Box_Annotations_CVPR_2021_paper.html) | [code](https://github.com/aim-uofa/AdelaiDet/blob/master/configs/BoxInst/README.md) |COCO,VOC|
| BBAM   |  CVPR2021 | Box | [paper](https://openaccess.thecvf.com/content/CVPR2021/html/Lee_BBAM_Bounding_Box_Attribution_Map_for_Weakly_Supervised_Semantic_and_CVPR_2021_paper.html) | [code](https://github.com/jbeomlee93/BBAM) |COCO, VOC|
| BoxCaseg   |  CVPR2021 | Box+Sailency | [paper](https://openaccess.thecvf.com/content/CVPR2021/html/Wang_Weakly-Supervised_Instance_Segmentation_via_Class-Agnostic_Learning_With_Salient_Images_CVPR_2021_paper.html) | [code](https://github.com/hustvl/BoxCaseg) |COCO, VOC|
| A^2GNN   |  TPAMI2021 | Box | [paper](https://ieeexplore.ieee.org/document/9440699) | [code](https://github.com/zbf1991/A2GNN) |COCO, VOC|

## 2020
| Methods | Publication | Supervision | paper | code |dataset|
| :----: | :----: | :----: | :----: | :----: |:----: |
| Arun et al.  |  ECCV2020 | Box | [paper](https://link.springer.com/chapter/10.1007/978-3-030-58604-1_16) | - | VOC|
| Sun et al.  |  IEEE Acess2020 | Box | [paper](https://link.springer.com/chapter/10.1007/978-3-030-58604-1_16) | - | VOC|

## 2019
| Methods | Publication | Supervision | paper | code |dataset|
| :----: | :----: | :----: | :----: | :----: |:----: |
| BBTP  |  NIPS2019 | Box | [paper](https://proceedings.neurips.cc/paper/2019/file/e6e713296627dff6475085cc6a224464-Paper.pdf) | [code](https://github.com/chengchunhsu/WSIS_BBTP) | COCO,VOC|

## 2017
| Methods | Publication | Supervision | paper | code |dataset|
| :----: | :----: | :----: | :----: | :----: |:----: |
| SDI  |  CVPR2017 | Box | [paper](https://openaccess.thecvf.com/content_cvpr_2017/papers/Khoreva_Simple_Does_It_CVPR_2017_paper.pdf) | [code](https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/weakly-supervised-learning/simple-does-it-weakly-supervised-instance-and-semantic-segmentation) | VOC|


## Related Paper
 * Instance segmentation with `image-level` supervision
 
 | Methods | Publication | Supervision | paper | code |dataset|
 | :----: | :----: | :----: | :----: | :----: |:----: |
 | EM-Paste | ArXiv2022 | image-level | [paper](https://arxiv.org/pdf/2212.07629.pdf) | - |  COCO,VOC |


 * Instance segmentation with `box+points` supervision
 
| Methods | Publication | Supervision | paper | code |dataset|
| :----: | :----: | :----: | :----: | :----: |:----: |
| LWSIS | AAAI2023 | Box+ points for LiDAR | [paper](https://arxiv.org/pdf/2212.03504.pdf) | [code](https://github.com/Serenos/LWSIS) |  nuInsSeg(based nuScenes) |
| APIS |  ECCV2022 | Box+7/10Points | [paper](https://arxiv.org/abs/2207.11493) | [code](https://github.com/chufengt/APIS) | COCO|
| PointSup |  CVPR2022 | Box+10Points | [paper](https://openaccess.thecvf.com/content/CVPR2022/html/Cheng_Pointly-Supervised_Instance_Segmentation_CVPR_2022_paper.html) | [code](https://bowenc0221.github.io/point-sup/) | COCO|

 * Rotate object detection with the genenral `horizontal box` supervision 
 
| Methods | Publication | Supervision | paper | code |dataset|
| :----: | :----: | :----: | :----: | :----: |:----: |
| H2RBox | ICLR2023 | horizontal box   | [paper](https://arxiv.org/abs/2210.06742) | [code](https://github.com/yangxue0827/h2rbox-mmrotate) | DOTA, DIOR|
