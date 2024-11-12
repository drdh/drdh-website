---
title: 'Enhancing Decision-Making of Large Language Models via Actor-Critic'

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
publication: Submit to *The Thirteenth International Conference on Learning Representations*
publication_short: Submit to *ICLR*

abstract: Large Language Models (LLMs) have achieved significant advancements in natural language processing tasks, yet they encounter challenges in complex decision-making scenarios that require long-term reasoning and alignment with high-level objectives. This paper introduces a novel gradient-free LLM-based Actor-Critic framework, termed LAC, which addresses these limitations by integrating both action generation and action evaluation mechanisms. Our approach employs two distinct critics, a language-based critic that provides context-sensitive feedback and a value-based critic that offers quantitative assessments of expected long-term rewards. This dual-critic architecture enhances decision-making by leveraging the complementary strengths of both critics, enabling contextually appropriate and more robust action selection. Additionally, we propose a gradient-free policy improvement method that reduces computational overhead, facilitating efficient updates to the actor’s policy without the complexities of gradient backpropagation. We validate the effectiveness of LAC across diverse environments that cover both high-level action space (ALFWorld) and low-level action space (BabyAI-Text), demonstrating its superior performance compared to existing state-of-the-art methods. Our method outperforms other state-of-the-art baselines using the same 7B/8B open-source LLMs and even exceeds a strong baseline ReAct using GPT-4 in most settings. Our findings highlight the efficacy and generality of the dual-critic Actor-Critic framework in enhancing LLM-based decision-making.



# Summary. An optional shortened abstract.
summary:  We propose an LLM-based Actor-Critic algorithm that integrates actor and critic methods in the way that would utilize the merits of the actor-critic algorithm with the strengths of LLMs.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf:  'https://openreview.net/pdf?id=q9jQPA6zPK'
url_pdf: 'uploads/paper_tmp.pdf'
# url_code: 'https://github.com/drdh/HERD'
url_dataset: ''
# url_poster: 'poster.pdf'
url_project: 'https://sites.google.com/view/lang-ac'
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
