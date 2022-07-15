---
title: "TM2T: Stochastic and Tokenized Modeling for the Reciprocal Generation of 3D Human Motions and Texts."

# if the author is from our lab, then you need to match it with the folder name you can find here
# https://github.com/Vision-and-Learning-Lab-UAlberta/home/tree/master/content/authors
# otherwise just write down their full name
authors:
  - chuanguo # in our lab
  - xinxinzuo
  - senwang
  - licheng # in our lab

date: "2022-07-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-07-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# you can have this as multiple types, just use a list like ["1", "3"]
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: European Conference on Computer Vision
publication_short: European Conference on Computer Vision (ECCV)

abstract: "Inspired by the strong ties between vision and language, the two intimate human sensing and communication modalities, our paper aims to explore the generation of 3D human full-body motions from texts, as well as its reciprocal task, shorthanded for text2motion and motion2text, respectively. To tackle the existing challenges, especially to enable the generation of multiple distinct motions from the same text, and to avoid the undesirable production of trivial motionless pose sequences, we propose the use of motion token, a discrete and compact motion representation. This provides one level playing ground when considering both motions and text signals, as the motion and text tokens, respectively. Moreover, our motion2text module is integrated into the inverse alignment process of our text2motion training pipeline, where a significant deviation of synthesized text from the input text would be penalized by a large training loss; empirically this is shown to effectively improve performance. Finally, the mappings in-between the two modalities of motions and texts are facilitated by adapting the neural model for machine translation (NMT) to our context. This autoregressive modeling of the distribution over discrete motion tokens further enables non-deterministic production of pose sequences, of variable lengths, from an input text. Our approach is flexible, could be used for both text2motion and motion2text tasks. Empirical evaluations on two benchmark datasets demonstrate the superior performance of our approach on both tasks over a variety of state-of-the-art methods."

# Summary. An optional shortened abstract.
summary: 

tags:
  - MM
  - Motion Generation

featured: true

links:
url_pdf: https://arxiv.org/abs/2207.01696
#url_code: https://github.com/EricGuo5513/action-to-motion
#url_dataset: https://ericguo5513.github.io/action-to-motion/#data
# url_poster:
url_project: https://ericguo5513.github.io/TM2T/
# url_slides:
# url_source:
#url_video: https://www.youtube.com/watch?v=eDzN3mhNdeo

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# If you have one, please zip together
image:
  caption: ""
  focal_point: ""
  preview_only: false
---
