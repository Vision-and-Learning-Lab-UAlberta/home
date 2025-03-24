---
title: "BootPlace: Bootstrapped Object Placement with Detection Transformers"

# if the author is from our lab, then you need to match it with the folder name you can find here
# https://github.com/Vision-and-Learning-Lab-UAlberta/home/tree/master/content/authors
# otherwise just write down their full name
authors:
  - hangzhou # in our lab
  - xinxinzuo
  - Rui Ma
  - licheng # in our lab

date: "2025-02-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-02-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# you can have this as multiple types, just use a list like ["1", "3"]
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Computer Vision and Pattern Recognition, 2025
publication_short: "*Computer Vision and Pattern Recognition (CVPR)*"

abstract: "In this paper, we tackle the copy-paste image-to-image composition problem with a focus on object placement learning. Prior methods have leveraged generative models to minimize the need for dense supervision, which unfortunately may limit their ability to model complex data distributions. Alternatively, transformer networks with a sparse contrastive loss have been employed; yet their over-relaxed regularization often leads to imprecise placement. We propose BootPlace, a novel paradigm that formulates object placement as a placement-by-detection problem. Our method first identifies regions of interest suitable for object placement by training a dedicated detection transformer on object-subtracted backgrounds with multi-object supervisions. It then associates each target compositing object with detected regions based on semantic complementary. Using a boostrapped training approach on randomly object-subtracted images, our model regularizes meaningful placements through richly paired data augmentation. Experimental results on standard benchmarks demonstrate BootPlace's superior performance in object reposition, significantly outperforming state-fo-the-art baselines on Cityscapes and OPA datasets with notable improvements in IOU scores. Additional ablation studies further showcase the compositionality and generalizability of our approach, supported by user study evaluations."

# Summary. An optional shortened abstract.
summary: 

tags:
  - CVPR

featured: true

links:
# url_pdf: https://arxiv.org/abs/2207.01696
# url_code: https://github.com/EricGuo5513/action-to-motion
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
