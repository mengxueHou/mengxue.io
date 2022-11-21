---
title: 'Dynamic Event-triggered Integrated Task and Motion Planning for Process-aware Source Seeking'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yingke Li
  - admin
  - Enlu Zhou
  - Fumin Zhang
  # Author notes (optional)

date: '2023-07-01T00:00:00Z'
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
publication_short: In *ACC*

abstract: The process-aware source seeking (PASS) problem in flow fields aims to find an informative trajectory to reach an unknown source location while taking the energy consumption in the flow fields into consideration. Taking advantage of the existing methods on flow field partition, this paper formulates this problem as a task and motion planning (TAMP) problem and proposes a bi-level hierarchical planning framework to decouple the planning of inter-region transition and inner-region trajectory by introducing inter-region junctions. An integrated strategy is utilized to enable efficient upper-level planning by investigating the optimal solution of the lower-level planner. In order to leverage the triggering rate and the performance, a dynamic event-triggered mechanism is introduced to decide the triggering conditions for both measurements and re-plans. The proposed algorithm provides guaranteed convergence of the trajectory, and achieves automatic trade-off between exploration and exploitation. The simulation results demonstrate that the proposed algorithm greatly reduces the energy consumption as well as the frequencies of measurements and re-plans.

# Summary. An optional shortened abstract.


tags: [Planning]

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
  - Robotic planning

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---
