---
title: "Action2video: Generating Videos of Human 3D Actions"

# if the author is from our lab, then you need to match it with the folder name you can find here
# https://github.com/Vision-and-Learning-Lab-UAlberta/home/tree/master/content/authors
# otherwise just write down their full name
authors:
  - chuanguo # in our lab
  - xinxinzuo
  - senwang
  - Xinshuang Liu
  - shihaozou
  - Minglun Gong
  - licheng # in our lab

date: "2022-03-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# you can have this as multiple types, just use a list like ["1", "3"]
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: International Journal of Computer Vision
publication_short: "*International Journal of Computer Vision (IJCV)*"

abstract: "We aim to tackle the interesting yet challenging problem of generating videos of diverse and natural human motions from prescribed action categories. The key issue lies in the ability to synthesize multiple distinct motion sequences that are realistic in their visual appearances. It is achieved in this paper by a two-step process that maintains internal 3D pose and shape representations, action2motion and motion2video. Action2motion stochastically generates plausible 3D pose sequences of a prescribed action category, which are processed and rendered by motion2video to form 2D videos. Specifically, the Lie algebraic theory is engaged in representing natural human motions following the physical law of human kinematics; a temporal variational auto-encoder is developed that encourages diversity of output motions. Moreover, given an additional input image of a clothed human character, an entire pipeline is proposed to extract his/her 3D detailed shape, and to render in videos the plausible motions from different views. This is realized by improving existing methods to extract 3D human shapes and textures from single 2D images, rigging, animating, and rendering to form 2D videos of human motions. It also necessitates the curation and reannotation of 3D human motion datasets for training purpose. Thorough empirical experiments including ablation study, qualitative and quantitative evaluations manifest the applicability of our approach, and demonstrate its competitiveness in addressing related tasks, where components of our approach are compared favorably to the state-of-the-arts."

# Summary. An optional shortened abstract.
summary: A temporal VAE archtecture model equipped with Lie Algebra representation for action-conditioned 3D human motion generation.

tags:
  - MM
  - Motion Generation

featured: true

links:
url_pdf: https://link.springer.com/article/10.1007/s11263-021-01550-z
#url_code: https://github.com/EricGuo5513/action-to-motion
#url_dataset: https://ericguo5513.github.io/action-to-motion/#data
# url_poster:
#url_project: https://ericguo5513.github.io/action-to-motion/
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
