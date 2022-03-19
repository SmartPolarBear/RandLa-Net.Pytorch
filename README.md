# RandLA-Net: Efficient Semantic Segmentation of Large-Scale Point Clouds

This repository contains a PyTorch implementation of [RandLA-Net](http://arxiv.org/abs/1911.11236).

For detailed usage, see [original README](https://github.com/aRI0U/RandLA-Net-pytorch).  

To train the model, you overall follow the following procedure: 

> [fix errors in the dataset] --> prepare_*.py --> subsample_data.py --> train.py

## Fix S3DIS

S3DIS dataset contains some unprintable characters, which result in failures in preprocessing the data and training the model.
To fix those problems, [fix_s3dis.py](https://github.com/SmartPolarBear/RandLa-Net.Pytorch/blob/master/utils/fix_s3dis.py) is implemented
for removing them.

