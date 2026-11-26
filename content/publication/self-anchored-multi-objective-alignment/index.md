---
title: 'Self-Anchored Reference Distributions for Multi-Objective Foundation Model Alignment'

authors:
  - admin
  - Sijia Liu
  - Zhuangdi Zhu

date: '2026-09-25T00:00:00Z'
publishDate: '2026-11-26T00:00:00Z'

publication_types: ['article']

publication: Under review at *ICLR 2027*
publication_short: Under review at *ICLR 2027*

abstract: |
  Aligning a model with several goals at once, such as refusing harmful requests while staying helpful, often leads to conflicts where improving one objective hurts another. We identify the training signal itself, not just the optimizer, as a key source of this conflict: hard fine-tuning labels penalize equally valid responses. We propose Caesar, a post-training method in which the model, prompted per objective, serves as its own teacher, giving soft and mutually compatible targets with no extra teacher model or loss-weight tuning. Caesar cuts cross-objective interference by about 70% compared with standard fine-tuning and reduces jailbreak success from 60.6% to 2.0% with benign refusals nearly unchanged, and it remains effective with as few as 160 training examples.

summary: Caesar uses the model itself, prompted per objective, as a self-anchored teacher for multi-objective alignment, cutting cross-objective interference by ~70% and jailbreak success from 60.6% to 2.0%.

tags:
  - Large Language Models
  - Safety Alignment
  - Multi-Objective Alignment
  - Post-Training

featured: true

url_pdf: ''
url_code: ''
---
