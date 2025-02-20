---
title: "AdaOrb: Adapting In-Orbit Analytics Models for Location-aware Earth Observation Tasks"
authors:
- admin
date: "2025-02-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-03-20T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "Pervasive Computing and Communications"
publication_short: "PerCom 2025"

abstract: Satellite-based Earth observation provides aerial views of vast areas for various monitoring and analytics applications. The rapid growth in low-Earth-orbit satellites enables providing Earth observation applications to public users via a shared platform. However, the limited satellite-ground communication resources present a major challenge in downlinking and fully utilizing satellite-captured Earth observation data on the ground. As a new edge computing paradigm, orbital edge computing enables deploying lightweight deep learning models with satellite on-board computing resources for in-orbit data analysis, reducing downlink data volume and response time. However, the limited generalizability of lightweight in-orbit models and significant data distribution shifts across geographical locations on Earth severely impact the accuracy of in-orbit analytics. In this work, we design a framework, AdaOrb, which dynamically schedules model adaptation for location-specific Earth observation tasks. The adaptation is achieved via model retraining using online captured in-orbit data. Scheduling decisions are made with a model predictive control model that allocates limited downlink capacity for retraining data across onboard tasks. By developing and using a hardware-in-the-loop orbital edge computing testbed, we show that our methods achieve superior overall accuracy of in-orbit analytics tasks compared to alternative methods.

# Summary. An optional shortened abstract.
summary: 

tags:
- Orbital Edge Computing

featured: false

links:
- name: Custom Link
  url: http://example.org
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- oec

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
