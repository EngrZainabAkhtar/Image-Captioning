# Image Captioning
This repository contains project files for Computer Vision, Nanodegree  via [Udacity](https://eu.udacity.com/course/computer-vision-nanodegree--nd891). 

## Project Overview
In this work we have to combine Deep Convolutional Nets for image classification  with Recurrent Networks for sequence modeling, to create a single network that generates descriptions of image using [COCO Dataset - Common Objects in Context](http://cocodataset.org/).

COCO is a large image dataset designed for object detection, segmentation, person keypoints detection, stuff segmentation, and caption generation. GPU Accelerated Computing (CUDA) is neccessery for this project.

<p align="center"> <img src="encoder-decoder.png" align="middle" alt="drawing" width="900px"> </p> 

Following are a few results obtained after training the model for 3 epochs.

Image | Caption 
--- | --- 
<img src="Surf.png" width="200"> | **Generated Caption:** a person riding a surf board on a wave
<img src="motorcycle.png" width="200"> | **Generated Caption:** a group of people riding motorcycles down a street
<img src="boy.png" width="200">  | **Generated Caption:** a young boy brushing his teeth with a toothbrush
<img src="vase.png" width="200"> | **Generated Caption:** a vase with a flower on a table

## References
[Microsoft COCO](https://arxiv.org/pdf/1405.0312.pdf), [arXiv:1411.4555v2 [cs.CV] 20 Apr 2015](https://arxiv.org/pdf/1411.4555.pdf) </li>
and [arXiv:1502.03044v3 [cs.LG] 19 Apr 2016](https://arxiv.org/pdf/1502.03044.pdf)

## Licence
This project is licensed under the terms of the [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
