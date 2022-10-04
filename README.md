# Person-Reidentification

This code is an implementation of [[Multi-direction and Multi-scale Pyramid in
Transformer for Video-based Pedestrian Retrieval]](https://arxiv.org/pdf/2202.06014.pdf). 

To run the code, Please follow the Vis.ipynb file. The pretrained model can be found at this [[link]](https://github.com/rwightman/pytorch-image-models/releases/download/v0.1-vitjx/jx_vit_base_p16_224-80ecf9dd.pth)

### Requirements

```
# virtual envs
$ conda create -n PiT python=3.6 -y
$ conda activate PiT
# install pytorch 1.8.1/1.6.0 
$ pip install timm scipy einops yacs opencv-python tensorboard pandas
```

### Dataset Preparation
For iLIDS-VID, please refer to this [issue](https://github.com/deropty/PiT/issues/2).

### Base
This repository is built upon the repository [TranReID](https://github.com/damo-cv/TransReID).
