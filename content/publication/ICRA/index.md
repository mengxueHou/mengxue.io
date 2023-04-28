---
title: 'Belief Space Partitioning for Symbolic Motion Planning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tony X. Lin
  - Wei Zhang
  - Catherine R. Edwards
  - Fumin Zhang
  # Author notes (optional)

date: '2021-07-01T00:00:00Z'
doi: '10.1109/ICRA48506.2021.9561121'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2021 IEEE International Conference on Robotics and Automation*
publication_short: In *ICRA*

abstract: We propose a memory-constrained partition-based method to extract symbolic representations of the belief state and its dynamics in order to solve planning problems in a partially observable Markov decision process (POMDP). Our K-means partitioning strategy uses a fixed number of symbols to represent the partitions of the belief space and ensures the parameterization of the belief dynamics does not grow exponentially as the system dimension increases. By casting our problem as a partitioning of the POMDP, we can then solve planning problems using traditional symbolic planning solvers (such as HTN or A* solvers). Our work is motivated by an autonomous underwater vehicle navigation problem where the vehicle is affected by uncertain flow conditions and receives severely limited position observations. Simulation experiments are provided to validate the performance of the proposed algorithms.

# Summary. An optional shortened abstract.


tags: [Robotic Planning, Automated Planning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9561121'
url_code: 
url_dataset: 
url_poster: 
url_project: 
url_slides: 'https://github.com/mengxueHou/mengxue.io/blob/43574696af72925718fa19aada15000ebb227dd7/static/uploads/ICRA_slides.pdf'
url_source: 
url_video: 

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
slides: 
---
