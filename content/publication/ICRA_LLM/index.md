---
title: 'OceanChat: Piloting Autonomous Underwater Vehicles in Natural Language'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ruochu Yang
  - admin
  - Junkai Wang
  - Fumin Zhang
  # Author notes (optional)

date: '2023-10-01T00:00:00Z'
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: '2021-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2024 IEEE International Conference on Robotics and Automation*
publication_short: In *ICRA (under review)*

abstract: In the trending research of fusing Large Language Models (LLMs) and robotics, we aim to pave the way for innovative development of AI systems that can enable Autonomous Underwater Vehicles (AUVs) to seamlessly interact with humans in an intuitive manner. We propose OceanChat, a system that leverages a closed-loop LLM-guided task and motion planning framework to tackle AUV missions in the wild. LLMs translate an abstract human command into a high-level goal, while a task planner further grounds the goal into a task sequence with logical constraints. To assist the AUV with understanding the task sequence, we utilize a motion planner to incorporate real-time Lagrangian data streams received by the AUV, thus mapping the task sequence into an executable motion plan. Considering the highly dynamic and partially known nature of the underwater environment, an event-triggered replanning scheme is developed to enhance the system's robustness towards uncertainty. We also build a simulation platform HoloEco that generates photo-realistic simulation for a wide range of AUV applications. Experimental evaluation verifies that the proposed system can achieve improved performance in terms of both success rate and computation time. 

# Summary. An optional shortened abstract.


tags: [Robotic Planning, Automated Planning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2309.16052'
url_code: 
url_dataset: 
url_poster: 
url_project: 
url_slides: 
url_source: 
url_video: 'https://sites.google.com/view/oceanchat'

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
  - Task and Motion Planning

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---
