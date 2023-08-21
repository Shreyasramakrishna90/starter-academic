---
# Display name
title: Shreyas Ramakrishna

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: Senior Architect, System Safety Engineer

# Organizations/Affiliations to show in About widget
organizations:
- name: NVIDIA
  url: https://www.nvidia.com/en-us/


# Education to show in About widget
education:
  courses:
  - course: PhD in Electrical Engineering
    institution: Vanderbilt University, USA
    year: 2022
  - course: Masters in Electrical Engineering and Computer Science
    institution: Technical Univerity Kaiserslautern, Germany
    year: 2015
  - course: Bachelors in Electronics and Communication Engineering
    institution: Visvesvaraya Technological University, India
    year: 2012

 # Professional Experience to show in About widget
interests:
  - Cyber-Physical Systems
  - Autonomous Vehicles
  - Machine Learning
  - Safety Engineering


  #header:
  #  image: "media/av.jpeg"

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "/#contact" for contact widget.
social:
- icon: envelope
  icon_pack: fas
  link: mailto:shreyasramakrishna90@gmail.com
- icon: google-scholar  #icon from `ai` icon pack graduation-cap  # Alternatively, use `
  icon_pack: ai
  link: https://scholar.google.com/citations?user=M6Yu9GEAAAAJ&hl=en&oi=ao
- icon: linkedin
  icon_pack: fab
  link: https://www.linkedin.com/in/shreyasramakrishna/
- icon: github
  icon_pack: fab
  link: https://github.com/Shreyasramakrishna90

# Link to a PDF of your resume/CV.
# To use: copy your resume to `static/media/resume.pdf`, enable `ai` icons in `params.toml`,
# and uncomment the lines below.
#- icon: cv
#  icon_pack: ai
#  link: media/New_Job_Resume.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: "shreyasramakrishna90@gmail.com"

# Highlight the author in author lists? (true/false)
highlight_name: true
---
<div style="text-align: justify">

I am Shreyas Ramakrishna, a senior safety architect at <a href="https://www.nvidia.com/en-us/">NVIDIA Corporation</a>. My work involves applying functional safety analysis as per the ISO 26262 safety standard for assuring the safety of the automotive hardware and software developed by NVIDIA. I received my Ph.D. in electrical engineering from <a href="https://www.vanderbilt.edu/">Vanderbilt University</a>, where I was advised by Professor <a href="https://abhishekdubey.bio/">Abhishek Dubey</a>, and I worked at <a href="https://scopelab.ai/index.html">SCOPE Lab</a>, which is located in  <a href="https://www.isis.vanderbilt.edu/">Institute for Software Integrated Systems</a>. My research focused on developing dynamic safety assurance techniques for autonomous cyber-physical systems. I designed a safety assurance framework that combines runtime recovery procedures along with machine learning-based assurance monitors (e.g., Out-of-Distribution detector, risk assessors) and design-time safety assurance case to assure the safety of an autonomous system during operation.

I've published over 15 articles and abstracts in renowned international journals like ACM Transactions on Cyber-physical systems, Elsevier's Journal of system architecture and conferences like ICCPS, SEAMS, EMSOFT, Safecomp, ITSC, and DESTION. I am also serving as a reviewer for journals published in Elsevier, SAE International, PHM Society, and Springer.
</div>



<!-- Before joining Vanderbilt University, I had a masters in electrical engineering with a specialization in <a href="https://www.eit.uni-kl.de/en/topics/embedded-systems">embedded systems</a> from <a href="https://www.uni-kl.de/en/startseite">Technical University Kaiserslautern</a>, Germany and a Bachelors in electronics and communication engineering from <a href="https://vtu.ac.in/">Visvesvaraya Technological University</a>, India. In the past, I've interned with Siemens Corporation, Technology (2021).

My current work at NVIDIA focuses on safety engineering. During my Ph.D., I worked on the <a href="https://www.darpa.mil/program/assured-autonomy">DARPA Assured Autonomy</a> project. My research focused on dynamic safety assurance techniques for autonomous cyber-physical systems. I designed a safety assurance framework that is a combination of traditional static safety assurance techniques (e.g., assurance cases) and machine learning monitors (e.g., anomaly detectors based on generative models) for proactive problem detection, risk assessment, and mitigation of the assessed risk of the system at runtime. I've published papers in prestigious international journals (such as Transactions on Cyber-physical systems, Journal of system architecture) and conferences such as SEAMS, EMSOFT, Safecomp, ITSC, and DESTION. Since June 2022, I've also reviewed manuscripts for well-known journals from Elsevier (such as Journals on Artificial Intelligence, and Reliability) and PHM society.   -->

