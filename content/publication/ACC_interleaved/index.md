---
title: 'An Interleaved Algorithm for Integration of Robotic Task and Motion Planning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yingke Li
  - Fumin Zhang
  - Shreyas Sundaram 
  - Shaoshuai Mou
# Author notes (optional)

date: '2023-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2023 American Control Conference*
publication_short: In *ACC (accepted)*

abstract: We propose an interleaved method for robotic task and motion planning (TAMP) problems, which involves optimizing both continuous and discrete dynamic behaviors. The coupling between the task planning and motion planning results in a very large search space, causing challenge for computing the optimal solution. To address this challenge, we develop a novel bi-level algorithm leveraging the Depth First Search (DFS) algorithm and the Monte Carlo Tree Search (MCTS) algorithm to solve the TAMP. Incorporating task completion cost estimation from the motion planning level, we solve the task planning problem in a computationally efficient manner. We prove that our proposed TAMP algorithm is complete, i.e., it always finds the optimal solution if there exists one. Finally, we present simulation results to demonstrate that the proposed algorithm can find the optimal solution of the TAMP problem with lower computation cost than existing algorithms. 

# Summary. An optional shortened abstract.


tags: [planning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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

