---
title: Out-of-Distribution Detection and Feature Identification
summary: Though machine learning components have shown remarkable performance for challenging tasks such as autonomous driving ([NVIDIA DAVE-II](https://www.youtube.com/watch?v=NJU9ULQUwng&ab_channel=IProgrammerTV)), they have shown to be susceptible to slight shifts in the operating contexts, popularly known as out-of-distribution (OOD) data.

tags:
- old


# Optional external URL for project (replaces project detail page).
#external_link: ""

image:
  caption: Automated Workflow for Out-of-Distribution Detection using B-Variational Autoencoders
  #focal_point: Smart


# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

Machine Learning components have shown remarkable performance in several perception and control tasks like NVIDIA’s DAVE-II self-driving car. However, incidents like TESLA’s self-driving accident and UBER’s autonomous car crash have shown these components to be susceptible to Out-of-distribution (OOD) data. Besides, the black-box nature of these components makes it difficult to test and verify them. To address this, we have used a generative model called B-Variational Autoencoder (B-VAE) to detect the OOD data and identify the factor responsible for the OOD data problem. For example, if an autonomous vehicle is trained on images from day scenes, but if it encounters images from evening scenes, then the vehicle's performance on these images will be erroneous. For the vehicle's safety, it is required to detect that the operating scene has changed from that of training and the time-of-day factor is responsible for the problem. [Recommended Reading](https://arxiv.org/abs/2108.11800)

# Demonstration

{{< youtube id="CK8ghywFI_Q" title="Out-of-Distribution Detection using B-VAE detector" >}}

The precipitation increases to a high value at t = 13 seconds in the video. Images of high rain were not included in training the Machine Learning controller driving the AV. So, we used the B-VAE detector to identify OOD images in CARLA simulation. As the precipitation value increases, the detector martingale and the martingale of the precipitation reasoner increases (Martingale used for performing time-series detection. You can find out more from the recommended reading material) You can find more videos and the implementation from our [GitHub](https://github.com/scope-lab-vu/Beta-VAE-OOD-Detector).
