---
title:  Assuring Cyber-Physical Systems with Learning Enabled Components 
summary: Tremendous advances have been made in the area of autonomous cyber-physical systems (CPSs) in the last decades, through self driving cars, unmanned robots, unmanned aerial vehicles, etc. Despite its wide spread use, there are still challenges in designing fully autonomous systems, as guaranteeing the safety of such systems is challenging. My research work is mainly focuses on developing research methods and tools for system level safety assurance for learning-enabled cyber-physical systems. To achieve this I've worked on three different technical areas which are listed in the figure and described below. 


# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

#### 1. System Risk Management
System Risk Management (SRM) has become critical in regulatory accaptance in domains such as aviation. SRM includes two components (1) safety assurance case and (2) risk assessment.

* **Automating Assurance Case Generation** - As assurance cases have become an integral component for safety-certification in various CPS domains, including automotive, aviation, military, and medical devices. Despite the strict requirements, current practices still rely on manual methods that are brittle, do not have a systematic approach or thorough consideration of sound arguments. In addition, stringent certification requirements and ever-increasing system complexity make ad-hoc, manual assurance case generation inefficient, time consuming, and expensive. In this area, we improve the current state of practice by introducing a structured *assurance case generation (ACG)* method which uses system design artifacts, accumulated evidence, and developer expertise to construct an assurance case and evaluate it in an automated manner. Besides, we also focus on designing a tool called ALC to automate the entire design and testing of learning-enabled CPSs. [[paper]](https://arxiv.org/pdf/2003.05388.pdf)
 
* **Runtime Risk Assessment** - Design-time system risk assessment based on hazard analysis information has been a core activity of SRM. This is popularly reffered to as the pre-determined risk assessment and widly used in the aviation domain. Despite its importance, pre-determined risk assessment only uses design-time system and operating environment information to estimate the risk, which is not sufficient for cyber-physical systems that operate in uncertain environments. To address this problem, we introduce the Runtime Safety Evaluation in Autonomous Systems (ReSonAte) framework for quantitative assessment of a system's dynamic risk at runtime. ReSonAte uses the hazard information from design-time Bow-Tie Diagrams along with the information about the system's current state (e.g. from anomaly detectors, assurance monitors, etc.) and the operating environment (e.g., weather, traffic, etc.) to estimate current hazard rates. These hazard rates are then used to determine the likelihood of system-level consequences described in the Bow-Tie Diagram. 

#### 2. Out-of-Distribution detectors for Learning Enabled Components (LECs)
Learning Enabled Components (LECs) have shown remarkable performance in several perception and control tasks like NVIDIA’s DAVE-II self driving car. However, incidents like TESLA’s self-driving accident and UBER’s autonomous car crash have shown the susceptibility of LECs to Out-of-distribution (OOD) data. Besides the black box nature of the LECs makes it difficult to test and verify them. In this area, we have been working on designing a generative model based Out-of-Distribution method. Specifically, we have been working on designing B-Variational Autoencoders (B-VAE) for detecting the OOD data and isolating the problem causing it. [[paper1]](https://arxiv.org/pdf/2003.08740.pdf) [[paper2]](https://ieeexplore.ieee.org/document/9244027)


#### 3. Runtime contingency Management for Learning-enabled Cyber-Physical Systems
CPSs have increasingly started using LECs for performing perception-based control tasks. The simple design approach, and their capability to continuously learn has led to their widespread use in different autonomous applications. Despite their simplicity and impressive capabilities, these models are difficult to assure, which makes their use challenging. The problem of assuring CPS with untrusted controllers has been achieved using the Simplex Architecture. This architecture integrates the system to be assured with a safe controller and provides a decision logic to switch between the decisions of these controllers. However, designing Simplex Architectures for Learning-enabled CPSs is complex, because of the LECs black-box nature. To address this, i've proposed the dynamic-weighted simplex strategy that uses reinforcement-learning as the decision logic. [[paper1]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8759270&casa_token=sY0FaPfy_jAAAAAA:UkwiJv9Z2ngJAzMy67_g5Ud64AQmhyWKMcnF65XudWqom5PdqKIM8AyZ4v89e-O2-hXijTM&tag=1) [[github]](https://github.com/scope-lab-vu/deep-nn-car) [[paper2]](https://www.sciencedirect.com/science/article/pii/S1383762120300540?casa_token=9jbLN0Eoi3QAAAAA:cBu7fJSS-BDZiiuKn8dnOxkCfcQDqmROKQ4l4C32_sYjSqlHop5YzMd2euF0cTYIqRCVEuM)

