---
title:          "Hunyuan-TurboS: Advancing Large Language Models through Mamba-Transformer Synergy and Adaptive Chain-of-Thought"
date:           2025-07-08
selected:       true
# pub:            "International Conference on Machine Learning (ICML)"
pub_pre:        "Arxiv"
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"
# semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776  # use this to retrieve citation count
abstract: >-
  As Large Language Models (LLMs) rapidly advance, we introduce Hunyuan-TurboS,
  a novel large hybrid Transformer-Mamba Mixture of Experts (MoE) model. It synergistically combines Mamba’s long-sequence processing efficiency with Transformer’s superior contextual understanding. Hunyuan-TurboS features an adaptive long-short chain-of-thought (CoT) mechanism, dynamically switching between rapid responses for simple queries and deep ”thinking” modes for complex problems, optimizing computational resources. Architecturally, this 56B activated (560B total) parameter model employs 128 layers (Mamba2, Attention, FFN) with an innovative AMF/MF block pattern. Faster Mamba2 ensures linear complexity, Grouped-Query Attention minimizes KV cache, and FFNs use an MoE structure. Pre-trained on 16T high-quality tokens, it supports a 256K context length and is the first industry-deployed large-scale Mamba model. Our comprehensive post-training strategy enhances capabilities via Supervised Fine-Tuning (3M instructions), a novel Adaptive Long-short CoT Fusion method, Multiround Deliberation Learning for iterative improvement, and a two-stage Large-scale
  Reinforcement Learning process targeting STEM and general instruction-following. Evaluations show strong performance: overall top 7 rank on LMSYS Chatbot Arena with a score of 1356, outperforming leading models like Gemini-2.0-Flash-001 (1352) and o4-mini-2025-04-16 (1345). TurboS also achieves an average of 77.9% across 23 automated benchmarks. Hunyuan-TurboS balances high performance and efficiency, offering substantial capabilities at lower inference costs than many reasoning models, establishing a new paradigm for efficient large-scale pre-trained models.
cover:          /assets/images/covers/turbos-cover.png
authors:
  - Hunyuan Team
links:
  Paper: https://arxiv.org/pdf/2505.15431
  Blog: https://mp.weixin.qq.com/s/TGtOpYc_2IFBRrqSkwU_1A
---
