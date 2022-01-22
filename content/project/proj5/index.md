---
title: Adaptive Decision Making for Risk Mitigation of Autonomous Systems
summary: Cyber-Physical Systems need a contingency plan once it encounters high risk because of operational hazards.

#tags:
#- old


# Optional external URL for project (replaces project detail page).
#external_link: ""

image:
  caption: Reinforcement Learning Setup used for Simplex decision Logic
  #focal_point: Smart


# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

Adaptive decision-making for mitigation is a decisive step of my dynamic assurance framework. Once a problem has been detected, and the system risk is assessed, this information needs to be proactively used for selecting a suitable control action that mitigates the system's risk. [Simplex Architecture](https://ieeexplore.ieee.org/abstract/document/703255?casa_token=b0hDZcHUVyEAAAAA:OOwd116kACcSTNvS2kPzORhUTmzYF8QlX5KS3i9YJpGaMq9-YjbTmrX1Dz0Jb521WuKGDaFH9Q) has been widely utilized as a mitigation strategy in Cyber-Physical Systems. This architecture integrates the system to be assured with a safe controller and provides a decision logic to switch between the decisions of these controllers. However, the decision logic is always designed "offline" and used at runtime for control action selection. Such an offline logic cannot optimally balance the safety vs. mission-critical information (e.g., performance) of the system employing the architecture. I have been working towards a "proactive" and "adaptive" decision logic to address this limitation. I have used reinforcement learning in my previous work, and I plan to use Monte Carlo Tree Search (MCTS) to learn an online decision logic at runtime. [Recommended Reading](https://www.sciencedirect.com/science/article/abs/pii/S1383762120300540)