##PhD Thesis
[Dynamic Safety Assurance of Autonomous Cyber-Physical Systems](https://ir.vanderbilt.edu/handle/1803/17763)
Advisor: <a href="https://abhishekdubey.bio/">Abhishek Dubey</a>
Rest of Thesis Committee: <a href="https://www.isis.vanderbilt.edu/user/46">Janos Sztipanovits</a>, <a href="https://www.isis.vanderbilt.edu/gabor">Gabor Karsai</a>, <a href="https://www.isis.vanderbilt.edu/user/78">Xenofon Koutsoukos</a>, <a href="https://www.linkedin.com/in/arun-ramamurthy-71b03b6a/">Arun Ramamurthy</a>, and <a href="https://ayanmukhopadhyay.github.io/">Ayan Mukhopadhyay</a>

Abstract: Cyber-Physical Systems (CPSs) are ubiquitous through our interactions with applications such as smart homes, medical devices, avionics, and automobiles. However, the ever-increasing complexity, domain interdependence, and dynamic nature of operations have raised safety concerns in using them for safety-critical applications. Typically, safety assurance techniques such as an assurance case are used at design time to design a safety argument supported by evidence intended to demonstrate that the system will satisfy its assurance guarantees. The argument is subject to certain assumptions about the behavior of components and the system's operating environment. However, on deployment, the evolving nature of the system potentially invalidates the design-time assumptions, thereby defeating the safety argument. This problem of safety assurance is exacerbated by using data-driven Learning Enabled Components (e.g., Deep Neural Networks) to design autonomous CPS. Despite having performed well, the closed-world assumptions under which these components are trained often get invalidated when deployed in open-world scenarios (Out-of-Distribution data problem). The invalidation of these design-time assumptions could potentially increase the system's risk of consequence at runtime. Therefore, there is a need to continuously monitor these assumptions at runtime and quantify the risk posed to the system. This is not possible by the existing design-time safety assurance techniques and requires a dynamic safety assurance approach. This research aims to quantify the risk posed to autonomous CPS and select a suitable mitigation strategy for mitigating the risk at runtime. For this, we have designed the dynamic safety assurance framework, which is a synergy of the design-time and runtime assurance approaches. The framework begins with (a) Automated development of an assurance case, which holds the safety arguments for the system and the assumptions under which they are valid. Once these arguments and the assumptions are available, the framework has three components to perform the following activities at runtime. (b) Detect invalidation of the design-time assumptions and identify the factor(s) responsible for the problem. Especially, we are interested in detecting the violations of the closed-world assumption in training the LEC, resulting in the OOD data problem. (c) Assess the system's operational risk at runtime, given the current operating conditions, the known sensor and actuator faults, and the information from the detectors. (d) Mitigate the risk by dynamically selecting a suitable control action for the system. We refer to each of these components as the dynamic assurance components. Finally, we have the data generation component to generate the data required for developing the other components of the framework. We demonstrate the effectiveness of the proposed approach with two different autonomous CPS testbeds. The first platform is a resource-constrained remote-controlled autonomous driving testbed called DeepNNCar. The second platform is an Autonomous Vehicle (AV) case study in the CARLA simulation.





<!--## Impact and Highlights
* **Apr 2023** NVIDIA DRIVE Platform gets safety certification from TUV. [NVIDIA Blog](https://blogs.nvidia.com/blog/2023/04/20/nvidia-drive-safety-milestones/?ncid=so-link-715362-vt03#cid=av16_so-link_en-us)
* **Feb 2023** Our paper "Dynamic Simplex: Balancing Safety and Performance in Autonomous Cyber Physical Systems" is accepted at [ICCPS'23](https://iccps.acm.org/2023/) [[paper]](https://dl.acm.org/doi/abs/10.1145/3576841.3585934)
* **Sep 2022** I will be attending the [GTC](https://www.nvidia.com/gtc/) conference hosted by NVIDIA between Sep 19 - 21
* **Aug 2022** I started working as a Senior Safety Architect at NVIDIA
* **July 2022** I successfully defended my PhD [Defense Presentation](media/Dissertation-Presentation.pdf)
* **June 2022** Our paper "ANTI-CARLA: An Adversarial Testing Framework for Autonomous Vehicles in CARLA" is accepted at [ITSC'22](https://www.ieee-itsc2022.org/#/) [[paper]](https://arxiv.org/abs/2208.06309)-->



<!-- * **Aug 2021** Our Paper "Efficient Out-of-Distribution Detection Using Latent Space of β-VAE for Cyber-Physical Systems" is accepted at [TCPS'21](https://dl.acm.org/journal/tcps/special-issue-ai) [[paper]](https://arxiv.org/abs/2108.11800)

* **May 2021** Our Paper "Deep-RBF Networks for Anomaly Detection in Automotive Cyber-Physical Systems" is accepted at [SMARTCOMP'21](https://www.smart-comp.info/) [[paper]](https://arxiv.org/abs/2103.14172) -->

<!-- * **May 2021** I will be interning at Siemens Corporation, Technology, over the summer. I will be working on the DARPA ARCOS project.
* **Mar 2021** Our Paper "ReSonAte: A Runtime Risk Assessment Framework for Autonomous Systems" is accepted at [SEAMS'21](https://conf.researchr.org/home/seams-2021) [[paper]](https://arxiv.org/abs/2102.09419) -->

{{< icon name="download" pack="fas" >}} Download my {{< staticref "media/Resume.pdf" "newtab" >}}[CV]{{< /staticref >}} [[Research Slides]](media/Shreyas-Research-Portfolio.pdf) [[PHD Thesis]](https://ir.vanderbilt.edu/handle/1803/17763)
