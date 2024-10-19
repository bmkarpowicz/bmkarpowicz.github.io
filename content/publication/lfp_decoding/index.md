---
title: "Few-shot Algorithms for Consistent Neural Decoding (FALCON) Benchmark"
authors:
- admin
- Bareesh Bhaduri
- Samuel R. Nason-Tomaszewski
- Brandon G. Jacques
- Yahia H. Ali
- Robert D. Flint
- Payton H. Bechefsky
- Leigh R. Hochberg
- Nicholas AuYong
- Marc W. Slutzky
- Chethan Pandarinath
date: "2024-10-18T00:00:00Z"
doi: "https://doi.org/10.1088/1741-2552/ad88a4"


# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Objective: Current intracortical brain-computer interfaces (iBCIs) rely predominantly on threshold crossings ("spikes") for decoding neural activity into a control signal for an external device. Spiking data can yield high accuracy online control during complex behaviors; however, its dependence on high-sampling-rate data collection can pose challenges. An alternative signal for iBCI decoding is the local field potential (LFP), a continuous-valued signal that can be acquired simultaneously with spiking activity. However, LFPs are seldom used alone for online iBCI control as their decoding performance has yet to achieve parity with spikes. Approach: Here, we present a strategy to improve the performance of LFP-based decoders by first training a neural dynamics model to use LFPs to reconstruct the firing rates underlying spiking data, and then decoding from the estimated rates. We test these models on previously-collected macaque data during center-out and random-target reaching tasks as well as data collected from a human iBCI participant during attempted speech. Main results: In all cases, training models from LFPs enables firing rate reconstruction with accuracy comparable to spiking-based dynamics models. In addition, LFP-based dynamics models enable decoding performance exceeding that of LFPs alone and approaching that of spiking-based models. In all applications except speech, LFP-based dynamics models also facilitate decoding accuracy exceeding that of direct decoding from spikes. Significance: Because LFP-based dynamics models operate on lower bandwidth and with lower sampling rate than spiking models, our findings indicate that iBCI devices can be designed to operate with lower power requirements than devices dependent on recorded spiking activity, without sacrificing high-accuracy decoding.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
- name: Journal of Neural Engineering
  url: https://doi.org/10.1088/1741-2552/ad88a4
# url_pdf: https://www.biorxiv.org/content/10.1101/2024.09.15.613126v1.full.pdf
# url_code: https://github.com/snel-repo/falcon-challenge
# url_dataset: https://snel-repo.github.io/falcon/datasets
# url_poster: '#'
# url_project: https://snel-repo.github.io/falcon/
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
