---
title: Automated Generation of Accurate and Fluent Medical X-ray Reports

# if the author is from our lab, then you need to match it with the folder name you can find here
# https://github.com/Vision-and-Learning-Lab-UAlberta/home/tree/master/content/authors
# otherwise just write down their full name
authors:
  - hoangn # in our lab
  - Dong Nie
  - tk
  - Yujie Liu
  - Jason Truong
  - licheng

date: "2021-08-27T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# you can have this as multiple types, just use a list like ["1", "3"]
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing
publication_short: EMNLP

abstract: "Our paper focuses on automating the generation of medical reports from chest X-ray image inputs, a critical yet time-consuming task for radiologists. Unlike existing medical re-port generation efforts that tend to produce human-readable reports, we aim to generate medical reports that are both fluent and clinically accurate. This is achieved by our fully differentiable and end-to-end paradigm containing three complementary modules: taking the chest X-ray images and clinical his-tory document of patients as inputs, our classification module produces an internal check-list of disease-related topics, referred to as enriched disease embedding; the embedding representation is then passed to our transformer-based generator, giving rise to the medical reports; meanwhile, our generator also pro-duces the weighted embedding representation, which is fed to our interpreter to ensure consistency with respect to disease-related topics.Our approach achieved promising results on commonly-used metrics concerning language fluency and clinical accuracy. Moreover, noticeable performance gains are consistently ob-served when additional input information is available, such as the clinical document and extra scans of different views."

# # Summary. An optional shortened abstract.
# summary: A temporal VAE archtecture model equipped with Lie Algebra representation for action-conditioned 3D human motion generation.

tags:
  - EMNLP
  - Text Generation

featured: true

links:
url_pdf: https://arxiv.org/pdf/2108.12126.pdf
# url_code: https://github.com/EricGuo5513/action-to-motion
# url_dataset: https://ericguo5513.github.io/action-to-motion/#data
# url_poster:
# url_project: https://ericguo5513.github.io/action-to-motion/
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
