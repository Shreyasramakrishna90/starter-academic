---
title: Research Overview - Dynamic Safety Assuring of Autonomous Systems
summary: My research focuses on dynamic safety assurance of autonomous systems with machine learning components

tags:
- overview


# Optional external URL for project (replaces project detail page).
#external_link: ""

image:
  caption: Research Overview
  #focal_point: Smart


# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

## Summary
Tremendous advances have been made in the area of autonomous Cyber Physical Systems (CPSs) in the last decades, through self-driving cars, unmanned robots, unmanned aerial vehicles, etc. Despite its widespread use, there are still challenges in designing fully autonomous systems, as guaranteeing the safety of such systems is challenging. The primary goal of my research is to quantify the risk posed to autonomous systems and select a suitable mitigation strategy for mitigating the risk during operation. To achieve this goal, I have developed a Dynamic Safety Assurance framework with three components that perform the following activities at runtime. (a) Detect invalidation of the design-time assumptions and identify the factor(s) responsible for the problem. Primarily, I am interested in detecting the Out-of-Distribution data problem caused by the violation of the closed-world assumption made in training the machine learning components. (b) Assess the system's risk at runtime, given the current operating conditions, the known sensor and actuator faults, and the information from the detectors (dynamic risk assessment). (c) Mitigate the risk by dynamically selecting a suitable control action for the system (adaptive mitigation strategy). However, designing these components is non-trivial because they must operate at runtime on CPS testbeds like small scale autonomous cars and robots that have short inference times (50 - 100 milliseconds) and limited onboard computational resources (e.g., Raspberry Pi, NVIDIA Jetson TX2).
