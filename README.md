# Practical Wide-Angle Portraits Correction with Deep Structured Models
Jing Tan, Shan Zhao, Pengfei Xiong, Jiangyu Liu, Haoqiang Fan, Shuaicheng Liu

\[[arxiv](https://arxiv.org/abs/2104.12464)\] \[[BibTeX](#Citation)\]

<div align="center">
  <img src="figures/cvpr21_poster_latest.png"/>
</div><br/>

## Note
In this repository, we will release dataset and pytorch implementation of our paper.

## Quick Start
Python 3.6+, Pytorch 1.2, torchvision 0.4, cuda10.0, and other requirements. 

All codes are tested on Linux.

### Installation
1. Clone the repository
   ```
   git clone https://github.com/TanJing94/Deep_Portraits_Correction.git
   cd Deep_Portraits_Correction
   ```
2. Install dependencies
   ```
   pip install -r requirements.txt
   ```

### Resources preparation
1. Dataset
+ Download from [[BaiduCloud](https://pan.baidu.com/s/1MvwulIIs2CowfQ-8d0gcsQ?pwd=5pe5)], extraction code: 5pe5
+ Please refer to [[dataset.py](https://github.com/megvii-research/Portraits_Correction/blob/main/utils/dataset.py)] for data usage

2. Pre-trained model

### Training


### Testing



## Citation
If you find this work or code is helpful in your research, please cite:

```
@inproceedings{tan2021practical,
  title={Practical Wide-Angle Portraits Correction with Deep Structured Models},
  author={Tan, Jing and Zhao, Shan and Xiong, Pengfei and Liu, Jiangyu and Fan, Haoqiang and Liu, Shuaicheng},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={3498--3506},
  year={2021}
}
```