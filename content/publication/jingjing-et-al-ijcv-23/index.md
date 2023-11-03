---
title: "Delving into Calibrated Depth for Accurate RGB-D Salient Object Detection"
authors:
- jingjingli
- weiji
- Miao Zhang
- Yongri Piao
- Huchuan Lu
- licheng

date: "2023-02-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-02-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Interactional Journal of Computer Vision
publication_short: "*Interactional Journal of Computer Vision (IJCV)*"

abstract: "Recent years have witnessed growing interests in RGB-D Salient Object Detection (SOD), benefiting from the ample spatial layout cues embedded in depth maps to help SOD models distinguish salient objects from complex backgrounds or similar surroundings. Despite these progresses, this emerging line of research has been considerably hindered by the noise and ambiguity that prevail in raw depth images, as well as the coarse object boundaries in saliency predictions. To address the aforementioned issues, we propose a Depth Calibration and Boundary-aware Fusion (DCBF) framework that contains two novel components: (1) a learning strategy to calibrate the latent bias in the original depth maps towards boosting the SOD performance; (2) a boundary-aware multimodal fusion module to fuse the complementary cues from RGB and depth channels, as well as to improve object boundary qualities. In addition, we introduce a new saliency dataset, HiBo-UA, which contains 1515 high-resolution RGB-D images with finely-annotated pixel-level labels. To our best knowledge, this is the first RGB-D-based high-resolution saliency dataset with significantly higher image resolution (nearly 7×) than the widely used DUT-D dataset. The proposed high-resolution dataset with richer object boundary details is capable of accurately assessing the performance of various saliency models, in order to retain fine-grained object boundaries. It also facilitates the growing need of our research community in accessing higher-resolution data. Extensive empirical experiments demonstrate the superior performance of our approach against 31 state-of-the-art methods. It is worth noting that our calibrated depth alone can work in a plug-and-play manner; empirically it is shown to bring noticeable improvements when applied to existing state-of-the-art RGB-D SOD models."

# Summary. An optional shortened abstract.
# summary: "A hierarchical recurrent network structure is developed to simultaneously encodes local contexts of individual frames and global contexts of the sequence."

tags:
- IJCV
featured: true

links:
# - name: Custom Link
# url: https://example.org
# url_pdf: https://proceedings.neurips.cc/paper/2021/file/642e92efb79421734881b53e1e1b18b6-Paper.pdf
# url_code: https://github.com/VisualTrackingVLL
# url_dataset: '#'
# url_poster: '#'
# url_project: https://proceedings.neurips.cc/paper/2021/hash/642e92efb79421734881b53e1e1b18b6-Abstract.html
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