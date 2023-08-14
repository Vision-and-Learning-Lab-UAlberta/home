---
title: "Multispectral Video Semantic Segmentation: A Benchmark Dataset and Baseline"

# if the author is from our lab, then you need to match it with the folder name you can find here
# https://github.com/Vision-and-Learning-Lab-UAlberta/home/tree/master/content/authors
# otherwise just write down their full name
authors:
- weiji
- jingjingli
- Cheng Bian
- Zongwei Zhou
- Jiaying Zhao
- Alan Yuille
- licheng

date: "2023-03-01T00:00:00Z"
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# you can have this as multiple types, just use a list like ["1", "3"]
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of IEEE Conference on Computer Vision and Pattern Recognition
publication_short: CVPR

abstract: "Robust and reliable semantic segmentation in complex scenes is crucial for many real-life applications such as autonomous safe driving and nighttime rescue. In most approaches, it is typical to make use of RGB images as input. They however work well only in preferred weather conditions; when facing adverse conditions such as rainy, overexposure, or low-light, they often fail to deliver satisfactory results. This has led to the recent investigation into multispectral semantic segmentation, where RGB and thermal infrared (RGBT) images are both utilized as input. This gives rise to significantly more robust segmentation of image objects in complex scenes and under adverse conditions. Nevertheless, the present focus in single RGBT image input restricts existing methods from well addressing dynamic real-world scenes. Motivated by the above observations, in this paper, we set out to address a relatively new task of semantic segmentation of multispectral video input, which we refer to as Multispectral Video Semantic Segmentation, or MVSS in short. An in-house MVSeg dataset is thus curated, consisting of 738 calibrated RGB and thermal videos, accompanied by 3,545 fine-grained pixel-level semantic annotations of 26 categories. Our dataset contains a wide range of challenging urban scenes in both daytime and nighttime. Moreover, we propose an effective MVSS baseline, dubbed MVNet, which is to our knowledge the first model to jointly learn semantic representations from multispectral and temporal contexts. Comprehensive experiments are conducted using various semantic segmentation models on the MVSeg dataset. Empirically, the engagement of multispectral video input is shown to lead to significant improvement in semantic segmentation; the effectiveness of our MVNet baseline has also been verified."


# Summary. An optional shortened abstract.
summary: 

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