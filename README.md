# Completing Missing Entities: Exploring Consistency Reasoning for Oriented Object Detection
Peng Sun, Yongbin Zheng, Wanying Xu, Jian Li, and Jiansong Yang

## Introduction
This is the official implementation of the paper: **Completing Missing Entities: Exploring Consistency Reasoning for Remote Sensing Object Detection**, which is implemented on [MMrotate](https://github.com/open-mmlab/mmrotate).

We provide a demo to verify the experimental results, and the complete code will be released after the paper is accepted.
<img width="1963" height="729" alt="overview" src="https://github.com/user-attachments/assets/97ad4528-bcff-4e55-a7c7-3176c84d6ad0" />

## MMRotate官方使用文档
[English](/README-EN.md) | [简体中文](/README-CN.md)

## Code implementation
The code will be published after the paper is accepted. 

## Qualitative Results
<img width="516" height="558" alt="image" src="https://github.com/user-attachments/assets/7d0ba08d-a894-4945-9c90-7099963cf166" /> 

<img width="514" height="426" alt="image" src="https://github.com/user-attachments/assets/7e333b02-ad16-4faa-9997-c0a6d79aa3b7" />

<img width="968" height="468" alt="image" src="https://github.com/user-attachments/assets/485f5933-9848-49d4-bf67-5855963d353e" />

<img width="517" height="386" alt="image" src="https://github.com/user-attachments/assets/4ffb90f8-7767-4bb4-b45e-bd0c2768c32d" />

## Benchmark
### Remote Sensing Object Detection Task

| Model | Backbone | Dataset | Lr schd |  mAP | Configs | Download |
|:-:|:-:|:-:|:-:|:-:|
| FR-O w/ CTRP   | R50-FPN  | DOTA   | 1x  | 75.12 | 
| FR-O w/ CTRP   | R101-FPN | DOTA   | 1x  | 76.05 |
| O-RCNN w/ CTRP | R50-FPN  | DOTA   | 1x  | 77.17 |
| O-RCNN w/ CTRP | R101-FPN | DOTA   | 1x  | 77.80 |
| O-RCNN w/ CTRP | R50-FPN  | DIOR-R | 1x  | 65.53 |

### Occluded Object Detection Task

| Model | Backbone | Dataset | Lr schd |  mAP |
|:-:|:-:|:-:|:-:|:-:|
| FR-O w/ CTRP   | R50-FPN  | Occluded DOTA   | 1x  | 78.30 |
| FR-O w/ CTRP   | R50-FPN  | Occluded DOTA   | 1x  | 79.29 |
| O-RCNN w/ CTRP | R101-FPN | Occluded DOTA   | 1x  | 79.76 |
| O-RCNN w/ CTRP | R101-FPN | Occluded DOTA   | 1x  | 80.52 |
| FR-O w/ CTRP   | R50-FPN  | Occluded DIOR-R | 1x  | 58.46 |
| FR-O w/ CTRP   | R50-FPN  | Occluded DIOR-R | 1x  | 59.43 |
| O-RCNN w/ CTRP | R101-FPN | Occluded DIOR-R | 1x  | 61.54 |
| O-RCNN w/ CTRP | R101-FPN | Occluded DIOR-R | 1x  | 63.14 |

## Citation

If you use this toolbox or benchmark in your research, please cite this project.

```bibtex
@article{Li_2024_IJCV,
  title={LSKNet: A Foundation Lightweight Backbone for Remote Sensing},
  author={Li, Yuxuan and Li, Xiang and Dai, Yimain and Hou, Qibin and Liu, Li and Liu, Yongxiang and Cheng, Ming-Ming and Yang, Jian},
  journal={International Journal of Computer Vision},
  year={2024},
  doi = {https://doi.org/10.1007/s11263-024-02247-9},
  publisher={Springer}
}

@InProceedings{Li_2023_ICCV,
    author    = {Li, Yuxuan and Hou, Qibin and Zheng, Zhaohui and Cheng, Ming-Ming and Yang, Jian and Li, Xiang},
    title     = {Large Selective Kernel Network for Remote Sensing Object Detection},
    booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
    month     = {October},
    year      = {2023},
    pages     = {16794-16805}
}

@article{yuan2025strip,
  title={Strip R-CNN: Large Strip Convolution for Remote Sensing Object Detection},
  author={Yuan, Xinbin and Zheng, ZhaoHui and Li, Yuxuan and Liu, Xialei and Liu, Li and Li, Xiang and Hou, Qibin and Cheng, Ming-Ming},
  journal={arXiv preprint arXiv:2501.03775},
  year={2025}
}

```
