---
title: 'Hull First, Wake Second: Wake-Reliance Suppression for Robust Maritime Vessel Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Xingyu Wang
  - Ruibiao Zhu

# Author notes (optional)
author_notes:
  - 'First author'
  - 'Second author'
  - 'Third author'

date: '2026-08-12T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-08-12T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The 14th International Conference on Image and Graphics (ICIG).*
publication_short: In *ICIG 2026*

abstract: Maritime vessel detectors often face scenes where hulls are small, low-contrast, or blurred, while wakes are longer and easier to detect. This creates a wake-reliance problem that detectors may miss slow or stationary vessels with weak wakes, or produce false positives on wake-like water clutter. We propose HullWake, a hull-first wake-second framework for robust maritime vessel detection. HullWake separates proposal-centered hull evidence from directional wake context, extracts wake cues with bidirectional proposal-anchored corridors, and suppresses wake-dominant predictions through wake response supervision, wakeattenuated consistency, wake-only confidence suppression, and hull–wake decorrelation. We also introduce a wake-oriented evaluation protocol covering weak/no-wake vessels, wake-like hard negatives, worst-group AP, and confidence drop after wake attenuation. Experiments are conducted on Curated-Wake, a wake-oriented maritime dataset of about 10,000 images curated from Ships/Vessels in Aerial Images, the SMD benchmark, and SeaDronesSee, with newly added detection- and segmentation-level wake annotations. Compared with box-only detectors and mask-supervised segmentation baselines, HullWake improves overall AP, weak/no-wake robustness, wake-like false positives, worst-group AP, and confidence stability after wake attenuation.

# Summary. An optional shortened abstract.
summary: None

tags:
  - Image Processing and Pattern Recognition

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    arxiv: 'https://arxiv.org/abs/2608.26665'

# Custom links
links:
  - type: pdf
    url: ""
  - type: code
    url: "https://github.com/prettyyefan/HullWake"
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
