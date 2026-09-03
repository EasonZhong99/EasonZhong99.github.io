---
title: 'CALIBURN: Self-Calibrated LLM Unlearning Alignment'

authors:
  - Zhengbang Yang
  - admin
  - Junyuan Hong
  - Zhuangdi Zhu

date: '2026-08-20T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-08-20T00:00:00Z'

# Publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 2026 Conference on Empirical Methods in Natural Language Processing (EMNLP)*
publication_short: In *EMNLP 2026 Main Conference*

abstract: |
  Pretrained knowledge memorized in LLMs raises critical concerns over safety and privacy, which has motivated LLM Unlearning as a technique for selectively removing the influences of undesirable knowledge. Existing approaches, rooted in Gradient Ascent (GA), often degrade general domain knowledge while relying on retention data or curated contrastive pairs, which can be either impractical or data and computationally prohibitive. Negative Preference Alignment has been explored for unlearning to tackle the limitations of GA, which, however, remains confined by its choice of reference model and shows undermined performance in realistic data settings. These limitations raise two key questions: i) Can we achieve effective unlearning that quantifies model confidence in undesirable knowledge and uses it to calibrate gradient updates more precisely, thus reducing catastrophic forgetting? ii) Can we make unlearning robust to data scarcity and length variation? We answer both questions affirmatively with CALIBURN, a self-calibrated and tokenized alignment objective that rescales unlearning effects in proportion to the model's own token-level confidence, thus ensuring fine-grained control over forgetting. Extensive evaluations on the MUSE and WMDP benchmarks demonstrate that our method enables effective unlearning without requiring retention data or contrastive unlearning response pairs, achieving stronger knowledge forgetting and preservation trade-offs than state-of-the-art methods.

summary: A self-calibrated, token-level unlearning objective that uses the model's own confidence to focus forgetting on high-confidence undesirable tokens — improving the forgetting/utility trade-off without retention data or external reference models.

tags:
  - Large Language Models
  - Machine Unlearning
  - Preference Alignment
  - Trustworthy AI

# Display this page in the Featured widget?
featured: true

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: []
slides: ''
---
