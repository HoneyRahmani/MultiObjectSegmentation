
## Table of Content
> * [Multi Object Segmentation - Pytorch](# MultiObjectSegmentation-Pytorch)
>   * [About the Project](#AbouttheProject)
>   * [About Database](#AboutDatabases)
>   * [Built with](#Builtwith)
>   * [Installation](#Installation)
>   * [Examples](#Example)

# Multi Object Segmentation - Pytorch
## About the Project
This project focuses on developing a deep-learning model using PyTorch to outline the boundary of target objects in an image by a same size segmentation mask image. The segmentation mask is an image that each pixel in the image is labeled based on its object class. Thus, the task is multi-object segmentation and goal is to predict segmentation mask.
In this project, automatically segmenting 20 target objects in the Visual Object Classes (VOC) dataset is performed.

![recipe](https://user-images.githubusercontent.com/75105778/153649787-46a34ba4-83b7-4a1f-9e9f-87babf9a3d95.jpg)


## About Database

The VOC segmentation data is from the torchvision.datasets package.
For more information about VOC dataset, visit the following link: 
http:/ /host.robots.ox.ac.uk/pascal/VOC/ voc2012/ index. html.

## Built with
* Pytorch
* Model is DeepLabV3Net101.
* CrossEntropyLoss Loss function.
* Adam optimizer.

## Installation
    •	conda install pytorch torchvision cudatoolkit=coda version -c pytorch

## Examples


![mos1](https://user-images.githubusercontent.com/75105778/153681271-78f1d1b2-92e7-460e-8d99-a7672e814461.png)
