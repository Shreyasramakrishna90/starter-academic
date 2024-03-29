---
title: Autonomous Driving Testbed
summary: DeepNNCar is a low-cost research testbed for designing, training and testing autonomous driving pipelines and assurance components

tags:
- old


# Optional external URL for project (replaces project detail page).
#external_link: ""

image:
  caption: DeepNNCar Testbed
  #focal_point: Smart


# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

To implement, validate, and test our research products, we have mainly used the CARLA simulator and the DeepNNCar. While CARLA is a well-known open-source urban driving simulator, DeepNNCar is a low-cost research testbed that was designed in the Smart and Resilient Computing for Physical Environments Lab (SCOPE). DeepNNCar is built upon the chassis of Traxxas Slash 2WD 1/10 Scale RC car and is mounted with a USB forward-looking camera, IR- optocoupler, and a 2D LIDAR. The speed and steer for the robot are controlled using pulse-width modulation (PWM), by varying the duty cycle. [[Recommended Reading]](https://ieeexplore.ieee.org/abstract/document/8759365) [[Web Content]](https://medium.com/analytics-vidhya/deepnncar-a-testbed-for-autonomous-algorithms-b0db1ec4770c)

# Demonstration

{{< youtube id="BueAenB4H9w" title="DeepNNCar operating in autonomous mode" >}}

A demonstration of the DeepNNCar operating on an indoor track. The car performs end-to-end driving using a modified [NVIDIA DAVE-II](https://arxiv.org/abs/1604.07316) convolutional neural network. The network is trained to drive within the tracks while achieving high speeds. You can learn more about the platform from our [GitHub](https://github.com/scope-lab-vu/deep-nn-car)  
