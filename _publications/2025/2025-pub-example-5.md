---
title:          Bridging Offline and Online Learning: Reinforcement Learning-Enhanced Robot Vision and Language Manipulation  
date:           2025-08-10 00:01:00 +0800
selected:       true
pub:            "Arxiv"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-custom badge-secondary">Conference</span>'
pub_date:       "2025"

abstract: >-
  Recent advances in robot manipulation have demonstrated the potential of combining offline pre-training with online fine-tuning, yet existing approaches struggle with sparse reward signals, inefficient data utilization, and the challenge of maintaining stable learning dynamics when transitioning from offline to online regimes. To address these limitations, we propose a reinforcement learning-enhanced framework that bridges offline and online learning for robot vision and language manipulation tasks. Our approach introduces an asynchronous data generation pipeline with trajectory caching and a novel Rollout Relabel strategy that effectively leverages failed trajectories to combat sparse rewards, achieving 1.25× training efficiency improvements. Building upon the OpenVLA model, we design a unified training paradigm that synchronously processes both high-quality offline trajectory data and online exploration data, while dynamically adjusting the exploration-imitation balance to optimize learning progression. To mitigate entropy collapse during the offline-to-online transition, we incorporate importance sampling regularization that preserves the valuable knowledge from offline data while enabling effective online adaptation. Using binary outcome rewards, our method employs Generalized Reward-weighted Policy Optimization (GRPO) to surpass supervised fine-tuning baselines, demonstrating an average 4.2% performance improvement across four LIBERO benchmark tasks. 



cover:          assets/images/covers/iclr.png
authors:
  - Yanmin Zhou*  
  - Yiyang Jin  
  - Rong Jiang  
  - Xin Li  
  - Hongrui Sang  
  - Shuo Jiang  
  - Zhipeng Wang†  
  - Bin He
# links:
#   Dataset: https://huggingface.co/datasets/xsdfasfgsa/VLaPT
  
---


