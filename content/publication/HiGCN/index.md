---
title: "Higher-order Graph Convolutional Network with Flower-Petals Laplacians on Simplicial Complexes"
authors:
- admin
- Yujie
- Qiang Wu
- Linyuan
date: "2023-09-22"
doi: ""


# draft：true之后就不会显示
draft: true

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-22"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 38th AAAI Conference on Artificial Intelligence"
publication_short: "AAAI24"

abstract: "Despite the recent successes of vanilla Graph Neural Networks (GNNs) on many tasks, their foundation on pairwise interaction networks inherently limits their capacity to discern latent higher-order interactions in complex systems. To bridge this capability gap, we propose a novel approach exploiting the rich mathematical theory of simplicial complexes (SCs) - a robust tool for modeling higher-order interactions. Current SC-based GNNs are burdened by high complexity and rigidity, and quantifying higher-order interaction strengths remains challenging. Innovatively, we present a higher-order Flower-Petals (FP) model, incorporating FP Laplacians into SCs. Further, we introduce a Higher-order Graph Convolutional Network (HiGCN) grounded in FP Laplacians, capable of discerning intrinsic features across varying topological scales. By employing learnable graph filters, a parameter group within each FP Laplacian domain, we can identify diverse patterns where the filters' weights serve as a quantifiable measure of higher-order interaction strengths. The theoretical underpinnings of HiGCN's advanced expressiveness are rigorously demonstrated. Additionally, our empirical investigations reveal that the proposed model accomplishes state-of-the-art (SOTA) performance on a range of graph tasks and provides a scalable and flexible solution to explore higher-order interactions in graphs."

# Summary. An optional shortened abstract.
summary:  "*AAAI24*. Introduced a novel higher-order representation, the flower-petals (FP) model, and higher-order graph convolutional network (HiGCN), which achieves SOTA in various tasks and quantifies higher-order strength. "

tags:
- Source Themes
featured: true

links:
- icon_pack: 
  icon: 
  name: Preprint
  url: 'https://arxiv.org/abs/2309.12971'
- icon_pack: 
  icon: 
  name: "YouTube"
  url: https://www.youtube.com/watch?v=pe-L20ncdAQ
- icon_pack: 
  icon: 
  name: "Bilibili"
  url: https://www.bilibili.com/video/BV1vc41147Df/?spm_id_from=333.1007.top_right_bar_window_default_collection.content.click&vd_source=e060cbe71c18d308e963782a155bf798
- icon_pack: 
  icon: 
  name: "公众号解读"
  url: https://mp.weixin.qq.com/s/uhHhMvYrjPc0miuACbuvjw
url_pdf: https://arxiv.org/pdf/2309.12971.pdf
url_source: ''
url_code: https://github.com/Yiminghh/HiGCN
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: '**HiGCN**'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](xx).
