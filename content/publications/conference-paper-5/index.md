---
title: 'GaugeDefect: Detecting Surface Anomalies by Curvature of Feature Transport'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
author_notes:
  - 'First author'

date: '2026-07-15T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-07-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: The 9th Chinese Conference on Pattern Recognition and Computer Vision PRCV 2026.*
publication_short: In *PRCV 2026*

abstract:  Industrial anomaly localization has advanced rapidly with feature-based, reconstruction-based, and distillation-based methods. Most of these methods score a region by asking how unusual its local appearance or feature representation is with respect to normal training images. This is a strong and practical formulation. In this work, we study a complementary geometric cue for cases where an abnormal region may still contain locally plausible visual features. Thin scratches, small dents, and disrupted repeated patterns often do not make every local patch individually abnormal; instead, they disturb how nearby features vary and connect across the surface. We propose GaugeDefect, a geometric method for surface anomaly localization based on the curvature of feature transport. Given a feature lattice, we estimate a local feature frame at each node and compute orthogonal transports between neighboring frames. The accumulated transport around a small closed loop gives a holonomy matrix, whose deviation from identity measures feature-transport curvature. After calibration on normal training images, unusually large curvature indicates a local inconsistency in the feature field. The curvature here is not the physical curvature of the inspected object, but a representation-space measure of neighborhood inconsistency. This makes the method applicable to curved surfaces, textured materials, and non-planar industrial objects. Its main role is to improve localization of subtle surface disruptions, while often producing sharper responses near defect boundaries as a natural consequence of the curvature signal.

# Summary. An optional shortened abstract.
summary: None

tags:
  - Image Processing and Pattern Recognition

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    arxiv: 'https://arxiv.org/abs/2609.13282'

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
