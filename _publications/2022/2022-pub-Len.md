---
title:          "On Length Divergence Bias in Textual Matching Models"
date:           2022-05-05
selected:       true
pub:            "The Annual Meeting of the Association for Computational Linguistic (ACL) Findings"
pub_date:       "2022"
# semantic_scholar_id: 175b32c07e56f881479be4c5a74bfa3c731cc454  # use this to retrieve citation count
abstract: >-
  Despite the remarkable success deep models have achieved in Textual Matching (TM) tasks, it still remains unclear whether they truly understand language or measure the semantic similarity of texts by exploiting statistical bias in datasets.
  In this work, we provide a new perspective to study this issue --- via the length divergence bias.
  We find the length divergence heuristic widely exists in prevalent TM datasets, providing direct cues for prediction. 
  To determine whether TM models have adopted such heuristic, we introduce an adversarial evaluation scheme which invalidates the heuristic.
  In this adversarial setting, all TM models perform worse, indicating they have indeed adopted this heuristic.
  Through a well-designed probing experiment, we empirically validate that the bias of TM models can be attributed in part to extracting the text length information during training.
  To alleviate the length divergence bias, we propose an adversarial training method. 
  The results demonstrate we successfully improve the robustness and generalization ability of models at the same time.

cover:          /assets/images/covers/len-cover.png
authors:
  - Lan Jiang
  - Tianshu Lyu
  - Yankai Lin
  - Meng Chong
  - Xiaoyong Lyu
  - Dawei Yin
links:
  Paper: https://aclanthology.org/2022.findings-acl.330.pdf
  Code: https://github.com/jiangllan/LengthBias
---