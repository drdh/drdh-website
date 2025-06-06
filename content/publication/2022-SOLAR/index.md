---
title: 'Low-Rank Modular Reinforcement Learning via Muscle Synergy'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tonghan Wang
  - Jiayuan Liu
  - Chongjie Zhang

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2022-10-27T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-27T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Neural Information Processing Systems*
publication_short: In *NeurIPS 2022*

abstract: Modular Reinforcement Learning (RL) decentralizes the control of multi-joint robots by learning policies for each actuator. Previous work on modular RL has proven its ability to control morphologically different agents with a shared actuator policy. However, with the increase in the Degree of Freedom (DoF) of robots, training a morphology-generalizable modular controller becomes exponentially difficult. Motivated by the way the human central nervous system controls numerous muscles, we propose a Synergy-Oriented LeARning (SOLAR) framework that exploits the redundant nature of DoF in robot control. Actuators are grouped into synergies by an unsupervised learning method, and a synergy action is learned to control multiple actuators in synchrony. In this way, we achieve a low-rank control at the synergy level. We extensively evaluate our method on a variety of robot morphologies, and the results show its superior efficiency and generalizability, especially on robots with a large DoF like Humanoids++ and UNIMALs.

# Summary. An optional shortened abstract.
summary: Synergy-Oriented LeARning Framework (SOLAR).

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=zYc5FSxL6ar'
url_code: 'https://github.com/drdh/Synergy-RL'
url_dataset: ''
url_poster: 'poster.pdf'
url_project: 'https://sites.google.com/view/synergy-rl/'
url_slides: 'slides.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Synergy discovery and synergy-aware policy learning.'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
