---
title: "Towards Natural and Accurate Future Motion Prediction of Humans and
Animals"
authors:
- shuangwu
- Zhenguang Liu
- Shuyuan Jin
- Qi Liu
- Shijian Lu
- Roger Zimmermann
- licheng

date: "2019-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition"
publication_short: "CVPR"

abstract: Anticipating the future motions of 3D articulate objects is challenging due to its non-linear and highly stochastic nature. Current approaches typically represent the skeleton of an articulate object as a set of 3D joints, which unfortunately ignores the relationship between joints, and fails to encode fine-grained anatomical constraints. Moreover, conventional recurrent neural networks, such as LSTM and GRU, are employed to model motion contexts, which inherently have difficulties in capturing long-term dependencies. To address these problems, we propose to explicitly encode anatomical constraints by modeling their skeletons with a Lie algebra representation. Importantly, a hierarchical recurrent network structure is developed to simultaneously encodes local contexts of individual frames and global contexts of the sequence. We proceed to explore the applications of our approach to several distinct quantities including human, fish, and mouse. Extensive experiments show that our approach achieves more natural and accurate predictions over state-of-the-art methods.

# Summary. An optional shortened abstract.
summary: "A hierarchical recurrent network structure is developed to simultaneously encodes local contexts of individual frames and global contexts of the sequence."

tags:
- CVPR
featured: true

links:
# - name: Custom Link
# url: https://example.org
url_pdf: https://www.ece.ualberta.ca/~lcheng5/papers/LiuEtAl_CVPR19.pdf
url_code: https://github.com/BII-wushuang/Lie-Group-Motion-Prediction
# url_dataset: '#'
# url_poster: '#'
url_project: 'https://coderstellaj.github.io/Hierarchical-Motion-Recurrent-Network-Website/'
# url_slides: ''
# url_source: '#'
url_video: 'https://www.youtube.com/watch?v=qi33KKUzrVA&feature=emb_title'


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
projects:
- shuang_hmr_2019

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

