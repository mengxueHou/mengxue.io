---
title: "Bounded Cost Path Planning for Underwater Vehicles Assisted by a Time-Invariant Partitioned Flow Field Model"
authors:
- admin
- Sungjin Cho
- Haomin Zhou
- Catherine R. Edwards
- Fumin Zhang
author_notes: ""
date: "2022-09-01T00:00:00Z"
doi: 10.3389/frobt.2021.575267

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Frontiers in Robotics and AI* (8), 575267"
publication_short: ""

abstract: A bounded cost path planning method is developed for underwater vehicles assisted by a data-driven flow modeling method. The modeled flow field is partitioned as a set of cells of piece-wise constant flow speed. A flow partition algorithm and a parameter estimation algorithm are proposed to learn the flow field structure and parameters with justified convergence. A bounded cost path planning algorithm is developed taking advantage of the partitioned flow model. An extended potential search method is proposed to determine the sequence of partitions that the optimal path crosses. The optimal path within each partition is then determined by solving a constrained optimization problem. Theoretical justification is provided for the proposed extended potential search method generating the optimal solution. The path planned has the highest probability to satisfy the bounded cost constraint. The performance of the algorithms is demonstrated with experimental and simulation results, which show that the proposed method is more computationally efficient than some of the existing methods.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Robotics
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: "https://www.frontiersin.org/articles/10.3389/frobt.2021.575267/full"
url_code: ""
url_dataset: "
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: "

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
projects: [path-planning]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
