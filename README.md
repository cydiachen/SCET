# Self-Calibrated Efficient Transformer for Lightweight Super-Resolution (official-Deployment)
## Introduction

We have implemented our SCET method through the [mmediting](https://github.com/open-mmlab/mmediting) and [mim](https://github.com/open-mmlab/mim) algorithm framework. Next, we will describe the main processes of training and testing.

- Paper The SCET has been accepted by CVPRW2022, you can read the [paper](https://arxiv.org/pdf/2204.08913.pdf) here.
- Model

![Network](./Image/Network.png)

In this repo, we will provide detailed code for deploy this image super-resolution model in ONNXRuntime, TensorRT and other platform. 

## Training Details

You can refer to our paper version repo [SCET](https://github.com/AlexZou14/SCET) for reimplementing this paper and train your own image super-resolution network. 

This repo mainly provides the detailed implementation for various kind of devices.

