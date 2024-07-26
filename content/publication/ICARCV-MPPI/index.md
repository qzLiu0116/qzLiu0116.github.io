---
title: "A Gradient-free and Parallel Hierarchical Motion Planning Framework for Quadrotor Swarm"
authors:
- Xuewei Zhang
- admin
- Hongyu Cao
- Bailing Tian

date: "2024-06-30"
doi: ""


# draft：true之后就不会显示
# draft: true

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Quadrotor swarm with advanced coordination capabilities has garnered widespread attention, yet efficient
and reliable motion planning remains a challenge. This paper presents a hierarchical motion planning framework for quadrotor swarm autonomous navigation in unknown cluttered scenes. Specifically, we take a step forward sampling of multiple
neighbors in the lattice graph and generate a group of paths. The infeasible paths are excluded and the one with the minimum cost is chosen from the remaining. Taking it as a guiding path, a gradient-free trajectory optimization method based on model predictive path integral (MPPI) is developed to produce the execution trajectory. Compared to gradient-descent approaches, it is capable of dealing with non-continuous and non-convex constraints. Additionally, the proposed method is deployed on GPUs in parallel to enhance efficiency. Extensive simulations demonstrate the robustness and effectiveness of the proposed motion planning framework."

# Summary. An optional shortened abstract.
summary:  "**Submitted to The International Conference on Control, Automation, Robotics and Vision,2024 (ICARCV 2024)**. A gradient-free trajectory optimization method based on model predictive path integral (MPPI) is developed."

tags:

featured: true

links:
url_pdf: 
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
  caption: '**Simulation Results**'
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




