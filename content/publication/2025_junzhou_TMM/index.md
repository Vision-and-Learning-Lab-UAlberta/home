---
title: "Hand Gesture Recognition from an Open-Set Perspective"

# if the author is from our lab, then you need to match it with the folder name you can find here
# https://github.com/Vision-and-Learning-Lab-UAlberta/home/tree/master/content/authors
# otherwise just write down their full name
authors:
  - junzhou # in our lab
  - Chi Xu
  - licheng # in our lab

date: "2025-01-27T00:00:00Z"
doi: "10.1109/TMM.2025.3535363"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# you can have this as multiple types, just use a list like ["1", "3"]
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Multimedia, 2025
publication_short: "*IEEE Transactions on Multimedia (TMM)*"

abstract: "Existing hand gesture recognition methods predominantly rely on a close-set assumption, which in essence limits the viewpoints, gesture categories, and hand shapes at test time to closely resemble those seen during training. This requirement is however rarely met in practice, as images are often captured from unconstrained viewpoints, with novel gestures and unseen hand shapes that can differ significantly from the training data. This motivates us to investigate an open-set hand gesture recognition problem, where hand gestures are still recognizable from unconstrained viewpoints, and novel gesture classes and hand shapes can be incrementally learned with just a few examples. To address this, we propose a viewpoint influence elimination network that extracts view-independent features, significantly improving performance in scenarios with unconstrained viewpoints. Moreover, a joint-weighted classification scheme is introduced to augment the cosine similarity metric for evaluating few-shot incremental learning of novel gestures and shapes. Finally, as existing hand gesture recognition datasets primarily adhere to the close-set assumption, a new hand gesture recognition dataset, OHG, is introduced in this paper, that includes a wide range of viewpoints, diverse gesture classes, and distinct hand shapes. Experimental hand gesture recognition results demonstrate the superior performance of our approach in both unconstrained viewpoint and few-shot incremental learning scenarios."

# Summary. An optional shortened abstract.
summary: 

tags:
  - TMM

featured: true

links:
# url_pdf: https://arxiv.org/abs/2207.01696
# url_code: https://github.com/EricGuo5513/action-to-motion
# url_dataset: https://ericguo5513.github.io/action-to-motion/#data
# url_poster:
# url_project: https://ericguo5513.github.io/TM2T/
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
