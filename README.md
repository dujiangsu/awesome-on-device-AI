# Welcome to Awesome On-device AI
![Awesome](https://awesome.re/badge.svg) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/ysyisyourbrother/awesome-mlsys-mobile/pulls)

A curated list of awesome projects and papers for AI on **Mobile/IoT/Edge** devices. Everything is continuously updating. Welcome contribution!

## Contents

- [Papers](#papers)
  - [Learning on Devices](#1-learning-on-devices)
  - [Inference on Devices](#2-inference-on-devices)
  - [Models for Mobile](#3-model-for-mobile)
- [Open Source Projects](#open-source-projects)
	- [DL Framework on Mobile](#1-DL-Framework-on-Mobile)
  - [Inference Deployment](#2-Inference-Deployment)
  - [Open Source Auto-Parallelism Framework](#3-Open-Source-Auto-Parallelism-Framework)
- [Contribute](#Contribute)

## Papers

### 1. Learning on Devices

#### 1.1 Memory Efficient Learning

- [POET: Training Neural Networks on Tiny Devices with Integrated Rematerialization and Paging](https://proceedings.mlr.press/v162/patil22b/patil22b.pdf) by Patil et al., ICML 2022
- [On-Device Training Under 256KB Memory](https://arxiv.org/pdf/2206.15472.pdf) by Ji Lin, Song Han et al., NIPS 2022
- [Melon: breaking the memory wall for resource-efficient on-device machine learning](https://xumengwei.github.io/files/MobiSys22-Melo.pdf) by Qipeng Wang et al., MobiSys 2022
- [Sage: Memory-efficient DNN Training on Mobile Devices](https://dl.acm.org/doi/abs/10.1145/3498361.3539765) by In Gim et al., MobiSys 2022

#### 1.2 Learning Acceleration

- [Mandheling: Mixed-Precision On-Device DNN Training with DSP Offloading](http://arxiv.org/abs/2206.07509) by Daliang Xu et al., MobiCom 2022

#### 1.3 Learning on Mobile Cluster

- Eco-FL: Adaptive Federated Learning with Efficient Edge Collaborative Pipeline Training. by Shengyuan Ye et al., ICPP 2022 [[code](https://github.com/ysyisyourbrother/Federated-Learning-Research.git)] [[paper](https://ssl.linklings.net/conferences/icpp/icpp2022_program/views/includes/files/pap117s3-file1.pdf)]
- [EDDL: A Distributed Deep Learning System for Resource-limited Edge Computing Environment](https://buzhangy.github.io/publication/eddl-sec21.pdf) by Pengzhan Hao et al., SEC 2021

#### 1.4 Measurement and Survey

- [Towards Ubiquitous Learning: A First Measurement of On-Device Training Performance](https://dl.acm.org/doi/10.1145/3469116.3470009) by Dongqi Chai, Mengwei Xu et al., Mobisys 2021 Workshop

### 2. Inference on Devices

#### 2.1 Collaborative Inference

- [CoDL: efficient CPU-GPU co-execution for deep learning inference on mobile devices](https://chrisplus.me/assets/pdf/mobisys22-CoDL.pdf) by Fucheng Jia et al., MobiSys 2022
- [Distributed Inference with Deep Learning Models across Heterogeneous Edge Devices](https://iqua.ece.toronto.edu/papers/chenghao-infocom22.pdf) by Chenghao hu et al., InfoCom 2022
- [Coedge: Cooperative dnn inference with adaptive workload partitioning over heterogeneous edge devices](https://ieeexplore.ieee.org/abstract/document/9296560/) by Liekang Zeng et al., TON 2020
- [Model Parallelism Optimization for Distributed Inference via Decoupled CNN Structure](https://ieeexplore.ieee.org/document/9275375/) by Jiangsu Du et al., TPDS 2020
- [μLayer: Low Latency On-Device Inference Using Cooperative Single-Layer Acceleration and Processor-Friendly Quantization](https://dl.acm.org/doi/abs/10.1145/3302424.3303950) by Youngsok Kim et al., EuroSys 2019
- [DeepThings: Distributed Adaptive Deep Learning Inference on Resource-Constrained IoT Edge Clusters](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8493499) by zhuoran Zhao et al., TCAD 2018
- [Modnn: Local distributed mobile computing system for deep neural network](https://ieeexplore.ieee.org/abstract/document/7927211/) by Jiachen Mao et al., DATE 2017

#### 2.2 Latency Prediction for Inference

- [nn-Meter: towards accurate latency prediction of deep-learning model inference on diverse edge devices](https://dl.acm.org/doi/abs/10.1145/3458864.3467882) by Li Lyna Zhang et al., MobiSys 2021

### 3. Models for Mobile

#### 3.1 Lightweight Model

- [MobileBERT: a Compact Task-Agnostic BERT for Resource-Limited Devices](https://arxiv.org/pdf/2004.02984.pdf) by Zhiqing Sun et al., ACL 2020
- [EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks](http://proceedings.mlr.press/v97/tan19a/tan19a.pdf) by Mingxing Tan et al., ICML 2019
- [Shufflenet: An extremely efficient convolutional neural network for mobile devices](http://openaccess.thecvf.com/content_cvpr_2018/html/Zhang_ShuffleNet_An_Extremely_CVPR_2018_paper.html) by Xiangyu Zhang et al., CVPR 2018
- [MobileNetV2: Inverted Residuals and Linear Bottlenecks](https://openaccess.thecvf.com/content_cvpr_2018/papers/Sandler_MobileNetV2_Inverted_Residuals_CVPR_2018_paper.pdf) by Mark Sandler et al., CVPR 2018

### 4. On-device AI Application

#### 4.1 On-device NLP

- [DeepType: On-Device Deep Learning for Input Personalization Service with Minimal Privacy Concern](https://dl.acm.org/doi/10.1145/3287075) by Mengwei Xu et al., Ubicomp 2018
- [Federated learning for mobile keyboard prediction](https://arxiv.org/abs/1811.03604) by Google, Arrive 2018

## Open Source Projects

### 1. DL Framework on Mobile

- Tensorflow Lite: Deploy machine learning models on mobile and edge devices. by Google. [[code](https://www.tensorflow.org/lite)]
- TensorflowJS: A WebGL accelerated JavaScript library for training and deploying ML models. by Google. [[code](https://github.com/tensorflow/tfjs)]
- MNN: A Universal and Efficient Inference Engine. by Alibaba. [[code](https://github.com/alibaba/MNN)]

### 2. Inference Deployment

- TensorRT: A C++ library for high performance inference on NVIDIA GPUs and deep learning accelerators. by Nvidia. [[code](https://github.com/NVIDIA/TensorRT)]
- TVM: Open deep learning compiler stack for cpu, gpu and specialized accelerators. by Tianqi Chen et al. [[code](https://github.com/apache/tvm)]
- MACE: a deep learning inference framework optimized for mobile heterogeneous computing platforms. by XiaoMi. [[code](https://github.com/XiaoMi/mace)]
- NCNN: a high-performance neural network inference framework optimized for the mobile platform. by Tencent. [[code](https://github.com/Tencent/ncnn)]

### 3. Open Source Auto-Parallelism Framework

#### 3.1 Pipeline Parallelism

- Pipeline Parallelism for PyTorch by **Pytorch**. [[code](https://github.com/pytorch/PiPPy)]
- A Gpipe implementation in Pytorch by Kakaobrain. [[code](https://github.com/kakaobrain/torchgpipe)]



## Contribute

All contributions to this repository are welcome. Open an [issue](https://github.com/ysyisyourbrother/awesome-mlsys-mobile/issues) or send a [pull request](https://github.com/ysyisyourbrother/awesome-mlsys-mobile/pulls).
