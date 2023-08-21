---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: 'PHD Thesis'
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
  view: 3
---

<!-- <p align="center">
  <img src="media/featured.png" align="center"/>
</p> -->
<!-- xfun::embed_file("media/featured.pdf") -->

<div align="justify">

<center><b><font size="+2"> Dynamic Safety Assurance of Autonomous Cyber-Physical Systems</font> </b> </center>

Advisor: <a href="https://abhishekdubey.bio/">Abhishek Dubey</a>
Rest of Thesis Committee: <a href="https://www.isis.vanderbilt.edu/user/46">Janos Sztipanovits</a>, <a href="https://www.isis.vanderbilt.edu/gabor">Gabor Karsai</a>, <a href="https://www.isis.vanderbilt.edu/user/78">Xenofon Koutsoukos</a>, <a href="https://www.linkedin.com/in/arun-ramamurthy-71b03b6a/">Arun Ramamurthy</a>, and <a href="https://ayanmukhopadhyay.github.io/">Ayan Mukhopadhyay</a>

Abstract: Cyber-Physical Systems (CPSs) are ubiquitous through our interactions with applications such as smart homes, medical devices, avionics, and automobiles. However, the ever-increasing complexity, domain interdependence, and dynamic nature of operations have raised safety concerns in using them for safety-critical applications. Typically, safety assurance techniques such as an assurance case are used at design time to design a safety argument supported by evidence intended to demonstrate that the system will satisfy its assurance guarantees. The argument is subject to certain assumptions about the behavior of components and the system's operating environment. However, on deployment, the evolving nature of the system potentially invalidates the design-time assumptions, thereby defeating the safety argument. This problem of safety assurance is exacerbated by using data-driven Learning Enabled Components (e.g., Deep Neural Networks) to design autonomous CPS. Despite having performed well, the closed-world assumptions under which these components are trained often get invalidated when deployed in open-world scenarios (Out-of-Distribution data problem). The invalidation of these design-time assumptions could potentially increase the system's risk of consequence at runtime. Therefore, there is a need to continuously monitor these assumptions at runtime and quantify the risk posed to the system. This is not possible by the existing design-time safety assurance techniques and requires a dynamic safety assurance approach.

For this, the thesis proposes a dynamic safety assurance framework, which is a synergy of the design-time and runtime assurance approaches. The framework begins with (a) Automated development of an assurance case, which holds the safety arguments for the system and the assumptions under which they are valid. Once these arguments and the assumptions are available, the framework has three components to perform the following activities at runtime. (b) Detect invalidation of the design-time assumptions and identify the factor(s) responsible for the problem. Especially, we are interested in detecting the violations of the closed-world assumption in training the LEC, resulting in the OOD data problem. (c) Assess the system's operational risk at runtime, given the current operating conditions, the known sensor and actuator faults, and the information from the detectors. (d) Mitigate the risk by dynamically selecting a suitable control action for the system. Finally, we have the data generation component to generate the data required for developing the other components of the framework. We demonstrate the effectiveness of the proposed approach with two different autonomous CPS testbeds.
</div>

{{< icon name="download" pack="fas" >}} Download my [[PHD Thesis]](https://ir.vanderbilt.edu/handle/1803/17763)



<!-- **Dynamic Safety Assurance of Autonomous Systems**-Tremendous advances have been made in the area of autonomous Cyber-Physical Systems (CPSs) in the last decades, through self-driving cars, unmanned robots, unmanned aerial vehicles, etc. Despite its widespread use, there are still challenges in designing fully autonomous systems, as guaranteeing the safety of such systems is challenging. There have always been design-time techniques like Assurance Case with verification and testing for safety assurance of CPS. However, the evolving operating conditions of these systems and the uncertainties introduced by the machine learning components render the design-time techniques insufficient. So, runtime monitoring is needed to complement the design-time techniques for safety assurance of these systems. The primary goal of my research is to perform runtime safety assurance of autonomous systems. For this, I have been developing a Dynamic Safety Assurance framework, which has the following components as shown in the figure: **Detect** anomalies in the system's components at runtime. Primarily, I am interested in detecting the Out-of-Distribution data used by Machine Learning components for predictions. **Assess** the system's risk at runtime, given the current operating conditions, the known sensor and actuator faults, and the information from the detectors. **Mitigate** the risk by dynamically selecting a suitable control action for the system. This involves adaptive decision-making under uncertainty. These components are not limited to autonomous vehicles but can be applied to other CPS domains, including electrical grids, smart grids, transportation systems, etc. -->
<!--  -->


<!-- However, designing these components is non-trivial because they must operate at runtime on small-scale CPS testbeds like [DeepNNCar](https://github.com/scope-lab-vu/deep-nn-car) and [F1/10 car](https://f1tenth.org/) that have short inference times (50 - 100 milliseconds) and limited onboard computational resources (e.g., Raspberry Pi, NVIDIA Jetson TX2). -->


<!-- [![Screenshot](https://github.com/Shreyasramakrishna90/starter-academic/blob/master/static/media/featured.jpg) -->
