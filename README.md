# ACF Network: For Multi-Modal Violence Detection 
	
These are official codes for ICASSP2021 paper "LOOK, LISTEN AND PAY MORE ATTENTION: FUSING MULTI-MODAL INFORMATION FOR VIDEO VIOLENCE DETECTION"

Overall Structure 

![Structure of our method](overall-architecture.jpg)

Structure of SA unit and FA unit

<p align="center"><img src="https://gitee.com/silencewind/PicGoImage/raw/master/img/20210923210419.jpg" width="60%" height="23%"></p>
<p align="center"><img src="https://gitee.com/silencewind/PicGoImage/raw/master/img/20210923210418.jpg" width="60%" height="23%"></p>

## Updates
**`[September 22th]`** 
Our codes and more details about the work will be released soon, please stay tuned.

## Datasets
[XD-Violence](https://roc-ng.github.io/XD-Violence/)
This dataset is from the official github of "Not only Look, but also Listen: Learning Multimodal Violence Detection under Weak Supervision (ECCV2020)".

Based on their ground truth we have created a new format frame_mask of test dataset for our method, which has been published in the repository.

## Requirements
- python>=3.6
- pytorch=1.5.0+cu101
- torchvision=0.6.0+cu101
- scikit-learn
- numpy
- apex
- yacs
- opencv
