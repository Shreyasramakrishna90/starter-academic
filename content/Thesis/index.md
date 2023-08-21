---
#title:  Risk Assessment for Autonomous Systems
#summary: Proactive risk assessment is required for runtime safety assessment of autonomous systems. It needs to utilize the detection results from the anomaly detectors to estimate the risk of the system

title: [Dynamic Safety Assurance of Autonomous Cyber-Physical Systems](https://ir.vanderbilt.edu/handle/1803/17763)
Advisor: <a href="https://abhishekdubey.bio/">Abhishek Dubey</a>
Rest of Thesis Committee: <a href="https://www.isis.vanderbilt.edu/user/46">Janos Sztipanovits</a>, <a href="https://www.isis.vanderbilt.edu/gabor">Gabor Karsai</a>, <a href="https://www.isis.vanderbilt.edu/user/78">Xenofon Koutsoukos</a>, <a href="https://www.linkedin.com/in/arun-ramamurthy-71b03b6a/">Arun Ramamurthy</a>, and <a href="https://ayanmukhopadhyay.github.io/">Ayan Mukhopadhyay</a>

#tags:
#- current


# Optional external URL for project (replaces project detail page).
#external_link: ""

#image:
#  caption: Resonate Risk Assessment Framework
  #focal_point: Smart


# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
Abstract: Cyber-Physical Systems (CPSs) are ubiquitous through our interactions with applications such as smart homes, medical devices, avionics, and automobiles. However, the ever-increasing complexity, domain interdependence, and dynamic nature of operations have raised safety concerns in using them for safety-critical applications. Typically, safety assurance techniques such as an assurance case are used at design time to design a safety argument supported by evidence intended to demonstrate that the system will satisfy its assurance guarantees. The argument is subject to certain assumptions about the behavior of components and the system's operating environment. However, on deployment, the evolving nature of the system potentially invalidates the design-time assumptions, thereby defeating the safety argument. This problem of safety assurance is exacerbated by using data-driven Learning Enabled Components (e.g., Deep Neural Networks) to design autonomous CPS. Despite having performed well, the closed-world assumptions under which these components are trained often get invalidated when deployed in open-world scenarios (Out-of-Distribution data problem). The invalidation of these design-time assumptions could potentially increase the system's risk of consequence at runtime. Therefore, there is a need to continuously monitor these assumptions at runtime and quantify the risk posed to the system. This is not possible by the existing design-time safety assurance techniques and requires a dynamic safety assurance approach. This research aims to quantify the risk posed to autonomous CPS and select a suitable mitigation strategy for mitigating the risk at runtime. For this, we have designed the dynamic safety assurance framework, which is a synergy of the design-time and runtime assurance approaches. The framework begins with (a) Automated development of an assurance case, which holds the safety arguments for the system and the assumptions under which they are valid. Once these arguments and the assumptions are available, the framework has three components to perform the following activities at runtime. (b) Detect invalidation of the design-time assumptions and identify the factor(s) responsible for the problem. Especially, we are interested in detecting the violations of the closed-world assumption in training the LEC, resulting in the OOD data problem. (c) Assess the system's operational risk at runtime, given the current operating conditions, the known sensor and actuator faults, and the information from the detectors. (d) Mitigate the risk by dynamically selecting a suitable control action for the system. We refer to each of these components as the dynamic assurance components. Finally, we have the data generation component to generate the data required for developing the other components of the framework. We demonstrate the effectiveness of the proposed approach with two different autonomous CPS testbeds. The first platform is a resource-constrained remote-controlled autonomous driving testbed called DeepNNCar. The second platform is an Autonomous Vehicle (AV) case study in the CARLA simulation.

<!--Design-time system risk assessment based on hazard analysis information has been a core activity of System risk management. This is popularly reffered to as the pre-determined risk assessment and widely used in the aviation domain. Despite its importance, pre-determined risk assessment only uses design-time system and operating environment information to estimate the risk, which is not sufficient for cyber-physical systems that operate in uncertain environments. To address this problem, we introduce the Runtime Safety Evaluation in Autonomous Systems (ReSonAte) framework for quantitative assessment of a system's dynamic risk at runtime. ReSonAte uses the hazard information from design-time Bow-Tie Diagrams along with the information about the system's current state (e.g. from anomaly detectors, assurance monitors, etc.) and the operating environment (e.g., weather, traffic, etc.) to estimate current hazard rates. These hazard rates are then used to determine the likelihood of system-level consequences described in the Bow-Tie Diagram. [Recommended Reading](https://arxiv.org/abs/2102.09419)


# Demonstration

{{< youtube id="umwnMnq2ggc" title="ReSonAte estimating the AVs risk in CARLA simulation" >}}


A demonstration of the ReSonAte framework estimating the AVs risk in CARLA simulation. Resonate estimated collision rate as the Autonomous Vehicle navigated through a nominal CARLA scene with weather(cloud = 0.0, precipitation = 0.0, deposits = 0.0). The scene gets adverse with high brightness. The [B-VAE assurance monitor](https://arxiv.org/abs/2108.11800) detects the increase in brightness and its martingale increases. The Blur detectors and Occlusion detector (on the left) remain low throughout. The likelihood of a collision increases with the adverse brightness, and as expected, the AV goes very close to the other vehicle stopped in front. You can learn more about the platform from our [GitHub](https://github.com/scope-lab-vu/Resonate) -->
