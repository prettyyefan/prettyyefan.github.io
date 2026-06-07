---
title: 'PRGCD: Probabilistic Representation Learning for Generalized Category Discovery'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yiming Han
  - Jiayang Cheng
  - admin

# Author notes (optional)
author_notes:
  - 'First author'
  - 'Second author'
  - 'Third author'

date: '2025-12-11T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-12-11T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The IEEE International Conference on Multimedia & Expo 2026*
publication_short: In *ICME 2026*

abstract: Generalized Category Discovery (GCD) aims to classify unlabeled images from both known and novel categories, leveraging partially labeled data. Existing methods predominantly rely on deterministic contrastive learning, which represents each sample as a single point embedding and measures similarity through point-to-point distances. We argue that this paradigm is inherently limited, as it provides only one degree of freedom for optimization. In this paper, we propose PRGCD, a novel framework that models each sample as a Gaussian distribution parameterized by mean and variance. We adopt the 2-Wasserstein distance for distribution-level similarity, which naturally decomposes into location and spread terms, enabling dual consistency enforcement. Based on this formulation, we design Wasserstein Unsupervised Contrastive (WUC) loss and Wasserstein Supervised Contrastive (WSC) loss for representation learning, along with a distribution calibration loss to prevent posterior collapse. Extensive experiments on six benchmarks demonstrate that PRGCD achieves state-of-the-art performance.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Analysis and Understanding

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
