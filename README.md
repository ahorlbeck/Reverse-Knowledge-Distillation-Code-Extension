
This repository extends the work done by Deng and Li and their work on anomaly detection:
"Anomaly Detection via Reverse Distillation From One-Class Embedding".

@InProceedings{Deng_2022_CVPR,
author    = {Deng, Hanqiu and Li, Xingyu},
title     = {Anomaly Detection via Reverse Distillation From One-Class Embedding},
booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
month     = {June},
year      = {2022},
pages     = {9737-9746}}


## Original Repository
https://github.com/hq-deng/RD4AD


## Extended Features
I have added the following features:
- AdamW instead of Adam to add further regularization
- Data augmentation like Flips, Rotation and Color Jitter
- Coordinate Layers (An Intriguing Failing of Convolutional Neural Networks and the CoordConv Solution by Liu et al.),
      @misc{liu2018intriguingfailingconvolutionalneural,
      title={An Intriguing Failing of Convolutional Neural Networks and the CoordConv Solution}, 
      author={Rosanne Liu and Joel Lehman and Piero Molino and Felipe Petroski Such and Eric Frank and Alex Sergeev and Jason Yosinski},
      year={2018},
      eprint={1807.03247},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/1807.03247}, 
       }

The .py-files of the original repo, that are adapted with the extended features, are listed here, for all .py files, see the original repo.
One notebook file, that entails the whole pipeline is added additionally.
