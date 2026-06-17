---
title: 'TopoMix: Continuous Spatial Mixing for Long-Tailed Data Augmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yusen Wu
  - Zihui Ling

# Author notes (optional)
author_notes:
  - 'First author'
  - 'Second author'
  - 'Third author'

date: '2026-04-16T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-04-16T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2026 IEEE International Conference on Systems, Man, and Cybernetics (SMC).*
publication_short: In *SMC 2026*

abstract: Most mixing-based augmentation methods improve generalization through a simple idea, combine two training samples with a fixed global ratio or a hard spatial replacement. While effective, this design leaves little room for local variation, which becomes a more visible limitation in long-tailed recognition, where minority classes are especially sensitive to the quality of augmented samples. We propose TopoMix, a training-free augmentation method that replaces fixed mixing with continuous spatial mixing. TopoMix constructs a smooth spatially varying mask from a low-resolution random control grid, bicubic interpolation, and stochastic non-linear shaping, and uses this mask for element-wise image mixing and label reweighting. Without introducing trainable parameters or auxiliary networks, TopoMix offers a simple way to make mixing more flexible in the input space. Experiments on standard long-tailed benchmarks show that it consistently improves over representative mixing-based baselines, indicating that smooth spatial mixing is an effective augmentation strategy for long-tailed recognition.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Image Processing and Pattern Recognition

# Display this page in the Featured widget?
featured: false

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
