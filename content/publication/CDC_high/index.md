---
title: 'High-dimensional Optimal Density Control with Wasserstein Metric Matching'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shaojun Ma
  - admin
  - Xiaojing Ye
  - Haomin Zhou
# Author notes (optional)

date: '2023-01-01T00:00:00Z'
doi: '10.1109/CDC49753.2023.10384042'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2023 Conference on Decision and Control*
publication_short: In *CDC*

abstract: We present a novel computational framework for density control in high-dimensional state spaces. The considered dynamical system consists of a large number of indistinguishable agents whose behaviors can be collectively modeled as a time-evolving probability distribution. The goal is to steer the agents from an initial distribution to reach (or approximate) a given target distribution within a fixed time horizon at minimum cost. To tackle this problem, we propose to model the drift as a nonlinear reduced-order model, such as a deep network, and enforce the matching to the target distribution at terminal time either strictly or approximately using the Wasserstein metric. The resulting saddle-point problem can be solved by an effective numerical algorithm that leverages the excellent representation power of deep networks and fast automatic differentiation for this challenging high-dimensional control problem. A variety of numerical experiments were conducted to demonstrate the performance of our method.

# Summary. An optional shortened abstract.


tags: [Robotic Planning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2307.13135'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - Robotic Planning

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

