---
title: "MoMask: Generative Masked Modeling of 3D Human Motions"

# if the author is from our lab, then you need to match it with the folder name you can find here
# https://github.com/Vision-and-Learning-Lab-UAlberta/home/tree/master/content/authors
# otherwise just write down their full name
authors:
  - chuanguo # in our lab
  - yuxuanmu
  - gohar
  - senwang
  - licheng # in our lab

date: "2024-02-27T00:00:00Z"
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
publication: Computer Vision and Pattern Recognition, 2024
publication_short: "*Computer Vision and Pattern Recognition (CVPR)*"

abstract: "We introduce MoMask, a novel masked modeling framework for text-driven 3D human motion generation. In MoMask, a hierarchical quantization scheme is employed to represent human motion as multi-layer discrete motion tokens with high-fidelity details. Starting at the base layer, with a sequence of motion tokens obtained by vector quantization, the residual tokens of increasing orders are derived and stored at the subsequent layers of the hierarchy. This is consequently followed by two distinct bidirectional transformers. For the base-layer motion tokens, a Masked Transformer is designated to predict randomly masked motion tokens conditioned on text input at training stage. During generation (i.e. inference) stage, starting from an empty sequence, our Masked Transformer iteratively fills up the missing tokens; Subsequently, a Residual Transformer learns to progressively predict the next-layer tokens based on the results from current layer. Extensive experiments demonstrate that MoMask outperforms the state-of-art methods on the text-to-motion generation task, with an FID of 0.045 (vs e.g. 0.141 of T2M-GPT) on the HumanML3D dataset, and 0.228 (vs 0.514) on KIT-ML, respectively. MoMask can also be seamlessly applied in related tasks without further model fine-tuning, such as text-guided temporal inpainting."

# Summary. An optional shortened abstract.
summary: 

tags:
  - CVPR

featured: true

links:
# url_pdf: https://arxiv.org/abs/2207.01696
url_code: https://github.com/EricGuo5513/momask-codes
# url_dataset: https://ericguo5513.github.io/action-to-motion/#data
# url_poster:
url_project: https://ericguo5513.github.io/momask/
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
