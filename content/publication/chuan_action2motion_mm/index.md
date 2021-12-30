---
title: "Action2Motion: Conditioned Generation of 3D Human Motions"

# if the author is from our lab, then you need to match it with the folder name you can find here
# https://github.com/Vision-and-Learning-Lab-UAlberta/home/tree/master/content/authors
# otherwise just write down their full name
authors:
  - chuanguo # in our lab
  - xinxinzuo
  - senwang
  - shihaozou
  - Qingyao Sun
  - Annan Deng
  - Minglun Gong
  - licheng # in our lab

date: "2020-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# you can have this as multiple types, just use a list like ["1", "3"]
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 28th ACM International Conference on Multimedia
publication_short: ACM Multimedia

abstract: "Action recognition is a relatively established task, where given an input sequence of human motion, the goal is to predict its action category. This paper, on the other hand, considers a relatively new problem, which could be thought of as an inverse of action recognition: given a prescribed action type, we aim to generate plausible human motion sequences in 3D. Importantly, the set of generated motions are expected to maintain its diversity to be able to explore the entire action-conditioned motion space; meanwhile, each sampled sequence faithfully resembles a natural human body articulation dynamics. Motivated by these objectives, we follow the physics law of human kinematics by adopting the Lie Algebra theory to represent the natural human motions; we also propose a temporal Variational Auto-Encoder (VAE) that encourages a diverse sampling of the motion space. A new 3D human motion dataset, HumanAct12, is also constructed. Empirical experiments over three distinct human motion datasets (including ours) demonstrate the effectiveness of our approach."

# Summary. An optional shortened abstract.
summary: A temporal VAE archtecture model equipped with Lie Algebra representation for action-conditioned 3D human motion generation.

tags:
  - MM
  - Motion Generation

featured: true

links:
url_pdf: https://arxiv.org/pdf/2007.15240.pdf
url_code: https://github.com/EricGuo5513/action-to-motion
url_dataset: https://ericguo5513.github.io/action-to-motion/#data
# url_poster:
url_project: https://ericguo5513.github.io/action-to-motion/
# url_slides:
# url_source:
url_video: https://www.youtube.com/watch?v=eDzN3mhNdeo

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# If you have one, please zip together
image:
  caption: ""
  focal_point: ""
  preview_only: false
---
