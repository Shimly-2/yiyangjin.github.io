---
title:           ReVeal: Self-Evolving Code Agents via Iterative Generation-Verification
date:           2025-06-19 00:01:00 +0800
selected:       true
pub:            "Arxiv"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-custom badge-secondary">Conference</span>'
pub_date:       "2025"

abstract: >-
  Recent advances in reinforcement learning (RL) with verifiable outcome rewards have significantly improved the reasoning capabilities of large language models (LLMs), especially when combined with multi-turn tool interactions. However, existing methods lack both meaningful verification signals from realistic environments and explicit optimization for verification, leading to unreliable self-verification. To address these limitations, we propose ReVeal, a multi-turn Reinforcement learning framework that interleaves code generation with explicit self-Verification and tool-based evaluation. ReVeal enables LLMs to autonomously generate test cases, invoke external tools for precise feedback, and improves performance via a customized RL algorithm with dense, per-turn rewards. As a result, ReVeal fosters the co-evolution of a model’s generation and verification capabilities through RL training, expanding the reasoning boundaries of the base model, demonstrated by significant gains in Pass@k on LiveCodeBench. It also enables test-time scaling into deeper inference regimes, with code consistently evolving as the number of turns increases during inference, ultimately surpassing DeepSeek-R1-Zero-Qwen- 32B. These findings highlight the promise of ReVeal as a scalable and effective paradigm for building more robust and autonomous AI agents.



cover:          assets/images/covers/nerlps.png
authors:
  - Yiyang Jin*
  - Kunzhao Xu*
  - Hang Li  
  - Xueting Han†
  - Yanmin Zhou
  - Jiaxuan Lu
  - Cheng Li
  - Jing Bai
links:
  Paper: https://arxiv.org/abs/2506.11442
  
---


