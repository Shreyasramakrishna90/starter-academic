---
title:  Risk Assessment for an AV in Carla simulation
summary: ReSonAte framework used to assess the risk of an AV operating in an urban town setting
tags:
- current


# Optional external URL for project (replaces project detail page).
#external_link: ""

#image:
  #caption: Resonate Risk Assessment Framework
  #focal_point: Smart


# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

<p align="center">
  <img src="media/resonate.gif" align="center"/>
</p>

Resonate estimated collision rate as the Autonomous Vehicle navigated through a nominal CARLA scene with weather(cloud = 0.0, precipitation = 0.0, deposits = 0.0). The scene gets adverse with high brightness. The [B-VAE assurance monitor](https://ieeexplore-ieee-org.proxy.library.vanderbilt.edu/stamp/stamp.jsp?arnumber=9283847) detects the increase in brightness and its martingale increases. The Blur detectors and Occlusion detector (on left) remain low throughout. The Likelihood of a collision increases with the adverse brightness, and as expected the AV goes very close to the other vehicle stopped in front.

Additional videos of other scenes can be found in the [Video Folder](https://github.com/Shreyasramakrishna90/AV-Runtime-Risk/blob/main/videos/)

The slides for this work can be found [here](https://github.com/scope-lab-vu/Resonate/blob/main/seams_slides.pdf) and a presentation video can be found on [YouTube](https://www.youtube.com/watch?v=R25RxhwaH5o&ab_channel=VU-ALC)
