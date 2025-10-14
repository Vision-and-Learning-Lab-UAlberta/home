---
title: "Act to See, See to Act: Diffusion-Driven Perception-Action Interplay for Adaptive Policies"

# if the author is from our lab, then you need to match it with the folder name you can find here
# https://github.com/Vision-and-Learning-Lab-UAlberta/home/tree/master/content/authors
# otherwise just write down their full name
authors:
  - jingwang # in our lab
  - Weiting Peng
  - Jing Tang
  - Zeyu Gong
  - Xihua Wang
  - Bo Tao
  - licheng # in our lab

date: "2025-10-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# you can have this as multiple types, just use a list like ["1", "3"]
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: 39th Conference on Neural Information Processing Systems (NeurIPS 2025)
publication_short: "*Neural Information Processing Systems (NeurIPS)*"

abstract: "Existing imitation learning methods decouple perception and action, which overlooks the causal reciprocity between sensory representations and action execution that humans naturally leverage for adaptive behaviors. To bridge this gap, we introduce Action-Guided Diffusion Policy (DP-AG), a unified representation learning that explicitly models a dynamic interplay between perception and action through probabilistic latent dynamics. DP-AG encodes latent observations into a Gaussian posterior via variational inference and evolves them using an action-guided SDE, where the Vector–Jacobian Product (VJP) of the diffusion policy's noise predictions serves as a structured stochastic force driving latent updates. To promote bidirectional learning between perception and action, we introduce a cycle-consistent contrastive loss that organizes the gradient flow of the noise predictor into a coherent perception–action loop, enforcing mutually consistent transitions in both latent updates and action refinements. Theoretically, we derive a variational lower bound for the action-guided SDE, and prove that the contrastive objective enhances continuity in both latent and action trajectories. Empirically, DP-AG significantly outperforms state-of-the-art methods across simulation benchmarks and real-world UR5 manipulation tasks. As a result, our DP-AG offers a promising step toward bridging biological adaptability and artificial policy learning. Code is available on our project website: https://jingwang18.github.io/dp-ag.github.io/."

# Summary. An optional shortened abstract.
summary: 

tags:
  - NeurIPS

featured: true

links:
# url_pdf: https://arxiv.org/pdf/2509.25822
url_code: https://github.com/JingWang18/DP-AG-Adaptive-Policy
# url_dataset: 
# url_poster:
url_project: https://jingwang18.github.io/dp-ag.github.io/
# url_slides:
# url_source:
# url_video: https://youtu.be/2Qa7ueFiDk0

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# If you have one, please zip together
image:
  caption: ""
  focal_point: ""
  preview_only: false
---
