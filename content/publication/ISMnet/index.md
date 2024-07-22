---
title: "Influential Simplices Mining via Simplicial Convolutional Networks"
authors:
- Yujie
- admin
- Qiang Wu
- Linyuan 
- (Co-first author)
date: "2024-06-29"
doi: "10.1016/j.ipm.2024.103813"


# draft：true之后就不会显示
draft: true

# Schedule page publish date (NOT publication's date).
# publishDate: "2024-06-14"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Information Processing & Management"
publication_short: "Information Processing & Management"

abstract: "Simplicial complexes have recently been in the limelight of higher-order network analysis, where a minority of simplices play crucial roles in structures and functions due to network heterogeneity. We find a significant inconsistency between identifying influential nodes and simplices. Therefore, it remains elusive how to characterize simplices' influence and identify influential simplices, despite the relative maturity of research on influential nodes (0-simplices) identification. Meanwhile, graph neural networks (GNNs) are potent tools that can exploit network topology and node features simultaneously, but they struggle to tackle higher-order tasks. In this paper, we propose a higher-order graph learning model, named higher-order influencer mining neural network (ISMnet), to identify vital h-simplices in simplicial complexes. In this paper, we propose a higher-order graph learning model, named influential simplices mining neural network (ISMnet), to identify vital $h$-simplices in simplicial complexes. It can tackle higher-order tasks by leveraging novel higher-order presentations: hierarchical bipartite graphs and higher-order hierarchical (HoH) Laplacians, where targeted simplices are grouped into a hub set and can interact with other simplices.  Furthermore, ISMnet employs learnable graph convolutional operators in each HoH Laplacian domain to capture interactions among simplices, and it can identify influential simplices of arbitrary order by changing the hub set.  Empirical results demonstrate that ISMnet significantly outperforms existing methods in ranking 0-simplices (nodes) and 2-simplices. In general, this novel framework excels in identifying influential simplices and promises to serve as a potent tool in higher-order network analysis."
# Summary. An optional shortened abstract.
summary:  "*Information Processing & Management.* Detected an inconsistency between mining influential nodes and simplices. Innovatively formulated the influential simplices mining task as a graph learning problem and designed an influential simplices mining neural network (ISMnet) that achieves SOTA performance in this task."

# tags:
# - Source Themes
featured: True

links:
- icon_pack: 
  icon: 
  name: Preprint
  url: 'https://arxiv.org/pdf/2307.05841.pdf'
- icon_pack: 
  icon: 
  name: "公众号解读"
  url: 'https://mp.weixin.qq.com/s/DnmGTCx0EJ873OsnW1_jYQ'
url_pdf: 'https://doi.org/10.1016/j.ipm.2024.103813'
url_code: ''
url_dataset: 'https://github.com/sssleverlily/ISMnet'
url_poster: ''
url_project: ''
url_source: ''
url_video: ''


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: '**ISMnet**'
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

Supplementary notes can be added here, including [code and math](xxx).
