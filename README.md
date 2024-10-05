# PointJEM

# Note: If your work uses this algorithm or makes improvements based on it, please be sure to cite this paper. Thank you for your cooperation.

# 注意：如果您的工作用到了本算法，或者基于本算法进行了改进，请您务必引用本论文，谢谢配合

# PointJEM: Self-supervised Point Cloud Understanding for Reducing Feature Redundancy via Joint Entropy Maximization

Xin Cao, Huan Xia, Haoyu Wang, Linzhi Su, Ping Zhou and Kang Li※

The 32th Pacific Conference on Computer Graphics and Applications (Pacific Graphics 2024), 2024. (Oral presentation)

##  Datasets

Please download the used dataset with the following links:

+ ShapeNet: https://drive.google.com/uc?id=1sJd5bdCg9eOo3-FYtchUVlwDgpVdsbXB

+ ModelNet40: https://shapenet.cs.stanford.edu/media/modelnet40_normal_resampled.zip
+ ScanNet (subset): Please follow the instruction in their official [website](http://www.scan-net.org/). The 25k frames subset is enough for our model. You may also need to download the preprocessed data for evaluation [here](https://shapenet.cs.stanford.edu/media/scannet_data_pointnet2.zip).

## Requirements:

```
python==3.10.14
pytorch==1.12.1
torchvision==0.13.1
```

## Pre-tarined:

```
pyton train.py
```

## Downstream Tasks:

For the fine-tuning and evaluation of downstream tasks, please refer to other corresponding repos. We sincerely thank all these authors for their nice work!

+ Classification: [WangYueFt/dgcnn](https://github.com/WangYueFt/dgcnn)
+ Semantic Segmentation: [AnTao97/*dgcnn*.pytorch](https://github.com/AnTao97/dgcnn.pytorch)
+ Indoor Object Detection: [facebookresearch/*votenet*](https://github.com/facebookresearch/votenet)

## Citation

```
@misc{cao2023pointjemselfsupervisedpointcloud,
      title={PointJEM: Self-supervised Point Cloud Understanding for Reducing Feature Redundancy via Joint Entropy Maximization}, 
      author={Xin Cao and Huan Xia and Xinxin Han and Yifan Wang and Kang Li and Linzhi Su},
      year={2023},
      eprint={2312.03339},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2312.03339}, 
}
```

