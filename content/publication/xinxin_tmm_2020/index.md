---
title: "SparseFusion: Dynamic Human Avatar Modeling from Sparse RGBD Images"

# if the author is from our lab, then you need to match it with the folder name you can find here
# https://github.com/Vision-and-Learning-Lab-UAlberta/home/tree/master/content/authors
# otherwise just write down their full name
authors:
- xinxinzuo # in our lab
- senwang # in our lab 
- Jiangbin Zheng
- Weiwei Yu
- Minglun Gong
- Ruigang Yang
- licheng # in our lab

date: "2020-06-10T00:00:00Z"
doi: "10.1109/TMM.2020.3001506"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# you can have this as multiple types, just use a list like ["1", "3"]
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Multimedia
publication_short: TMM

abstract: In this paper, we propose a novel approach to reconstruct 3D human body shapes based on a sparse set of RGBD frames using a single RGBD camera. We specifically focus on the realistic settings where human subjects move freely during the capture. The main challenge is how to robustly fuse these sparse frames into a canonical 3D model, under pose changes and surface occlusions. This is addressed by our new framework consisting of the following steps. First, based on a generative human template, for every two frames having sufficient overlap, an initial pairwise alignment is performed; It is followed by a global non-rigid registration procedure, in which partial results from RGBD frames are collected into a unified 3D shape, under the guidance of correspondences from the pairwise alignment; Finally, the texture map of the reconstructed human model is optimized to deliver a clear and spatially consistent texture. Empirical evaluations on synthetic and real datasets demonstrate both quantitatively and qualitatively the superior performance of our framework in reconstructing complete 3D human models with high fidelity. It is worth noting that our framework is flexible, with potential applications going beyond shape reconstruction. As an example, we showcase its use in reshaping and reposing to a new avatar.

# Summary. An optional shortened abstract.
summary: A novel approach to reconstruct 3D human body shapes based on a sparse set of RGBD frames using a single RGBD camera

tags:
- TMM

featured: false

links:
url_pdf: https://arxiv.org/pdf/2006.03630.pdf
# url_code: https://github.com/BII-wushuang/Lie-Group-Motion-Prediction
# url_dataset:
# url_poster:
# url_project: https://coderstellaj.github.io/Hierarchical-Motion-Recurrent-Network-Website/
# url_slides:
# url_source:
url_video: https://www.youtube.com/watch?v=6Yw6O_14xHQ&feature=youtu.be


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# If you have one, please zip together
image:
  caption: ''
  focal_point: ""
  preview_only: false

---