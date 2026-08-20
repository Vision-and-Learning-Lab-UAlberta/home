---
title: "Progressive Pose-Guided 4D Animal Reconstruction from Monocular Video"

authors:
  - siyuanli # in our lab
  - Weiying Chen 
  - yilinwang # in our lab
  - xinxinzuo 
  - Xingyu Li 
  - licheng # in our lab

date: "2026-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-07-01T00:00:00Z"

# Publication type.
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: European Conference on Computer Vision, 2026, *Oral Presentation*
publication_short: "*European Conference on Computer Vision (ECCV)*"

abstract: "Reconstructing 4D animals from monocular videos is challenging due to large inter-species variation, complex articulations, and the lack of reliable templates. Existing approaches typically rely on either strict category-specific priors that restrict generalization, or unconstrained generative models that sacrifice input fidelity. To bridge this gap, we present a progressive test-time optimization framework built on 3D Gaussian Splatting for high-fidelity 4D animal reconstruction from a single video. Our key insight is that a coarse shape prior suffices when coupled with a progressive strategy that disentangles articulated pose from non-rigid deformation. Specifically, we employ a symmetry-aware temporal encoding that exploits bilateral cues while absorbing camera estimation drift and a part-conditioned deformation mechanism guided by learnable part anchors and a learnable skinning field. Extensive experiments demonstrate that our approach generalizes robustly across diverse species, achieving superior geometric accuracy, temporal consistency, and visual fidelity compared to existing baselines, even under severe prior mismatch."

# Summary. An optional shortened abstract.
summary: A Monocular Video 4D Animal Reconstruction Method Based on a Progressive Pose-Guided Framework and 3D Gaussian Splatting.

tags:
  - ECCV

featured: true

links:
url_pdf: https://arxiv.org/abs/2607.00157
url_code: https://github.com/SYL-322/ReWild4D
# url_dataset: https://ericguo5513.github.io/action-to-motion/#data
# url_poster:
url_project: https://syl-322.github.io/ReWild4D/
# url_slides:
# url_source:
url_video: https://syl-322.github.io/ReWild4D/

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# If you have one, please zip together
image:
  caption: "Overview"
  focal_point: "Center"
  preview_only: false
---
