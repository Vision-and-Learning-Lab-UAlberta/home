---
title: "InterMask: 3D Human Interaction Generation via Collaborative Masked Modelling"

# if the author is from our lab, then you need to match it with the folder name you can find here
# https://github.com/Vision-and-Learning-Lab-UAlberta/home/tree/master/content/authors
# otherwise just write down their full name
authors:
  - gohar
  - chuanguo # in our lab
  - licheng # in our lab
  - Xingyu Li

date: "2025-01-22T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-04-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# you can have this as multiple types, just use a list like ["1", "3"]
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: International Conference on Learning Representations, 2025
publication_short: "*International Conference on Learning Representations (ICLR)*"

abstract: "Generating realistic 3D human-human interactions from textual descriptions remains a challenging task. Existing approaches, typically based on diffusion models, often generate unnatural and unrealistic results. In this work, we introduce InterMask, a novel framework for generating human interactions using collaborative masked modeling in discrete space. InterMask first employs a VQ-VAE to transform each motion sequence into a 2D discrete motion token map. Unlike traditional 1D VQ token maps, it better preserves fine-grained spatio-temporal details and promotes spatial awareness within each token. Building on this representation, InterMask utilizes a generative masked modeling framework to collaboratively model the tokens of two interacting individuals. This is achieved by employing a transformer architecture specifically designed to capture complex spatio-temporal interdependencies. During training, it randomly masks the motion tokens of both individuals and learns to predict them. In inference, starting from fully masked sequences, it progressively fills in the tokens for both individuals. With its enhanced motion representation, dedicated architecture, and effective learning strategy, InterMask achieves state-of-the-art results, producing high-fidelity and diverse human interactions. It outperforms previous methods, achieving an FID of 5.154 (vs 5.535 for in2IN) on the InterHuman dataset and 0.399 (vs 5.207 for InterGen) on the InterX dataset. Additionally, InterMask seamlessly supports reaction generation without the need for model redesign or fine-tuning."

# Summary. An optional shortened abstract.
summary: "A novel framework for human interaction generation using collaborative masked modeling in the discrete space, which explicitly models spatio-temporal dependencies within and between the interacting individuals."

tags:
  - ICLR

featured: true

links:
url_pdf: https://openreview.net/forum?id=ZAyuwJYN8N&referrer=%5BTasks%5D(%2Ftasks)
url_code: https://github.com/gohar-malik/intermask
# url_dataset: https://ericguo5513.github.io/action-to-motion/#data
# url_poster:
url_project: https://gohar-malik.github.io/intermask/
# url_slides:
# url_source:
# url_video: https://www.youtube.com/watch?v=eDzN3mhNdeo

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# If you have one, please zip together
image:
  caption: ""
  focal_point: ""
  preview_only: false
---
