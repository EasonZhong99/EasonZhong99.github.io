---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 Research Summary'
      subtitle: ''
      text: |-
        I am a PhD student in Cybersecurity at **George Mason University** (SPARK Lab, advised by Dr. Zhuangdi Zhu). My research centers on the security and privacy of large language models (LLMs), spanning **model unlearning**, **safety alignment**, and **defenses against LLM-driven content extraction**. I previously completed my Master's degree at the **University of Chinese Academy of Sciences**, where I worked on privacy-preserving and Byzantine-robust federated learning with cryptographic enforcement.

        I am always open to collaborations on secure foundation models—feel free to reach out!
    design:
      columns: '1'
  - block: markdown
    content:
      title: '🔍 Research Interests'
      subtitle: ''
      text: |-
        - Security & privacy of LLMs: unlearning, post-training alignment, misuse and leakage defenses.
        - Privacy-preserving & Byzantine-robust federated learning for mission-critical deployments.
    design:
      columns: '1'
  - block: collection
    id: news
    content:
      title: Recent News
      text: ""
      filters:
        folders:
          - post
        exclude_featured: false
    design:
      view: compact
  - block: collection
    id: papers
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    content:
      title: '🤝 Competitions & Service'
      subtitle: ''
      text: |-
        **Mathematical Contest in Modeling — Meritorious Winner (International First Prize, 2020).** Led a three-person team, coordinated modeling strategy, and implemented a 3D cellular automata system optimized via differential-equation-guided genetic search.

        **Academic Service.** Reviewer for ICLR 2024 and ICLR 2025.
    design:
      columns: '1'
  - block: markdown
    content:
      title: '🎖 Honors & Scholarships'
      subtitle: ''
      text: |-
        - Meritorious Winner, Mathematical Contest in Modeling (First Prize), 2020
        - Annual Scholarships, Chinese Academy of Sciences, 2021–2023
        - First-Class Scholarships, Harbin University of Science and Technology, 2017–2021
    design:
      columns: '1'
---
