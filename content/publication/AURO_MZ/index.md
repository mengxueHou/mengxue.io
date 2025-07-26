---
title: "Mori-Zwanzig Approach for Belief Abstraction with Application to Belief Space Planning"
authors:
- admin
- Tony X. Lin
- Enlu Zhou
- Fumin Zhang
author_notes: ""
date: "2023-09-01T00:00:00Z"
doi: "s10514-024-10185-1"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Autonomous Robots* "
publication_short: "*Autonomous Robots*"

abstract: We propose a learning-based method to extract symbolic representations of the belief state and its dynamics in order to solve planning problems in a continuous-state partially observable Markov decision processes (POMDP) problem. While existing approaches typically parameterize the continuous-state POMDP into a finite-dimensional Markovian model, they are unable to preserve fidelity of the abstracted model. The first major contribution of this paper is  we propose a Neural Network based method to learn the non-Markovian transition model based on the Mori-Zwanzig (M-Z) formalism. Different from existing work in applying M-Z formalism to autonomous time-invariant systems, our approach is the first work generalizing the M-Z formalism to robotics, by addressing the non-Markovian modeling of the belief dynamics that is dependent on historical observations and actions.  The second major contribution is we theoretically show that modeling the non-Markovian memory effect in the abstracted belief dynamics improves the modeling accuracy, which is the key benefit of the proposed algorithm. Simulation experiment of a belief space planning problem is provided to validate the performance of the proposed belief abstraction algorithms.

tags:
- Robotic Planning
- POMDP
- Model Reduction
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://link.springer.com/article/10.1007/s10514-024-10185-1'
url_code: 'https://github.com/mengxueHou/M-Z-based-Belief-Abstraction-for-Symbolic-Planning' 
url_dataset:
url_poster: '/uploads/POMDP_poster.pdf'
url_project: 
url_slides: 
url_source: 
url_video: 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image: featured.png
#caption: "
#focal_point: ""
#preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: 
- robotics

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
