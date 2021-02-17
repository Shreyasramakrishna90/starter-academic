---
title: "Augmenting Learning Components for Safety in Resource Constrained Autonomous Robots"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Shreyas Ramakrishna
- Abhishek Dubey
- Matthew P Burruss
- Charles Hartsell
- Nagabhushan Mahadevan
- Saideep Nannapaneni
- Aron Laszka
- Gabor Karsai

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2013-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE 22nd International Symposium on Real-Time Distributed Computing*
publication_short: In *ISORC*

abstract: Learning enabled components (LECs) trained using data-driven algorithms are increasingly being used in autonomous robots commonly found in factories, hospitals, and educational laboratories. However, these LECs do not provide any safety guarantees, and testing them is challenging. In this paper, we introduce a framework that performs weighted simplex strategy based supervised safety control, resource management and confidence estimation of autonomous robots. Specifically, we describe two weighted simplex strategies: (a) simple weighted simplex strategy (SW-Simplex) that computes a weighted controller output by comparing the decisions between a safety supervisor and an LEC, and (b) a context-sensitive weighted simplex strategy (CSW-Simplex) that computes a context-aware
weighted controller output. We use reinforcement learning to learn the contextual weights. We also introduce a system monitor that uses the current state information and a Bayesian network model learned from past data to estimate the probability of the robotic system staying in the safe working region. To aid resource constrained robots in performing complex computations of these weighted simplex strategies, we describe a resource manager that offloads tasks to an available fog nodes. The paper also describes a hardware testbed called DeepNNCar, which is a low cost resource-constrained RC car, built to perform autonomous
driving. Using the hardware, we show that both SW-Simplex and CSW-Simplex have 40% and 60% fewer safety violations, while demonstrating higher optimized speed during indoor driving (∼ 0.40 m/s) than the original system (using only LECs)

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.researchgate.net/profile/Abhishek_Dubey7/publication/332289747_Augmenting_Learning_Components_for_Safety_in_Resource_Constrained_Autonomous_Robots/links/5cac166c4585157bd32d288f/Augmenting-Learning-Components-for-Safety-in-Resource-Constrained-Autonomous-Robots.pdf'
url_code: 'https://github.com/scope-lab-vu/deep-nn-car'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- Assured 

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
