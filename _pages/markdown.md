---
layout: archive
title: "Research"
permalink: /markdown/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Selected research projects since joining industry (2022–present), spanning efficient foundation models, generative/agentic AI, and Physical AI / robot learning. See the full list on the [Publications](/publications/) page.

<p float="left">
  <img src="https://human2bots.github.io/static/images/system_overview.png" width="300" align="left" style="margin-right: 2em"/>
</p>
<em>Human2LocoMan: Learning Versatile Quadrupedal Manipulation with Human Pretraining</em> (RSS 2025)
<br/>
A cross-embodiment imitation-learning pipeline for the LocoMan quadruped: pretrains a Modularized Cross-Embodiment Transformer on cheap human demonstrations collected via an XR headset, then fine-tunes on limited robot teleoperation data. Achieves 41.9% overall and 79.7% out-of-distribution success-rate improvements over baselines, matching baseline performance using only half the robot data. With Prof. Ding Zhao (CMU).
<br/><br/>

<p float="left">
  <img src="https://raw.githubusercontent.com/xidongwu/AutoTrainOnce/main/overview/ATO_figs.png" width="300" align="left" style="margin-right: 2em"/>
</p>
<em>Auto-Train-Once: Controller Network Guided Automatic Network Pruning from Scratch</em> (CVPR 2024)
<br/>
Jointly trains a target model and a controller network from scratch, where the controller generates masks to guide pruning — removing the need for pretraining, fine-tuning, or hand-designed pruning schedules. Achieves state-of-the-art compression/accuracy trade-offs on ResNet/MobileNet across CIFAR-10/100 and ImageNet, with theoretical convergence guarantees.
<br/><br/>

<p float="left">
  <img src="https://raw.githubusercontent.com/boschresearch/FedTPG/main/images/train_overview.png" width="300" align="left" style="margin-right: 2em"/>
</p>
<em>Federated Text-Driven Prompt Generation for Vision-Language Models (FedTPG)</em> (ICLR 2024)
<br/>
Learns a single, unified prompt-generation network shared across federated clients, conditioned on task-related text so prompts stay context-aware. Generalizes better to unseen classes and unseen datasets than prior federated prompt-learning methods, across nine image classification benchmarks.
<br/><br/>

<p float="left">
  <img src="https://ar5iv.labs.arxiv.org/html/2311.08479/assets/images/sota.png" width="300" align="left" style="margin-right: 2em"/>
</p>
<em>Leveraging Foundation Models to Improve Lightweight Clients in Federated Learning</em> (NeurIPS Workshop FL@FM 2023)
<br/>
Distills knowledge from large foundation models into lightweight client models during federated training, improving performance on rare/underrepresented classes under heterogeneous (non-IID) client data, without increasing client-side inference cost.
<br/><br/>

<p float="left">
  <img src="https://ar5iv.labs.arxiv.org/html/2509.14543/assets/figures/methodologyIllustration.png" width="300" align="left" style="margin-right: 2em"/>
</p>
<em>Catch Me If You Can? Not Yet: LLMs Still Struggle to Imitate the Implicit Writing Styles of Everyday Authors</em> (Findings of EMNLP 2025)
<br/>
Evaluates whether LLMs can imitate an individual writer's implicit style from few-shot examples, testing 40,000+ generations across 400+ real authors in news, email, forum, and blog domains. Finds LLMs do reasonably well in structured genres (news, email) but struggle in informal, nuanced writing (blogs, forums). With Prof. Jiawei Zhou (Stony Brook).
<br/><br/>
