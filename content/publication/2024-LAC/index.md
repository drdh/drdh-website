---
title: 'Implementing Actor-Critic with Large Language Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Kefei Duan
  - Chongjie Zhang

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-05-23T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-23T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
# publication: In *The Twelfth International Conference on Learning Representations*
# publication_short: In *ICLR*
publication: Submit to *Thirty-eighth Annual Conference on Neural Information Processing Systems*
publication_short: Submit to *NeurIPS*

abstract: While large language models (LLMs) have shown impressive capability across numerous tasks, they often struggle with interactive decision-making tasks if they are used as actor-only methods, i.e., directly generating and selecting actions based on previous trajectories. This struggle is because LLMs generate textual action auto-regressively and do not conduct explicit long-term planning, which is often necessary for decision-making tasks. Hence recent work turns to critic-only methods, which use other repurposed LLMs as critics to evaluate each action candidate through planning and simulating and select the action with the best-estimated evaluation. However, both actor-only and critic-only methods ignore the interrelation between actor and critic, prioritize one over the other, and insufficiently exploit the valuable knowledge from the actor and critic for decision-making. To address this problem, we propose to integrate prior actor-only and critic-only methods in the way that would utilize the merits of the actor-critic algorithm with the strengths of LLMs. Specifically, we design two novel critics to exploit the strong prior knowledge in LLMs and integrate them with the actor via in-context learning and solving an optimization problem, respectively, during different decision-making phases. Empirically, we apply our approach to a diverse set of decision-making tasks that cover both high-level action space (ALFWorld) and low-level action space (BabyAI-text). Our method outperforms other state-of-the-art baselines using the same 7B/8B open-source LLMs and even exceeds ReAct using GPT-4 in most settings.

# Summary. An optional shortened abstract.
summary:  We propose an LLM-based Actor-Critic algorithm that integrates prior actor-only and critic-only methods in the way that would utilize the merits of the actor-critic algorithm with the strengths of LLMs.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf:  https://openreview.net/pdf?id=q9jQPA6zPK'
# url_code: 'https://github.com/drdh/HERD'
url_dataset: ''
# url_poster: 'poster.pdf'
# url_project: 'https://sites.google.com/view/hyperbolic-robot-design'
# url_slides: 'slides.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Actor-Critic'
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
