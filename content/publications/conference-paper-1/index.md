---
title: 'Role-Aware Tactile Path Perception from UAV Videos via Motion-Semantic Guidance'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yusen Wu
  - Lingling Qu

# Author notes (optional)
author_notes:
  - 'First author'
  - 'Second author'
  - 'Third author'

date: '2026-03-26T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-03-26T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Artificial Neural Networks 2026*
publication_short: In *ICANN 2026*

abstract: Tactile paving in urban scenes is often affected by parked objects, moving pedestrians, and shadow-like interference. Although UAV inspection offers a flexible solution for accessibility monitoring, aerial tactile-path perception remains difficult because visually similar regions may play very different roles for traversability. We formulate this task as role-aware tactile-path perception rather than category-only recognition and propose a SAM2-based framework with motion-semantic guidance. Specifically, optical flow is used to derive region-level motion cues, which are converted into soft role priors and fused with tactile-path spatial cues and altitude information for role-aware segmentation. To support this task, we build UTP-9K, a UAV benchmark covering stationary blockage, moving targets, and shadow-like artifacts under different flight heights and scene conditions. Experiments show that the proposed method improves both obstacle perception and role-aware perception while effectively reducing false alarms under aerial viewpoints. These results suggest that motion-aware role reasoning is more suitable than appearance-only prediction for UAV-based tactile-path monitoring.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Advances in Artificial Intelligence, Remote Sensing and Signal Processing for Urban and Earth Applications

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
    url: "https://github.com/prettyyefan/UTP-9K"
  - type: dataset
    url: "https://huggingface.co/datasets/prettyyefan/UTP-9K"
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
