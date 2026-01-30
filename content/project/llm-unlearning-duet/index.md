---
title: 'DUET — ICLR 2026 Accepted'
date: 2025-10-10
summary: 'Prompt-conditioned teacher distillation for targeted forgetting with Top-K logit alignment.'
show_date: false
tags:
  - LLM Unlearning
  - Alignment

links:
  - icon: file
    icon_pack: fas
    name: Manuscript
    url: https://drive.google.com/file/d/1HtOBAmisNKRjS7GjJCnbXQ8Pf9th2djh/view?usp=sharing
  - icon: academic-cap
    icon_pack: fas
    name: Publication Entry
    url: /publication/duet/
---

DUET introduces an efficiently contextualized teacher that demonstrates refusals on unsafe knowledge and distills the behavior to a student model using **Top-K logit alignment** instead of full-vocabulary KL. The approach:

- Achieves precise forgetting with minimal utility loss on MUSE, TOFU, and WMDP.
- Uses only 2,233 tokens of training data (~1/645 of the corpus) yet improves ROUGE-Retain/MMLU by 10% while lowering leakage by 4%.
- Remains robust when facing reverse prompts or QA→continuation format shifts, keeping leakage near 6–7 even when the teacher spikes to 37+.

Role: first author. I designed the unlearning objective, scaling recipe, and evaluation harness.
