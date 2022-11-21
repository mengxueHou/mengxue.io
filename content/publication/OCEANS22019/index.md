---
title: 'Partitioning Ocean Flow Field for Underwater Vehicle Path Planning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Haoyan Zhai
  - Haomin Zhou
  - Fumin Zhang
  # Author notes (optional)

date: '2019-07-01T00:00:00Z'
doi: '10.1109/OCEANSE.2019.8867327'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proc. of MTS /IEEE OCEANS’ 19, Marseille, France*
publication_short: In *OCEANS*

abstract: In this paper, we present a flow field partition method that extracts the key features, which are the spatial and temporal variation of the flow field. The partition method is developed based on K-means algorithm. In the case where the temporal pattern of the flow field contains only a periodic tidal component, we propose an algorithm that partitions the flow field into static clusters of piece-wise constant flow, by performing K-means clustering over the time-averaged flow field. Then the method is extended to partitioning the flow field into clusters of uniform time-varying flow, by fitting the spatially averaged flow in each static partitioned region to a parametric flow model. Simulation results of partitioning both a simulated jet flow field, as well as the ocean surface flow data into time-invariant and time-varying uniform flow are presented to demonstrate that the proposed method can represent the true flow field with significantly less amount of data. Result of using Method of Evolving Junctions to plan the time-optimal path in the partitioned flow field is also presented to demonstrate that the proposed flow partitioning method can be applied to facilitate path planning, and can reduce the path planning computational cost.


# Summary. An optional shortened abstract.


tags: [planning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/8867327'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://github.com/mengxueHou/mengxue.io/blob/4da974728d02aad3f1a0fa7bb4fd3edd0f741a4d/static/uploads/OCEANS_Marseille_poster_v2.pdf'
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
  - Robotic planning

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
