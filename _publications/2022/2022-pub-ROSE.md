---
title:          "ROSE: Robust Selective Fine-tuning for Pre-trained Language Models"
date:           2022-12-12
selected:       true
pub:            "The Conference on Empirical Methods in Natural Language Processing (EMNLP)"
pub_date:       "2022"
# semantic_scholar_id: 175b32c07e56f881479be4c5a74bfa3c731cc454  # use this to retrieve citation count
abstract: >-
  Even though large-scale language models have achieved excellent performance,
  they suffer from various adversarial attacks. A large body of defense methods
  has been proposed, but they are still limited due to redundant attack search
  spaces and the inability to defend against diverse attack types.
  In this work, we present a novel fine-tuning approach called RObust SElective
  fine-tuning (ROSE) to address this issue. ROSE conducts selective updates when
  adapting pre-trained models to downstream tasks, filtering out invaluable and
  unrobust parameter updates. Specifically, we propose two strategies:
  first-order and second-order ROSE, for selecting target robust parameters.
  Experimental results show that ROSE achieves significant improvements in
  adversarial robustness on various downstream NLP tasks, and the ensemble
  method even surpasses both variants above. Furthermore, ROSE can be easily
  incorporated into existing fine-tuning methods to further improve adversarial
  robustness. Empirical analysis confirms that ROSE eliminates unrobust spurious
  updates during fine-tuning, leading to solutions corresponding to flatter and
  wider optima than the conventional method. Code is available at
  https://github.com/jiangllan/ROSE.

cover:          /assets/images/covers/rose-cover.png
authors:
  - Lan Jiang*
  - Hao Zhou*
  - Yankai Lin
  - Peng Li
  - Jie Zhou
  - Rui Jiang
links:
  Paper: https://aclanthology.org/2022.emnlp-main.186.pdf
  Code: https://github.com/jiangllan/ROSE
---