---
title: 'DUET: Distilled LLM Unlearning from an Efficiently Contextualized Teacher'
authors:
  - Yisheng Zhong
  - Zhengbang Yang
  - Zhuangdi Zhu

date: '2025-10-10T00:00:00Z'
publishDate: '2025-10-10T00:00:00Z'
publication_types: ['paper-conference']
publication: "*ICLR 2026* Accepted"

abstract: |
  DUET introduces an LLM unlearning pipeline where an efficiently contextualized teacher demonstrates refusals on undesirable knowledge and distills those behaviors into a student model. By swapping full-vocabulary KL with **Top-K logit alignment**, DUET preserves utility while surgically forgetting risky content. On MUSE, the method lowers leakage by 4% (ROUGE-Forget) and improves retention by 10% (ROUGE-Retain/MMLU) while consuming only 2,233 training tokens (~1/645 of the corpus). Robustness studies show DUET resists reverse prompts and QA-to-continuation format shifts better than baselines.

tags:
  - LLM Unlearning
  - Safety Alignment
  - Knowledge Defense
featured: true
url_pdf: https://openreview.net/pdf?id=Xa6QRrXrKX
url_code: ''
url_dataset: ''
url_project: /project/llm-unlearning-duet/
url_slides: ''
projects:
  - llm-unlearning-duet
---
