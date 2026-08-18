---
title: "Auto-Train-Once: Controller Network Guided Automatic Network Pruning from Scratch"
collection: publications
permalink: /publications/2024-cvpr-auto-train-once
excerpt: 'An automatic network-pruning method that jointly trains a target model and a controller network from scratch, removing the need for pretraining, fine-tuning, or manual pruning schedules, with theoretical convergence guarantees.'
date: 2024-01-01
venue: 'IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)'
citation: 'Xidong Wu, Shangqian Gao, Zeyu Zhang, Zhenzhen Li, Runxue Bao, Yanfu Zhang, Xiaoqian Wang, Heng Huang.'
paperurl: 'https://arxiv.org/abs/2403.14729'
---

[[arXiv]](https://arxiv.org/abs/2403.14729)

## Abstract
Auto-Train-Once (ATO) trains a target model and a controller network jointly from scratch — the controller generates masks that guide which weights to prune, eliminating the need for pretraining, fine-tuning, or hand-designed pruning schedules. ATO achieves state-of-the-art compression/accuracy trade-offs on ResNet/MobileNet architectures across CIFAR-10/100 and ImageNet.
