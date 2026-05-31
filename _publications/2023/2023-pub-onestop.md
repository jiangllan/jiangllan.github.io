---
title:          "One-stop Training of Multiple Capacity Models"
date:           2023-05-24
selected:       false
pub_pre:        "arXiv"
pub_date:       "2023"
abstract: >-
  Training models with varying capacities can be advantageous for deploying them in different scenarios. 
  While high-capacity models offer better performance, low-capacity models require fewer computing resources for training and inference. 
  In this work, we propose a novel one-stop training framework to jointly train high-capacity and low-capactiy models. 
  This framework consists of two composite model architectures and a joint training algorithm called Two-Stage Joint-Training (TSJT).
  Unlike knowledge distillation, where multiple capacity models are trained from scratch separately, our approach integrates supervisions from different capacity models simultaneously, leading to faster and more efficient convergence.
  Extensive experiments on the multilingual machine translation benchmark WMT10 show that our method outperforms low-capacity baseline models and achieves comparable or better performance on high-capacity models. 
  Notably, the analysis demonstrates that our method significantly influences the initial training process, leading to more efficient convergence and superior solutions.
cover:          /assets/images/covers/onestop-cover.png
authors:
- Lan Jiang*
- Haoyang Huang*
- Dongdong Zhang
- Rui Jiang
- Furu Wei
links:
  Paper: https://arxiv.org/pdf/2305.14066
---