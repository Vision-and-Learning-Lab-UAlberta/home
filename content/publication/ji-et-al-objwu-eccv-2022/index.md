---
title: "Object Wake-up: 3D Object Rigging from a Single Image."
authors:
- jiyang
- xinxinzuo
- senwang
- Zhenbo Yu
- Xingyu Li
- Bingbig Ni
- Minglun Gong
- licheng

date: "2022-07-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-07-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: European Conference on Computer Vision
publication_short: European Conference on Computer Vision (ECCV)

abstract: "Given a single image of a general object such as a chair, could we also restore its articulated 3D shape similar to human modeling, so as to animate its plausible articulations and diverse motions? This is an interesting new question that may have numerous downstream augmented reality and virtual reality applications. Comparing with previous efforts on object manipulation, our work goes beyond 2D manipulation and rigid deformation, and involves articulated manipulation. To achieve this goal, we propose an automated approach to build such 3D generic objects from single images and embed articulated skeletons in them. Specifically, our framework starts by reconstructing the 3D object from an input image. Afterwards, to extract skeletons for generic 3D objects, we develop a novel skeleton prediction method with a multi-head structure for skeleton probability field estimation by utilizing the deep implicit functions. A dataset of generic 3D objects with ground-truth annotated skeletons is collected. Empirically our approach is demonstrated with satisfactory performance on public datasets as well as our in-house dataset; our results surpass those of the state-of-the-arts by a noticeable margin on both 3D reconstruction and skeleton prediction."

# Summary. An optional shortened abstract.
# summary: "A hierarchical recurrent network structure is developed to simultaneously encodes local contexts of individual frames and global contexts of the sequence."

tags:
- object wake-up
- 3D reconstruction
featured: true

links:
# - name: Custom Link
# url: https://example.org
url_pdf: https://arxiv.org/abs/2108.02708
# url_code: https://github.com/BII-wushuang/Lie-Group-Motion-Prediction
# url_dataset: '#'
# url_poster: '#'
url_project: https://kulbear.github.io/object-wakeup/
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