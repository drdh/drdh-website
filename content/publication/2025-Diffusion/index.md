---
title: 'On Diffusion Models for Multi-Agent Partial Observability: Shared Attractors, Error Bounds, and Composite Flow'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tonghan Wang
  - admin
  - Yanchen Jiang
  - David C. Parkes
  - Milind Tambe

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-10-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-10-03T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
# publication: In *The Twelfth International Conference on Learning Representations*
# publication_short: In *ICLR*
publication: In *The 24th International Conference on Autonomous Agents and Multiagent Systems*
publication_short: In *AAMAS 2025*

abstract: Multiagent systems grapple with partial observability (PO), and the decentralized POMDP (Dec-POMDP) model highlights the fundamental nature of this challenge. Whereas recent approaches to address PO have appealed to deep learning models, providing a rigorous understanding of how these models and their approximation errors affect agents' handling of PO and their interactions remain a challenge. In addressing this challenge, we investigate reconstructing global states from local action-observation histories in Dec-POMDPs using diffusion models. We first find that diffusion models conditioned on local history represent possible states as stable fixed points. In collectively observable (CO) Dec-POMDPs, individual diffusion models conditioned on agents' local histories share a unique fixed point corresponding to the global state, while in non-CO settings, the shared fixed points yield a distribution of possible states given joint history. We further find that, with deep learning approximation errors, fixed points can deviate from true states and the deviation is negatively correlated to the Jacobian rank. Inspired by this low-rank property, we bound the deviation by constructing a surrogate linear regression model that approximates the local behavior of diffusion models. With this bound, we propose a composite diffusion process iterating over agents with theoretical convergence guarantees to the true state.



# Summary. An optional shortened abstract.
summary:  We show that diffusion models can reconstruct global states in decentralized partially observable multiagent systems, with approximation errors leading to deviations that can be bounded for convergence to the true state.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf:  'https://arxiv.org/pdf/2410.13953'
# url_code: 'https://github.com/drdh/HERD'
url_dataset: ''
# url_poster: 'poster.pdf'
# url_project: 'https://sites.google.com/view/lang-ac'
# url_slides: 'slides.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'diffusion'
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
