---
title: "Sampling-Based Hierarchical Trajectory Planning for Formation Flight"
authors:
- admin

date: "2024-07-22"
doi: ""


# draft：true之后就不会显示
# draft: true

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Formation flight of unmanned aerial vehicles (UAVs) poses significant challenges in terms of safety and formation keeping, particularly in cluttered environments. However, existing methods often struggle to simultaneously satisfy these two critical requirements. To address this issue, this paper proposes a sampling-based trajectory planning method with a hierarchical structure for formation flight in dense obstacle environments. To ensure reliable local sensing information sharing among UAVs, each UAV generates a safe flight corridor (SFC), which is transmitted to the leader UAV. Subsequently, a sampling-based formation guidance path generation method is designed as the front-end strategy, steering the formation to fly in the desired shape safely with the formation connectivity provided by the SFCs. Furthermore, a model predictive path integral (MPPI) based distributed trajectory optimization method is developed as the back-end part, which ensures the smoothness, safety and dynamics feasibility of the executable trajectory. To validate the efficiency of the developed algorithm, comprehensive simulation comparisons are conducted. The supplementary simulation video can be seen at https://www.youtube.com/watch?v=xSxbUN0tn1M."

# Summary. An optional shortened abstract.
summary:  "**Submitted to IEEE Transactions on Intelligent Transportation Systems(T-ITS)**. A sampling-based trajectory planning method with a hierarchical structure for formation flight in dense obstacle environments is developed. "

tags:

featured: true

links:
- icon_pack: 
  icon: 
  name: Preprint
  url: 'https://arxiv.org/abs/2407.17392'
- icon_pack: 
  icon: 
  name: "YouTube"
  url: https://www.youtube.com/watch?v=xSxbUN0tn1M
url_pdf: https://arxiv.org/pdf/2407.17392
url_source: ''
url_code: 
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: '**A snapshot of the formation flight**'
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




