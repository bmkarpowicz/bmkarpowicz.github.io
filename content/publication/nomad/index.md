---
title: "Stabilizing brain-computer interfaces through alignment of latent dynamics"
authors:
- admin
- Yahia H. Ali
- Lahiru N. Wimalasena
- Andrew R. Sedler
- Mohammad Reza Keshtkaran
- Kevin Bodkin
- Xuan Ma
- Daniel B. Rubin
- Ziv M. Williams
- Sydney S. Cash
- Leigh R. Hochberg
- Lee E. Miller
- Chethan Pandarinath
date: "2025-05-19T00:00:00Z"
doi: "https://doi.org/10.1038/s41467-025-59652-y"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Intracortical brain-computer interfaces (iBCIs) restore motor function to people with paralysis by translating brain activity into control signals for external devices. In current iBCIs, instabilities at the neural interface result in a degradation of decoding performance, which necessitates frequent supervised recalibration using new labeled data. One potential solution is to use the latent manifold structure that underlies neural population activity to facilitate a stable mapping between brain activity and behavior. Recent efforts using unsupervised approaches have improved iBCI stability using this principle; however, existing methods treat each time step as an independent sample and do not account for latent dynamics. Dynamics have been used to enable high performance prediction of movement intention, and may also help improve stabilization. Here, we present a platform for Nonlinear Manifold Alignment with Dynamics (NoMAD), which stabilizes iBCI decoding using recurrent neural network models of dynamics. NoMAD uses unsupervised distribution alignment to update the mapping of nonstationary neural data to a consistent set of neural dynamics, thereby providing stable input to the iBCI decoder. In applications to data from monkey motor cortex collected during motor tasks, NoMAD enables accurate behavioral decoding with unparalleled stability over weeks-to months-long timescales without any supervised recalibration.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
- name: Nature Communications
  url: https://www.nature.com/articles/s41467-025-59652-y
url_pdf: https://www.nature.com/articles/s41467-025-59652-y.pdf
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

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
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
