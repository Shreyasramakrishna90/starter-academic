---
title: Out-of-Distribution detectors for Learning Enabled Components (LECs)
summary: Though LECs have shown remarkable performance for challanging tasks such as autonomous driving ([NVIDIA DAVE-II](https://www.youtube.com/watch?v=NJU9ULQUwng&ab_channel=IProgrammerTV)), they have shown to be susceptible to slight shifts in the operating contexts, popularly known as out-of-distribution (OOD) data. 

tags:
- current


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

Learning Enabled Components (LECs) have shown remarkable performance in several perception and control tasks like NVIDIA’s DAVE-II self driving car. However, incidents like TESLA’s self-driving accident and UBER’s autonomous car crash have shown the susceptibility of LECs to Out-of-distribution (OOD) data. Besides the black box nature of the LECs makes it difficult to test and verify them. In this area, we have been working on designing a generative model based Out-of-Distribution method. Specifically, we have been working on designing B-Variational Autoencoders (B-VAE) for detecting the OOD data and isolating the problem causing it. [[paper1]](https://arxiv.org/pdf/2003.08740.pdf) [[paper2]](https://ieeexplore.ieee.org/document/9244027)


