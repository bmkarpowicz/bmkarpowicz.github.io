---
title: "Few-shot Algorithms for Consistent Neural Decoding (FALCON) Benchmark"
authors:
- admin
- Joel Ye
- Chaofei Fan
- Pablo Tostado-Marcos
- Fabio Rizzoglio
- Clay Washington
- Thiago Scodeler
- Diogo de Lucena
- Samuel R. Nason-Tomaszewski
- Matthew J. Mender
- Xuan Ma
- Ezequiel Matias Arneodo
- Leigh R. Hochberg
- Cynthia A. Chestek
- Jaimie M. Henderson
- Timothy Q. Gentner
- Vikash Gilja
- Lee E. Miller
- Adam G. Rouse
- Robert A. Gaunt
- Jennifer L. Collinger
- Chethan Pandarinath
author_notes:
- Equal Contribution to Joel Ye
- Equal Contribution to Brianna M. Karpowicz
date: "2024-09-15T00:00:00Z"
doi: "https://doi.org/10.1101/2024.09.15.613126"

# Brianna M. Karpowicz1,2∗ Joel Ye3∗ Chaofei Fan4 Pablo Tostado-Marcos5 Fabio Rizzoglio6 Clay Washington1,2 Thiago Scodeler7 Diogo de Lucena7 Samuel R. Nason-Tomaszewski1,2 Matthew J. Mender8 Xuan Ma6 Ezequiel Matias Arneodo5,9 Leigh R. Hochberg10−12 Cynthia A. Chestek8 Jaimie M. Henderson4 Timothy Q. Gentner5 Vikash Gilja5 Lee E. Miller6 AdamG.Rouse13 Robert A. Gaunt14 Jennifer L. Collinger3,14 Chethan Pandarinath1,2†

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Intracortical brain-computer interfaces (iBCIs) can restore movement and communication abilities to individuals with paralysis by decoding their intended behavior from neural activity recorded with an implanted device. While this activity yields high-performance decoding over short timescales, neural data are often nonstationary, which can lead to decoder failure if not accounted for. To maintain performance, users must frequently recalibrate decoders, which requires the arduous collection of new neural and behavioral data. Aiming to reduce this burden, several approaches have been developed that either limit recalibration data requirements (few-shot approaches) or eliminate explicit recalibration entirely (zero-shot approaches). However, progress is limited by a lack of standardized datasets and comparison metrics, causing methods to be compared in an ad hoc manner. Here we introduce the FALCON benchmark suite (Few-shot Algorithms for COnsistent Neural decoding) to standardize evaluation of iBCI robustness. FALCON curates five datasets of neural and behavioral data that span movement and communication tasks to focus on behaviors of interest to modern-day iBCIs. Each dataset includes calibration data, optional few-shot recalibration data, and private evaluation data. We implement a flexible evaluation platform which only requires user-submitted code to return behavioral predictions on unseen data. We also seed the benchmark by applying baseline methods spanning several classes of possible approaches. FALCON aims to provide rigorous selection criteria for robust iBCI decoders, easing their translation to real-world devices.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
- name: bioRxiv
  url: https://www.biorxiv.org/content/10.1101/2024.09.15.613126v1
url_pdf: https://www.biorxiv.org/content/10.1101/2024.09.15.613126v1.full.pdf
url_code: https://github.com/snel-repo/falcon-challenge
url_dataset: https://snel-repo.github.io/falcon/datasets
# url_poster: '#'
url_project: https://snel-repo.github.io/falcon/
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
