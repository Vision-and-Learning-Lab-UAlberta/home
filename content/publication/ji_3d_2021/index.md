---
title: "3D Pose Estimation and Future Motion Prediction from 2D Images"
authors:
- jiyang
- youdongma
- xinxinzuo
- senwang
- Minglun Gong
- licheng

date: "2021-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Pattern Recognition
publication_short: "*Pattern Recognition (PR)*"

abstract: "This paper considers to jointly tackle the highly correlated tasks of estimating 3D human body poses and predicting future 3D motions from RGB image sequences. Based on Lie algebra pose representation, a novel self-projection mechanism is proposed that naturally preserves human motion kinematics. This is further facilitated by a sequence-to-sequence multi-task architecture based on an encoder-decoder topology, which enables us to tap into the common ground shared by both tasks. Finally, a global refinement module is proposed to boost the performance of our framework. The effectiveness of our approach, called PoseMoNet, is demonstrated by ablation tests and empirical evaluations on Human3.6M and HumanEva-I benchmark, where competitive performance is obtained comparing to the state-of-the-arts."

# Summary. An optional shortened abstract.
# summary: "A hierarchical recurrent network structure is developed to simultaneously encodes local contexts of individual frames and global contexts of the sequence."

tags:
- PR
featured: true

links:
# - name: Custom Link
# url: https://example.org
url_pdf: https://arxiv.org/pdf/2111.13285.pdf
# url_code: https://github.com/BII-wushuang/Lie-Group-Motion-Prediction
# url_dataset: '#'
# url_poster: '#'
# url_project: https://coderstellaj.github.io/Hierarchical-Motion-Recurrent-Network-Website/
# url_slides: ''
# url_source: '#'
# url_video: 'https://www.youtube.com/watch?v=qi33KKUzrVA&feature=emb_title'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---