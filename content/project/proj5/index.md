---
title: Research Vertical 3 - Adaptive Mitigation for Risk Mitigation of Autonomous Systems
summary: Cyber-Physical Systems need a contingency plan once it encounters high risk because of operational hazards.

tags:
- old


# Optional external URL for project (replaces project detail page).
#external_link: ""

image:
  caption: DeepNNCar Autonomous Robot Testbed
  #focal_point: Smart


# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

## Summary

CPSs have increasingly started using LECs for performing perception-based control tasks. The simple design approach, and their capability to continuously learn has led to their widespread use in different autonomous applications. Despite their simplicity and impressive capabilities, these models are difficult to assure, which makes their use challenging. The problem of assuring CPS with untrusted controllers has been achieved using the Simplex Architecture. This architecture integrates the system to be assured with a safe controller and provides a decision logic to switch between the decisions of these controllers. However, designing Simplex Architectures for Learning-enabled CPSs is complex, because of the LECs black-box nature. To address this, i've proposed the dynamic-weighted simplex strategy that uses reinforcement-learning as the decision logic. We have implemented the dynamic-weighted simplex strategy on the DeepNNCar platform.
