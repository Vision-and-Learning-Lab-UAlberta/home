---
title: "RegionGrasp: A Novel Task for Contact Region Controllable Hand Grasp Generation"

# if the author is from our lab, then you need to match it with the folder name you can find here
# https://github.com/Vision-and-Learning-Lab-UAlberta/home/tree/master/content/authors
# otherwise just write down their full name
authors:
- yilinwang
- chuanguo
- licheng
- Hai Jiang

date: "2024-08-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# you can have this as multiple types, just use a list like ["1", "3"]
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: European Conference on Computer Vision Workshops, 2024
publication_short: "*European Conference on Computer Vision (ECCV) Workshops*"

abstract: "Can machine automatically generate multiple distinct and natural hand grasps, given specific contact region of an object in 3D? This motivates us to consider a novel task of Region Controllable Hand Grasp Generation (RegionGrasp), as follows: given as input a 3D object, together with its specific surface area selected as the intended contact region, to generate a diverse set of plausible hand grasps of the object, where the thumb finger tip touches the object surface on the contact region. To address this task, RegionGrasp-CVAE is proposed, which consists of two main parts. First, to enable contact region-awareness, we propose ConditionNet as the condition encoder that includes in it a transformer-backboned object encoder, O-Enc; a pretraining strategy is adopted by O-Enc, where the point patches of object surface are ran- domly masked off and subsequently restored, to further capture surface geometric information of the object. Second, to realize interaction aware- ness, HOINet is introduced to encode hand-object interaction features by entangling high-level hand features with embedded object features through geometric-aware multi-head cross attention. Empirical evalua- tions demonstrate the effectiveness of our approach qualitatively and quantitatively where it is shown to compare favorably with respect to the state of the art methods."

# Summary. An optional shortened abstract.
summary: 

tags:
  - ECCV

featured: true

links:
url_pdf: https://hands-workshop.org/files/2024/regiongrasp.pdf
# url_code: https://github.com/EricGuo5513/action-to-motion
# url_dataset: https://ericguo5513.github.io/action-to-motion/#data
# url_poster:
# url_project: https://yxmu.foo/GSD/
# url_slides:
# url_source:
# url_video: https://www.youtube.com/watch?v=eDzN3mhNdeo

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# If you have one, please zip together
image:
  caption: ""
  focal_point: ""
  preview_only: false
---
