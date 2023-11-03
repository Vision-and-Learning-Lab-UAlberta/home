---
title: "Investigating Pose Representations and Motion Contexts Modeling for 3D Motion Prediction"
authors:
- Zhenguang Liu
- shuangwu
- Shuyuan Jin
- Qi Liu
- Shouling Ji
- Shijian Lu
- licheng

date: "2022-01-04T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication:  IEEE Transactions on Pattern Analysis and Machine Intelligence
publication_short: "*IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)*"

abstract: "Predicting human motion from historical pose sequence is crucial for a machine to succeed in intelligent interactions with humans. One aspect that has been obviated so far, is the fact that how we represent the skeletal pose has a critical impact on the prediction results. Yet there is no effort that investigates across different pose representation schemes. We conduct an indepth study on various pose representations with a focus on their effects on the motion prediction task. Moreover, recent approaches build upon off-the-shelf RNN units for motion prediction. These approaches process input pose sequence sequentially and inherently have difficulties in capturing long-term dependencies. In this paper, we propose a novel RNN architecture termed AHMR for motion prediction which simultaneously models local motion contexts and a global context. We further explore a geodesic loss and a forward kinematics loss, which have more geometric significance than the widely employed L2 loss. Interestingly, we applied our method to a range of articulate objects including human, fish, and mouse. Empirical results show that our approach outperforms the state-of-the-art methods in short-term prediction and achieves much enhanced long-term prediction proficiency, such as retaining natural human-like motions over 50 seconds predictions. Our codes are released."

# Summary. An optional shortened abstract.
# summary: "A hierarchical recurrent network structure is developed to simultaneously encodes local contexts of individual frames and global contexts of the sequence."

tags:
- TPAMI
featured: true

links:
# - name: Custom Link
# url: https://example.org
url_pdf: https://arxiv.org/pdf/2112.15012
# url_code: https://github.com/VisualTrackingVLL
# url_dataset: '#'
# url_poster: '#'
url_project: https://ieeexplore.ieee.org/document/9669004/
# url_slides: ''
# url_source: '#'
# url_video: https://www.bmvc2021-virtualconference.com/conference/papers/paper_1542.html


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