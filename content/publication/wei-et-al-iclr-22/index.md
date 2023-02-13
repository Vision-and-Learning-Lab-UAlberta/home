---
title: "Promoting Saliency From Depth: Deep Unsupervised RGB-D Saliency Detection"

# if the author is from our lab, then you need to match it with the folder name you can find here
# https://github.com/Vision-and-Learning-Lab-UAlberta/home/tree/master/content/authors
# otherwise just write down their full name
authors:
- weiji
- jingjingli
- Qi Bi
- chuanguo
- Jie Liu
- licheng

date: "2022-03-01T00:00:00Z"
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# you can have this as multiple types, just use a list like ["1", "3"]
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: International Conference on Learning Representations
publication_short: International Conference on Learning Representations(ICLR)

abstract: Growing interests in RGB-D salient object detection (RGB-D SOD) have been witnessed in recent years, owing partly to the popularity of depth sensors and the rapid progress of deep learning techniques. Unfortunately, existing RGB-D SOD methods typically demand large quantity of training images being thoroughly annotated at pixel-level. The laborious and time-consuming manual annotation has become a real bottleneck in various practical scenarios. On the other hand, current unsupervised RGB-D SOD methods still heavily rely on handcrafted feature representations. This inspires us to propose in this paper a deep unsupervised RGB-D saliency detection approach, which requires no manual pixel-level annotation during training. It is realized by two key ingredients in our training pipeline. First, a depth-disentangled saliency update (DSU) framework is designed to automatically produce pseudo-labels with iterative follow-up refinements, which provides more trustworthy supervision signals for training the saliency network. Second, an attentive training strategy is introduced to tackle the issue of noisy pseudo-labels, by properly re-weighting to highlight the more reliable pseudo-labels. Extensive experiments demonstrate the superior efficiency and effectiveness of our approach in tackling the challenging unsupervised RGB-D SOD scenarios. Moreover, our approach can also be adapted to work in fully-supervised situation. Empirical studies show the incorporation of our approach gives rise to notably performance improvement in existing supervised RGB-D SOD models.


# Summary. An optional shortened abstract.
summary: 

tags:
- ICLR

featured: false

links:
url_pdf:  https://arxiv.org/abs/2205.07179
# url_code: https://github.com/BII-wushuang/Lie-Group-Motion-Prediction
# url_dataset:
# url_poster:
# url_project: https://coderstellaj.github.io/Hierarchical-Motion-Recurrent-Network-Website/
# url_slides:
# url_source:
# url_video: https://www.youtube.com/watch?v=6Yw6O_14xHQ&feature=youtu.be


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# If you have one, please zip together
image:
  caption: ''
  focal_point: ""
  preview_only: false

---