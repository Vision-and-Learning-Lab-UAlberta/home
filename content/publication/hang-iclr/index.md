---
title: "PICS: Pairwise Image Compositing with Spatial Interactions"

authors:
  - hangzhou # in our lab
  - xinxinzuo # in our lab
  - senwang # in our lab
  - licheng # in our lab

date: "2026-01-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-01-26T00:00:00Z"

# Publication type.
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: International Conference on Learning Representations, 2026
publication_short: "*International Conference on Learning Representations (ICLR)*"

abstract: "Despite strong single-turn performance, diffusion-based image compositing often struggles to preserve coherent spatial relations in pairwise or sequential edits, where subsequent insertions may overwrite previously generated content and disrupt physical consistency. We introduce PICS, a self-supervised composition-by-decomposition paradigm that composes objects in parallel while explicitly modeling the compositional interactions among (fully-/partially-)visible objects and background. At its core, an Interaction Transformer employs mask-guided Mixture-of-Experts to route background, exclusive, and overlap regions to dedicated experts, with an adaptive $\alpha$-blending strategy that infers a compatibility-aware fusion of overlapping objects while preserving boundary fidelity. To further enhance robustness to geometric variations, we incorporate geometry-aware augmentations covering both out-of-plane and in-plane pose changes of objects. Our method delivers superior pairwise compositing quality and substantially improved stability, with extensive evaluations across virtual try-on, indoor, and street scene settings showing consistent gains over state-of-the-art baselines. "

# Summary. An optional shortened abstract.
summary: A self-supervised paradigm for pairwise image compositing that models object interactions via Mixture-of-Experts and adaptive alpha-blending.

tags:
  - ICLR

featured: true

links:
url_pdf: https://arxiv.org/abs/2603.06873
url_code: https://github.com/RyanHangZhou/PICS
# url_dataset: https://ericguo5513.github.io/action-to-motion/#data
# url_poster:
url_project: https://ryanhangzhou.github.io/pics/
# url_slides:
# url_source:
url_video: https://recorder-v3.slideslive.com/#/share?share=108699&s=b9ecf964-9729-4a83-b826-513f340c5cf8

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# If you have one, please zip together
image:
  caption: "PICS Overview"
  focal_point: "Center"
  preview_only: false
---
