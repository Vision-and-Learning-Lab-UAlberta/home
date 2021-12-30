---
title: "Enhancing Human Motion Assessment by Self-supervised Representation Learning"
authors:
- mahdiarn
- licheng

date: "2021-09-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-09-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: The 32nd British Machine Vision Conference
publication_short: BMVC

abstract: "The space of human motions is vast, ranging from daily behaviors of healthy adults to the slow and stiff motions of Parkinson's patients, or to infant motions. This poses significant challenges when the task is focused on a relatively niche motion subspace such as physical rehabilitation: often the target datasets are limited and less-annotated; meanwhile, there exist large-scale, well-annotated benchmarks, typically consisting of daily activities from healthy adults. This observation inspires us to propose a two-stage pipeline that takes advantage of the best of both worlds: a non-expert network starts to learn the representation of normal motions from source datasets, by estimating the pace and a set of manually inpainted joints of the pose sequence; this is followed by an expert network that takes as input these representations as well as the appearance features of the dedicated motions from the target dataset, to assess the quality of the specific actions. Empirical experiments on two very different motion assessment applications (physical rehabilitation of Parkinson's & stroke patients, and neuromotor behaviors of infants) demonstrate the superior performance of our approach."

# Summary. An optional shortened abstract.
# summary: "A hierarchical recurrent network structure is developed to simultaneously encodes local contexts of individual frames and global contexts of the sequence."

tags:
- BMVC
featured: true

links:
# - name: Custom Link
# url: https://example.org
url_pdf: https://www.bmvc2021-virtualconference.com/assets/papers/1542.pdf
url_code: https://github.com/VisualTrackingVLL
# url_dataset: '#'
# url_poster: '#'
url_project: https://www.bmvc2021-virtualconference.com/conference/papers/paper_1542.html
# url_slides: ''
# url_source: '#'
url_video: https://www.bmvc2021-virtualconference.com/conference/papers/paper_1542.html


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