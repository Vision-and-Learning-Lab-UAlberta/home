---
title: "Calibrated RGB-D Salient Object Detection"

# if the author is from our lab, then you need to match it with the folder name you can find here
# https://github.com/Vision-and-Learning-Lab-UAlberta/home/tree/master/content/authors
# otherwise just write down their full name
authors:
- weiji
- jingjingli
- Shuang Yu
- Miao Zhang
- Yongri Piao
- Shunyu Yao
- Qi Bi
- Kai Ma
- Yefeng Zheng
- Huchuan Lu
- licheng

date: "2021-03-01T00:00:00Z"
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# you can have this as multiple types, just use a list like ["1", "3"]
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of IEEE Conference on Computer Vision and Pattern Recognition
publication_short: CVPR

abstract: "Complex backgrounds and similar appearances between objects and their surroundings are generally recognized as challenging scenarios in Salient Object Detection (SOD). This naturally leads to the incorporation of depth information in addition to the conventional RGB image as input, known as RGB-D SOD or depth-aware SOD. Meanwhile, this emerging line of research has been considerably hindered by the noise and ambiguity that prevail in raw depth images. To address the aforementioned issues, we propose a Depth Calibration and Fusion (DCF) framework that contains two novel components: 1) a learning strategy to calibrate the latent bias in the original depth maps towards boosting the SOD performance; 2) a simple yet effective cross reference module to fuse features from both RGB and depth modalities. Extensive empirical experiments demonstrate that the proposed approach achieves superior performance against 27 state-of-the-art methods. Moreover, our depth calibration strategy alone can work as a preprocessing step; empirically it results in noticeable improvements when being applied to existing cutting-edge RGB-D SOD models."


# Summary. An optional shortened abstract.
summary: This paper systematically addresses the depth-related side effects via the designed calibration strategy towards boosting saliency detection accuracy.

tags:
- CVPR

featured: false

links:
# url_pdf: https://arxiv.org/pdf/2006.03630.pdf
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