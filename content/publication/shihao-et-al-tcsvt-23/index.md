---
title: "Snipper: A Spatiotemporal Transformer for Simultaneous Multi-Person 3D Pose Estimation Tracking and Forecasting on a Video Snippet"
authors:
- shihaozou
- Yuanlu Xu
- Chao Li
- Lingni Ma
- licheng
- Minh Vo

date: "2023-02-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-02-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Circuits and Systems for Video Technology"
publication_short: "*IEEE Transactions on Circuits and Systems for Video Technology(TCSVT)*"

abstract: "Multi-person pose understanding from RGB videos involves three complex tasks: pose estimation, tracking and motion forecasting. Intuitively, accurate multi-person pose estimation facilitates robust tracking, and robust tracking builds crucial history for correct motion forecasting. Most existing works either focus on a single task or employ multi-stage approaches to solving multiple tasks separately, which tends to make sub-optimal decision at each stage and also fail to exploit correlations among the three tasks. In this paper, we propose Snipper, a unified framework to perform multi-person 3D pose estimation, tracking, and motion forecasting simultaneously in a single stage. We propose an efficient yet powerful deformable attention mechanism to aggregate spatiotemporal information from the video snippet. Building upon this deformable attention, a video transformer is learned to encode the spatiotemporal features from the multi-frame snippet and to decode informative pose features for multi-person pose queries. Finally, these pose queries are regressed to predict multi-person pose trajectories and future motions in a single shot. In the experiments, we show the effectiveness of Snipper on three challenging public datasets where our generic model rivals specialized state-of-art baselines for pose estimation, tracking, and forecasting."
# Summary. An optional shortened abstract.
summary: ""

tags:
- 
featured: true

links:
# - name: Custom Link
# url: https://example.org
url_pdf: https://arxiv.org/abs/2207.04320
# url_code: '#'
# url_dataset: https://jimmyzou.github.io/publication/2020-PHSPDataset
# url_poster: '#'
# url_project: https://jimmyzou.github.io/publication/2020-polarization-clothed-human-shape
# url_slides: ''
# url_source: '#'
# url_video: '#'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->

