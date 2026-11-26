---
title: 'Self-Anchored Reference Distributions for Multi-Objective Foundation Model Alignment'

authors:
  - admin
  - Sijia Liu
  - Zhuangdi Zhu

date: '2026-09-25T00:00:00Z'
publishDate: '2026-11-26T00:00:00Z'

publication_types: ['article']

publication: Under review
publication_short: Under review

abstract: |
  Foundation model (FM) alignment is inherently a multi-objective optimization problem that requires balancing competing goals, such as suppressing undesirable behaviors while complying with legitimate requests. Existing solutions typically optimize weighted combinations of objective-specific losses or reconcile conflicting gradients, but often require extensive hyperparameter tuning and may favor certain sub-objectives. We identify a central need for effective multi-objective alignment: characterizing an ideal posterior distribution of each alignment objective that provides richer supervision while reducing negative transfer. Motivated by FMs' few-shot learning ability to produce steerable predictive distributions, we propose a divide and conquer strategy that constructs objective-specific supervision from the target model itself. Specifically, the model is conditioned on goal-specific instructions, which generates self-supervised teacher distribution that better characterizes the target distribution yet mitigates the distributional divergence across alignment goals. We evaluate our method in two settings where goal conflicts are especially pronounced: unlearning and safety alignment. Comprehensive evaluations show that our method achieves the strongest overall balance among competing objectives without sacrificing performance on individual learning objectives.

summary: A divide-and-conquer approach to multi-objective alignment that builds objective-specific teacher distributions from the target model itself, conditioned on goal-specific instructions, achieving the strongest overall balance among competing objectives in unlearning and safety alignment.

tags:
  - Large Language Models
  - Safety Alignment
  - Multi-Objective Alignment
  - Post-Training

featured: true

url_pdf: ''
url_code: ''
---
