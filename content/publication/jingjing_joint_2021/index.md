---
title: "Joint Semantic Mining for Weakly Supervised RGB-D Salient Object Detection"
authors:
- jingjingli
- weiji
- Qi Bi
- Cheng Yan
- Miao Zhang
- Yongri Piao
- Huchuan Lu
- licheng

date: "2021-12-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: International Conference on Neural Information Processing Systems
publication_short: NeurIPS

abstract: "Training saliency detection models with weak supervisions, e.g., image-level tags or captions, is appealing as it removes the costly demand of per-pixel annotations. Despite the rapid progress of RGB-D saliency detection in fully-supervised setting, it however remains an unexplored territory when only weak supervision signals are available. This paper is set to tackle the problem of weakly-supervised RGB-D salient object detection. The key insight in this effort is the idea of maintaining per-pixel pseudo-labels with iterative refinements by reconciling the multimodal input signals in our joint semantic mining (JSM). Considering the large variations in the raw depth map and the lack of explicit pixel-level supervisions, we propose spatial semantic modeling (SSM) to capture saliency-specific depth cues from the raw depth and produce depth-refined pseudo-labels. Moreover, tags and captions are incorporated via a fill-in-the-blank training in our textual semantic modeling (TSM) to estimate the confidences of competing pseudo-labels. At test time, our model involves only a light-weight sub-network of the training pipeline, i.e., it requires only an RGB image as input, thus allowing efficient inference. Extensive evaluations demonstrate the effectiveness of our approach under the weakly-supervised setting. Importantly, our method could also be adapted to work in both fully-supervised and unsupervised paradigms. In each of these scenarios, superior performance has been attained by our approach with comparing to the state-of-the-art dedicated methods. As a by-product, a CapS dataset is constructed by augmenting existing benchmark training set with additional image tags and captions."

# Summary. An optional shortened abstract.
# summary: "A hierarchical recurrent network structure is developed to simultaneously encodes local contexts of individual frames and global contexts of the sequence."

tags:
- NeurIPS
featured: true

links:
# - name: Custom Link
# url: https://example.org
url_pdf: https://proceedings.neurips.cc/paper/2021/file/642e92efb79421734881b53e1e1b18b6-Paper.pdf
# url_code: https://github.com/VisualTrackingVLL
# url_dataset: '#'
# url_poster: '#'
url_project: https://proceedings.neurips.cc/paper/2021/hash/642e92efb79421734881b53e1e1b18b6-Abstract.html
# url_slides: ''
# url_source: '#'
# url_video: https://www.bmvc2021-virtualconference.com/conference/papers/paper_1542.html


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