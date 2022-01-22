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
  page_type: event
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
Tremendous advances have been made in the area of autonomous Cyber Physical Systems (CPSs) in the last decades, through self-driving cars, unmanned robots, unmanned aerial vehicles, etc. Despite its widespread use, there are still challenges in designing fully autonomous systems, as guaranteeing the safety of such systems is challenging. The primary goal of my research is to quantify the risk posed to autonomous systems and select a suitable mitigation strategy for mitigating the risk during operation. To achieve this goal, I have developed a **Dynamic Safety Assurance framework** with three components that perform the following activities at runtime. (a) Detect invalidation of the design-time assumptions and identify the factor(s) responsible for the problem. Primarily, I am interested in detecting the Out-of-Distribution data problem caused by the violation of the closed-world assumption made in training the machine learning components. (b) Assess the system's risk at runtime, given the current operating conditions, the known sensor and actuator faults, and the information from the detectors (dynamic risk assessment). (c) Mitigate the risk by dynamically selecting a suitable control action for the system (adaptive mitigation strategy). However, designing these components is non-trivial because they must operate at runtime on CPS testbeds like small scale autonomous cars and robots that have short inference times (50 - 100 milliseconds) and limited onboard computational resources (e.g., Raspberry Pi, NVIDIA Jetson TX2).
