---
title: WorldDriveVLA 
# event: NetSci 2022


# location: Tianjin (Online)


summary: The development of the unified framework for image prediction and trajectory generation.The project is underway, more details will be shown when it is completed.


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2025-09-01"
date_end: "2026-08-31"
all_day: true

draft: false

authors: 
- admin
  
tags: []
# tags:
# - Source Themes
featured: false

# Is this a featured talk? (true/false)
# featured: true


links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""



# Enable math on this page?
math: true
---

## Project Overview:

To address the challenges of sparse supervision signals and lack of scene inference capabilities in current autonomous driving VLA models under the traditional imitation learning paradigm, WorldDriveVLA is developed: an end-to-end autonomous driving framework that integrates world models and VLA models. This work employs a native unified multimodal feature representation within an autoregressive model architecture, achieving deep alignment of visual, linguistic, and action information in the semantic space. Through multi-task self-supervised training on large-scale driving data, the model simultaneously learns dynamic modeling of the external world and its own motion planning. Building upon the general understanding and reasoning capabilities of VLA models, this framework further enables explicit inference of future driving scenarios, thereby improving the robustness and interpretability of autonomous driving decision-making and planning.
