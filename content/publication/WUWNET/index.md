---
title: 'An LSTM based Kalman Filter for Spatio-temporal Ocean Currents Assimilation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ziqiao Zhang
  - admin
  - Fumin Zhang
  - Catherine R. Edwards

  # Author notes (optional)

date: '2019-07-01T00:00:00Z'
doi: '10.1145/3366486.3366522'

# Schedule page publish date (NOT publication's date).
publishDate: '2019-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2019 Proc. of ACM International Conference on Underwater Networks and Systems*
publication_short: In *WUWNet*

abstract:  In this paper, we present a Long Short-Term Memory (LSTM)-based Kalman Filter for data assimilation of a 2D spatio-temporally varying depth-averaged ocean flow field for underwater glider path planning. The data source to the filter combines both the Eulerian flow map with the Lagrangian mobile sensor data stream. The depth-averaged flow is modeled as two components, the tidal and the non-tidal flow component. The tidal flow is modeled with ADCIRC (Advanced Three-Dimensional Circulation Model), while the non-tidal flow field is modeled by a set of spatial basis functions and their time series coefficients. The spatial basis functions are the principal modes derived by performing EOF (Empirical Orthogonal Functions) analysis on the historical surface flow field measured by high frequency radar (HFR), and the temporal coefficients of the spatial basis function are modeled by an LSTM neural network. The Kalman Filter is performed to combine the dynamics derived from the LSTM network, and the observations from the glider flow estimation data. Simulation results demonstrate that the proposed data assimilation method can give flow field prediction of reasonable accuracy.

# Summary. An optional shortened abstract.


tags: [Nonlinear Filtering]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3366486.3366522'
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
  - Distributed sensing

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---
