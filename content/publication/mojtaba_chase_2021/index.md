---
title: "CHASE: Robust Visual Tracking via Cell-Level Differentiable Neural Architecture Search"
authors:
- mojtabas
- javadk
- licheng
- Hossein Ghanei-Yakhdan
- Shohreh Kasaei

date: "2021-09-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-09-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: The 32nd British Machine Vision Conference
publication_short: The 32nd British Machine Vision Conference (BMVC)

abstract: "A strong visual object tracker nowadays relies on its well-crafted modules, which typically consist of manually-designed network architectures to deliver high-quality tracking results. Not surprisingly, the manual design process becomes a particularly challenging barrier, as it demands sufficient prior experience, enormous effort, intuition, and perhaps some good luck. Meanwhile, neural architecture search has gaining grounds in practical applications as a promising method in tackling the issue of automated search of feasible network structures. In this work, we propose a novel cell-level differentiable architecture search mechanism with early stopping to automate the network design of the tracking module, aiming to adapt backbone features to the objective of Siamese tracking networks during offline training. Besides, the proposed early stopping strategy avoids over-fitting and performance collapse problems leading to generalization improvement. The proposed approach is simple, efficient, and with no need to stack a series of modules to construct a network. Our approach is easy to be incorporated into existing trackers, which is empirically validated using different differentiable architecture search-based methods and tracking objectives. Extensive experimental evaluations demonstrate the superior performance of our approach over five commonly-used benchmarks."

# Summary. An optional shortened abstract.
# summary: "A hierarchical recurrent network structure is developed to simultaneously encodes local contexts of individual frames and global contexts of the sequence."

tags:
- BMVC
featured: true

links:
# - name: Custom Link
# url: https://example.org
url_pdf: https://arxiv.org/pdf/2107.03463.pdf
url_code: https://github.com/VisualTrackingVLL
# url_dataset: '#'
# url_poster: '#'
url_project: https://bmvc2021-virtualconference.com/conference/papers/paper_1571.html
# url_slides: ''
# url_source: '#'
url_video: https://bmvc2021-virtualconference.com/conference/papers/paper_1571.html


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