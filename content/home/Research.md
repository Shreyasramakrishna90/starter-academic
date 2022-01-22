---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: 'Research Overview'
subtitle:

content:
  # Page type to display. E.g. post, event, publication...
  page_type: research
  # Choose how many pages you would like to display (0 = all pages)
  count: 5
  # Filter on criteria
  filters:
    author: ""
    category: ""
    tag: ""
    exclude_featured: false
    exclude_future: false
    exclude_past: false
    publication_type: ""
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc

design:
  # Choose a view for the listings:
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view: 2
---
# Dynamic Safety Assurance of Autonomous Systems
<p align="center">
  <img src="media/featured.jpg" />
</p>

Tremendous advances have been made in the area of autonomous Cyber Physical Systems (CPSs) in the last decades, through self-driving cars, unmanned robots, unmanned aerial vehicles, etc. Despite its widespread use, there are still challenges in designing fully autonomous systems, as guaranteeing the safety of such systems is challenging. The primary goal of my research is to quantify the risk posed to autonomous systems and select a suitable mitigation strategy for mitigating the risk during operation. I have been developing a **Dynamic Safety Assurance framework** with three components that perform the following activities at runtime to achieve this goal. (a) Detect anomalies in the system's components at runtime. Primarily, I am interested in detecting the Out-of-Distribution data problem caused by the violation of the closed-world assumption made in training the machine learning components (Out-of-Distribution Detection and Feature Identification). (b) Assess the system's risk at runtime, given the current operating conditions, the known sensor and actuator faults, and the information from the detectors (dynamic risk assessment). (c) Mitigate the risk by dynamically selecting a suitable control action for the system (adaptive mitigation strategy). However, designing these components is non-trivial because they must operate at runtime on small-scale CPS testbeds like [DeepNNCar](https://github.com/scope-lab-vu/deep-nn-car) and [F1/10 car](https://f1tenth.org/) that have short inference times (50 - 100 milliseconds) and limited onboard computational resources (e.g., Raspberry Pi, NVIDIA Jetson TX2).

<!-- [![Screenshot](https://github.com/Shreyasramakrishna90/starter-academic/blob/master/static/media/featured.jpg) -->
