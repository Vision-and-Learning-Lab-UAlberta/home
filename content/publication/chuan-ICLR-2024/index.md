---
title: "Generative Human Motion Stylization in Latent Space"

# if the author is from our lab, then you need to match it with the folder name you can find here
# https://github.com/Vision-and-Learning-Lab-UAlberta/home/tree/master/content/authors
# otherwise just write down their full name
authors:
  - chuanguo # in our lab
  - yuxuanmu
  - xinxinzuo
  - Peng Dai
  - Youliang Yan
  - Juwei Lu
  - licheng # in our lab

date: "2024-01-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# you can have this as multiple types, just use a list like ["1", "3"]
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: International Conference on Learning Representations, 2024
publication_short: "*International Conference on Learning Representations (ICLR)*"

abstract: "Human motion stylization aims to revise the style of an input motion while keeping its content unaltered. Unlike existing works that operate directly in pose space, we leverage the \textit{latent space} of pretrained autoencoders as a more expressive and robust representation for motion extraction and infusion. Building upon this, we present a novel \textit{generative} model that produces diverse stylization results of a single motion (latent) code. During training, a motion code is decomposed into two coding components: a deterministic content code, and a probabilistic style code adhering to a prior distribution; then a generator massages the random combination of content and style codes to reconstruct the corresponding motion codes. Our approach is versatile, allowing the learning of probabilistic style space from either style labeled or unlabeled motions, providing notable flexibility in stylization as well. In inference, users can opt to stylize a motion using style cues from a reference motion or a label. Even in the absence of explicit style input, our model facilitates novel re-stylization by sampling from the unconditional style prior distribution. Experimental results show that our proposed stylization models, despite their lightweight design, outperform the state-of-the-arts in style reeanactment, content preservation, and generalization across various applications and settings."

# Summary. An optional shortened abstract.
summary: 

tags:
  - ICLR

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
