---
title: "Data-Driven High-Order Point-to-Point ILC With Higher Computational Efficiency"
authors:
- Xueming Zhang
- admin
- Zhongsheng Hou
author_notes: ""
date: "2023-10-01T00:00:00Z"
doi: "10.1109/TASE.2023.3321038"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE transaction on Automation Science and Engineering* "
publication_short: "*IEEE transaction on Automation Science and Engineering*"

abstract: For a class of unknown MIMO non-affine nonlinear repetitive discrete-time systems, a novel data-driven high-order point-to-point iterative learning control scheme is proposed. The control input objective function of this method consists of two parts. One includes the high-order error information, the other consists of the control inputs within the time sub-intervals divided by prescribed desired points. The control law is designed by optimizing this function and it comprises only the known control input signals in the current iteration and the error data in previous iterations. Further, the convergence analysis is conducted in a data-driven way and does not need precise mathematical models. In addition, a scalar index function is set up to evaluate the tracking error convergence rate. By choosing the appropriate high-order factor and corresponding step-size factors, the convergence rate of higher-order learning law is shown to have a faster speed than that of lower-order one. Simulation experiments verify the effectiveness and advantage of this method. Note to Practitioners —The motivation of this paper is to design a control algorithm that only depends on the information of the prescribed desired points, that is, the point-to-point iterative learning control scheme. This control algorithm can be competent for terminal temperature control tasks with very intense chemical reactions and other control tasks that the information except for the I/O data at the prescribed desired points is unavailable. When we want to improve further the control performance at some prescribed desired points, the data of some intermediate time instants can be used to supply extra support for the control system design to improve the control performance at the prescribed desired points. In fact, the point-to-point iterative learning control scheme can be applied to many fields, such as high-speed trains, functional electrical stimulation areas, and positioning X–Y tables. In this paper, a data-driven high-order point-to-point iterative learning control scheme for the MIMO systems is designed, and the stability of this scheme is theoretically analyzed by using the contraction mapping method. Further, the tracking error convergence rate with different order learning law is analyzed. Finally, two numerical simulations are used to verify the effectiveness of the scheme proposed in this paper.

tags:
- Data driven control
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10274888' 
url_code: 
url_dataset:
url_poster: 
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
- Data Driven Control

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
