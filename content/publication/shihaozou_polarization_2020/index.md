---
title: "3D Human Shape Reconstruction from a Polarization Image"
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

abstract: This paper tackles the problem of estimating 3D body shape of clothed humans from single polarized 2D images, i.e. polarization images. Polarization images are known to be able to capture polarized reflected lights that preserve rich geometric cues of an object, which has motivated its recent applications in reconstructing surface normal of the objects of interest. Inspired by the recent advances in human shape estimation from single color images, in this paper, we attempt at estimating human body shapes by leveraging the geometric cues from single polarization images. A dedicated two-stage deep learning approach, SfP, is proposed: given a polarization image, stage one aims at inferring the fined-detailed body surface normal; stage two gears to reconstruct the 3D body shape of clothing details. Empirical evaluations on a synthetic dataset (SURREAL) as well as a real-world dataset (PHSPD) demonstrate the qualitative and quantitative performance of our approach in estimating human poses and shapes. This indicates polarization camera is a promising alternative to the more conventional color or depth imaging for human shape estimation. Further, normal maps inferred from polarization imaging play a significant role in accurately recovering the body shapes of clothed people.
# Summary. An optional shortened abstract.
summary: "This paper tackles a new problem of estimating 3D body shape of clothed humans from single polarized 2D images, i.e. a polarization image."

tags:
- ECCV
featured: true

links:
# - name: Custom Link
# url: https://example.org
url_pdf: https://jimmyzou.github.io/files/eccv2020.pdf
url_code: '#'
url_dataset: https://jimmyzou.github.io/publication/2020-PHSPDataset
# url_poster: '#'
url_project: https://jimmyzou.github.io/publication/2020-polarization-clothed-human-shape
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

