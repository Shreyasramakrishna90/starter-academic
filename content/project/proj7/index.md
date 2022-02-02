---
title: Toolchain for AI-based Cyber-Physical Systems Development
summary: Design and development of Machine Learning components includes several steps like training, testing, and validation. Manually, performing these steps is difficult because of the several hyperparameters that require tuning. Automation can greatly aid designing these systems.

#tags:
#- old


# Optional external URL for project (replaces project detail page).
#external_link: ""

image:
  caption: Workflow
  #focal_point: Smart


# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

To implement, validate, and test our research products, we have mainly used the CARLA simulator and the DeepNNCar. While CARLA is a well-known open-source urban driving simulator, DeepNNCar is a low-cost research testbed that was designed in the Smart and Resilient Computing for Physical Environments Lab (SCOPE). DeepNNCar is built upon the chassis of Traxxas Slash 2WD 1/10 Scale RC car and is mounted with a USB forward-looking camera, IR- optocoupler, and a 2D LIDAR. The speed and steer for the robot are controlled using pulse-width modulation (PWM), by varying the duty cycle. [[Recommended Reading]](https://ieeexplore.ieee.org/abstract/document/8759365) [[Web Content]](https://medium.com/analytics-vidhya/deepnncar-a-testbed-for-autonomous-algorithms-b0db1ec4770c)
