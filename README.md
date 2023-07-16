# STrajNet
This repo is the implementation of the following paper:

**STrajNet: Multi-Model Hierarchical Transformer for Occupancy Flow Field Prediction in Autonomous Driving**
<br> [Haochen Liu](https://scholar.google.com/citations?user=iizqKUsAAAAJ&hl=en), [Zhiyu Huang](https://mczhi.github.io/), [Chen Lv](https://scholar.google.com/citations?user=UKVs2CEAAAAJ&hl=en) 
<br> [AutoMan Research Lab, Nanyang Technological University](https://lvchen.wixsite.com/automan)
<br> **[[arXiv]](http://arxiv.org/abs/2208.00394)**&nbsp; **[[paper]](https://ieeexplore.ieee.org/abstract/document/10160855)**&nbsp;

## General Info
- Our paper has been accepted in ICRA 23'!
- This implementation is improved upon our solutions in ablations, which has won the **2nd place for 2022 Waymo Occupancy and Flow Prediction Challenge**
- 🥈[**2022 Waymo Occupancy and Flow Prediction**](https://youtu.be/G01cfxuJ_ro)   
- 🚗[**CVPR2022 Workshop on Autonomous Driving website**](https://cvpr2022.wad.vision)
- 📑[**Waymo Occupancy and Flow Prediction Website**](https://waymo.com/open/challenges/2022/occupancy-flow-prediction-challenge/)
- Our implementation has achieved 3 SOTA metrics (Sep-2022), outperforms other baselines without using pretrained models, and has more concise structures:

![](pics/leaderboard.png)

- Model Framework Overview:

![](pics/overview.png)

## Dataset
Download the [Waymo Open Motion Dataset](https://waymo.com/open/data/motion/); the files in ```tf_exmaple/``` are used. Place the downloaded files into training and testing folders separately.

Also download the required [scenario IDs files](https://console.cloud.google.com/storage/browser/_details/waymo_open_dataset_motion_v_1_1_0/uncompressed/occupancy_flow_challenge/) (.txt) for evalutation and testing

## Citation
If you find this work useful please cite us 😀

```
@inproceedings{liu2023multi,
  title={Multi-modal Hierarchical Transformer for Occupancy Flow Field Prediction in Autonomous Driving},
  author={Liu, Haochen and Huang, Zhiyu and Lv, Chen},
  booktitle={2023 IEEE International Conference on Robotics and Automation (ICRA)},
  pages={1449--1455},
  year={2023},
  organization={IEEE}
}
```

