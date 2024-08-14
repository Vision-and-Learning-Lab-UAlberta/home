---
title: "GSD: View-Guided Gaussian Splatting Diffusion for 3D Reconstruction"

# if the author is from our lab, then you need to match it with the folder name you can find here
# https://github.com/Vision-and-Learning-Lab-UAlberta/home/tree/master/content/authors
# otherwise just write down their full name
authors:
- yuxuanmu
- xinxinzuo
- chuanguo
- yilinwang
- Juwei Lu
- Xiaofeng Wu
- Songcen Xu
- Peng Dai
- Youliang Yan
- licheng

date: "2024-08-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# you can have this as multiple types, just use a list like ["1", "3"]
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: European Conference on Computer Vision, 2024
publication_short: "*European Conference on Computer Vision (ECCV)*"

abstract: "We present GSD, a diffusion model approach based on Gaussian Splatting (GS) representation for 3D object reconstruction from a single view. Prior works suffer from inconsistent 3D geometry or mediocre rendering quality due to improper representations. We take a step towards resolving these shortcomings by utilizing the recent state-of-the-art 3D explicit representation, Gaussian Splatting, and an unconditional diffusion model. This model learns to generate 3D objects represented by sets of GS ellipsoids. With these strong generative 3D priors, though learning unconditionally, the diffusion model is ready for view-guided reconstruction without further model fine-tuning. This is achieved by propagating fine-grained 2D features through the efficient yet flexible splatting function and the guided denoising sampling process. In addition, a 2D diffusion model is further employed to enhance rendering fidelity, and improve reconstructed GS quality by polishing and re-using the rendered images. The final reconstructed objects explicitly come with high-quality 3D structure and texture, and can be efficiently rendered in arbitrary views. Experiments on the challenging real-world CO3D dataset demonstrate the superiority of our approach."

# Summary. An optional shortened abstract.
summary: 

tags:
  - ECCV

featured: true

links:
url_pdf: https://arxiv.org/abs/2407.04237
# url_code: https://github.com/EricGuo5513/action-to-motion
# url_dataset: https://ericguo5513.github.io/action-to-motion/#data
# url_poster:
url_project: https://yxmu.foo/GSD/
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
