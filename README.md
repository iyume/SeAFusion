

#  SeAFusion

The code of "Image fusion in the loop of high-level vision tasks: A semantic-aware real-time infrared and visible image fusion network"

## To Train

Run "**CUDA_VISIBLE_DEVICES=0 python train.py**" to train your model.
The training data are selected from the MFNet dataset. For convenient training, users can download the training dataset from [here](https://pan.baidu.com/s/1xueuKYvYp7uPObzvywdgyA), in which the extraction code is: **bvfl**.

## To Test

Run "**CUDA_VISIBLE_DEVICES=0 python test.py**" to test the model.


## Recommended Environment

 - [ ] torch  1.7.1
 - [ ] torchvision 0.8.2
 - [ ] numpy 1.19.2
 - [ ] pillow  8.0.1

## If this work is helpful to you, please cite it as：
```
@article{TANG2022SeAFusion,
title = {Image fusion in the loop of high-level vision tasks: A semantic-aware real-time infrared and visible image fusion network},
journal = {Information Fusion},
year = {2022},
issn = {1566-2535},
doi = {https://doi.org/10.1016/j.inffus.2021.12.004},
url = {https://www.sciencedirect.com/science/article/pii/S1566253521002542},
author = {Linfeng Tang and Jiteng Yuan and Jiayi Ma},
}
```
