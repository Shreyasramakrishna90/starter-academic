---
title:  Dynamic Risk Assessment for Autonomous Systems
summary: Proactive risk assessment is required for runtime safety assessment of autonomous systems. It needs to utilize the detection results from the anomaly detectors to estimate the risk of the system
#tags:
#- current


# Optional external URL for project (replaces project detail page).
#external_link: ""

image:
  caption: Resonate Risk Assessment Framework
  #focal_point: Smart


# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

Design-time system risk assessment based on hazard analysis information has been a core activity of System risk management. This is popularly reffered to as the pre-determined risk assessment and widely used in the aviation domain. Despite its importance, pre-determined risk assessment only uses design-time system and operating environment information to estimate the risk, which is not sufficient for cyber-physical systems that operate in uncertain environments. To address this problem, we introduce the Runtime Safety Evaluation in Autonomous Systems (ReSonAte) framework for quantitative assessment of a system's dynamic risk at runtime. ReSonAte uses the hazard information from design-time Bow-Tie Diagrams along with the information about the system's current state (e.g. from anomaly detectors, assurance monitors, etc.) and the operating environment (e.g., weather, traffic, etc.) to estimate current hazard rates. These hazard rates are then used to determine the likelihood of system-level consequences described in the Bow-Tie Diagram. [Recommended Reading](https://arxiv.org/abs/2102.09419)


# Demonstration

{{< youtube id="umwnMnq2ggc" title="ReSonAte estimating the AVs risk in CARLA simulation" >}}

A demonstration of the ReSonAte framework estimating the AVs risk in CARLA simulation. Resonate estimated collision rate as the Autonomous Vehicle navigated through a nominal CARLA scene with weather(cloud = 0.0, precipitation = 0.0, deposits = 0.0). The scene gets adverse with high brightness. The [B-VAE assurance monitor](https://arxiv.org/abs/2108.11800) detects the increase in brightness and its martingale increases. The Blur detectors and Occlusion detector (on left) remain low throughout. The Likelihood of a collision increases with the adverse brightness, and as expected the AV goes very close to the other vehicle stopped in front. You can learn more about the platform from our [[GitHub]](https://github.com/scope-lab-vu/Resonate)  
