---
title: 'Task-Aware KV Cache Compression for LLM Agents via Utility-Driven Step Pruning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yusen Wu
  - admin
  - Jia Yee Tan
  - Guangyuan Dong
  - Shuang Chen
  - Jing Yangum
  - Rongfeng Guo
  - Por Lip Yee
  - Yongtai Liu

# Author notes (optional)
author_notes:
  - 'First author'
  - 'Second author'
  - 'Third author'
  - 'Fourth author'
  - 'Fifth author'
  - 'Sixth author'
  - 'Seventh author'
  - 'Eighth author'
  - 'Ninth author'

date: '2026-09-15T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-09-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The Fortieth Annual Conference on Neural Information Processing Systems (NeurIPS).*
publication_short: In *NeurIPS 2026*

abstract:  KV-cache compression for long-horizon LLM agents is often guided by accumulated attention, yet attention frequency can retain repetitive error traces while discarding decisive instructions. We propose TaskKV, a streaming step-level retention policy with three contributions, (1) a signed directional utility label from the first-order change in action likelihood, distinguishing helpful steps from confusing distractors unlike unsigned saliency; (2) a structured residual scorer that treats attention mass and intent alignment as fixed priors and learns only a denoising correction, converging with 500 trajectories; and (3) an entropy-based regime classifier that falls back to contiguous retention when the scorer cannot confidently rank steps. With a 20% KV budget on AgentBench and AlfWorld, TaskKV preserves ~ 87--89% of full-cache success rate, improving over SnapKV by 5.0--7.9 SR points and over a strong heuristic by 2.9--7.3 points; on dense tasks, gains come from detecting when utility pruning should be disabled. 

# Summary. An optional shortened abstract.
summary: None

tags:
  - Language and multimodal language models

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    arxiv: ''

# Custom links
links:
  - type: pdf
    url: ""
  - type: code
    url: ""
  - type: dataset
    url: ""
  - type: slides
    url: ""
  - type: source
    url: ""
  - type: video
    url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

> [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
