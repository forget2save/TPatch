# TPatch: A Triggered Physical Adversarial Patch

## Environment

- python 3.8.11
- numpy 1.22.4
- torch 1.9.0
- torchvision 0.10.0
- opencv-python 4.5.3.56
- Pillow 9.2.0
- scipy 1.7.1
- matplotlib 3.4.3

## Datasets

We evaluate the Altering Attacks (AA) with the ImageNet. 
And we evaluate the Hiding Attacks (HA) and Creating Attacks (CA) with the MSCOCO, KITTI, and BDD100K.
Please build the `dataset` folder in advance following the [README](dataset/README.md).

## Models

You can download these models and place them under the folder `weights`.

- [`vgg13.pth`](https://download.pytorch.org/models/vgg13_bn-abd245e5.pth)
- [`vgg16.pth`](https://download.pytorch.org/models/vgg16_bn-6c64b313.pth)
- [`vgg19.pth`](https://download.pytorch.org/models/vgg19_bn-c79401a0.pth)
- [`resnet50.pth`](https://download.pytorch.org/models/resnet50-0676ba61.pth)
- [`resnet101.pth`](https://download.pytorch.org/models/resnet101-63fe2227.pth)
- [`resnet152.pth`](https://download.pytorch.org/models/resnet152-394f9c45.pth)
- [`incv3.pth`](https://download.pytorch.org/models/inception_v3_google-0cc3c7bd.pth)
- [`mobv2.pth`](https://download.pytorch.org/models/mobilenet_v2-b0353104.pth)
- [`fasterrcnn.pth`](https://drive.google.com/file/d/1lbvP04Y0M7-5Sw0Lny-XwHukpszA76iL/view?usp=sharing)
- [`yolov3.pt`](https://drive.google.com/file/d/1rFtQ1Nli063IstVg51ovpP3MXgpBo1jK/view?usp=sharing)
- [`yolov5m.pt`](https://drive.google.com/file/d/1J_Cw7JUO1VfgKCfHgExB-jEAK55BuCDN/view?usp=sharing)
