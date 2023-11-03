---
title: "Learning Calibrated Medical Image Segmentation via Multi-rater Agreement Modeling"

# if the author is from our lab, then you need to match it with the folder name you can find here
# https://github.com/Vision-and-Learning-Lab-UAlberta/home/tree/master/content/authors
# otherwise just write down their full name
authors:
- weiji
- Shuang Yu
- Junde Wu
- Kai Ma
- Cheng Bian
- Qi Bi
- jingjingli
- Hanruo Liu
- licheng
- Yefneg Zhang

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
publication_short: "*Proceedings of IEEE Conference on Computer Vision and Pattern Recognition(CVPR)*"

abstract: In medical image analysis, it is typical to collect multiple annotations, each from a different clinical expert or rater, in the expectation that possible diagnostic errors could be mitigated. Meanwhile, from the computer vision practitioner viewpoint, it has been a common practice to adopt the ground-truth obtained via either the majority-vote or simply one annotation from a preferred rater. This process, however, tends to overlook the rich information of agreement or disagreement ingrained in the raw multi-rater annotations. To address this issue, we propose to explicitly model the multi-rater (dis-)agreement, dubbed MRNet, which has two main contributions. First, an expertise-aware inferring module or EIM is devised to embed the expertise level of individual raters as prior knowledge, to form high-level semantic features. Second, our approach is capable of reconstructing multi-rater gradings from coarse predictions, with the multi-rater (dis-)agreement cues being further exploited to improve the segmentation performance. To our knowledge, our work is the first in producing calibrated predictions under different expertise levels for medical image segmentation. Extensive empirical experiments are conducted across five medical segmentation tasks of diverse imaging modalities. In these experiments, superior performance of our MRNet is observed comparing to the state-of-the-arts, indicating the effectiveness and applicability of our MRNet toward a wide range of medical segmentation tasks.


# Summary. An optional shortened abstract.
summary: This paper proposes a principled research investigation on exploiting the rich agreement information among multiple raters for improving the calibrated performance.

tags:
- CVPR

featured: false

links:
url_pdf: https://openaccess.thecvf.com/content/CVPR2021/papers/Ji_Learning_Calibrated_Medical_Image_Segmentation_via_Multi-Rater_Agreement_Modeling_CVPR_2021_paper.pdf
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