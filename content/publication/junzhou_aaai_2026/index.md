---
title: "VPHO: Joint Visual-Physical Cue Learning and Aggregation for Hand-Object Pose Estimation"

# if the author is from our lab, then you need to match it with the folder name you can find here
# https://github.com/Vision-and-Learning-Lab-UAlberta/home/tree/master/content/authors
# otherwise just write down their full name
authors:
  - junzhou # in our lab
  - Chi Xu
  - Kaifeng Tang
  - Yuting Ge
  - Tingrui Guo
  - licheng # in our lab

date: "2025-11-22T00:00:00Z"
doi: "10.48550/arXiv.2511.12030"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-11-22T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# you can have this as multiple types, just use a list like ["1", "3"]
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: The 40th Annual AAAI Conference on Artificial Intelligence
publication_short: "*AAAI 2026*"

abstract: "Estimating the 3D poses of hands and objects from a single RGB image is a fundamental yet challenging problem, with broad applications in augmented reality and human-computer interaction. Existing methods largely rely on visual cues alone, often producing results that violate physical constraints such as interpenetration or non-contact. Recent efforts to incorporate physics reasoning typically depend on post-optimization or non-differentiable physics engines, which compromise visual consistency and end-to-end trainability. To overcome these limitations, we propose a novel framework that jointly integrates visual and physical cues for hand-object pose estimation. This integration is achieved through two key ideas: 1) joint visual-physical cue learning: The model is trained to extract 2D visual cues and 3D physical cues, thereby enabling more comprehensive representation learning for hand-object interactions; 2) candidate pose aggregation: A novel refinement process that aggregates multiple diffusion-generated candidate poses by leveraging both visual and physical predictions, yielding a final estimate that is visually consistent and physically plausible. Extensive experiments demonstrate that our method significantly outperforms existing state-of-the-art approaches in both pose accuracy and physical plausibility."

# Summary. An optional shortened abstract.
summary: 

tags:
  - AAAI

featured: true

links:
url_pdf: https://arxiv.org/abs/2511.12030
url_code: https://github.com/zhoujun-7/VPHO
# url_dataset: https://ericguo5513.github.io/action-to-motion/#data
# url_poster:
# url_project: https://ericguo5513.github.io/TM2T/
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
