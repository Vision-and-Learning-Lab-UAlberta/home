---
title: "Detailed Human Shanpe and Pose Estimation from a Single Polarization image"
authors:
- shihaozou
- xinxinzuo
- Yiming Qian
- senwang
- Chi Xu
- Minglun Gong
- licheng

date: "2020-07-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-07-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the European Conference on Computer Vision"
publication_short: "ECCV"

abstract: This paper tackles a new problem of estimating detailed 3D human shape from a single polarized 2D image, i.e. a polarization image. Polarization images are known to be able to capture polarized reflected lights that preserve rich geometric cues of an object, which has motivated its recent applications in reconstructing detailed surface normal of the objects of interest. Meanwhile, inspired by the recent breakthroughs in human shape estimation from a single color image, in this paper, we investigate the new question of whether the geometric cues from polarization camera could be leveraged in estimating detailed human body shapes. This has led to the curation of Polarization Human Shape and Pose Dataset (PHSPD), our home-grown polarization image dataset of various human shapes and poses. A dedicated deep learning approach is also proposed, that is composed of two stages: stage 1 aims at inferring the surface normal that retains individuals' fine surface shapes including clothing details; stage 2 is responsible for reconstructing detailed 3D body shapes based on a rough shape model (SMPL). Empirical evaluations on a synthetic SURREAL dataset as well as real-life PHSPD dataset demonstrate the competitive performance of our approach in estimating human shapes and poses. It suggests that polarization camera could be a promising alternative to 2D color and 3D depth imaging for human shape and pose estimation. In particular, normal maps from polarization imaging help in accurately recovering human shapes with clothing details.

Test whether I can add other cotents here followed the abstract.

# Summary. An optional shortened abstract.
summary: "This paper tackles a new problem of estimating detailed 3D human shape from a single polarized 2D image, i.e. a polarization image."

tags:
- ECCV
featured: true

links:
# - name: Custom Link
# url: https://example.org
url_pdf: '#'
url_code: '#'
url_dataset: '#'
# url_poster: '#'
# url_project: 
# url_slides: ''
# url_source: '#'
url_video: '#'


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

<!-- {{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->

