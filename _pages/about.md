---
permalink: /
title: "Yanbaihui (Evelyn) Liu"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a Ph.D. candidate in the [General Robotics Lab](http://generalroboticslab.com/) at Duke University, advised by [Dr. Boyuan Chen](http://boyuanchen.com/).

My research focuses on **robot perception and intelligent sensing**, exploring how robots can leverage diverse and unconventional sensory signals to perceive aspects of the physical world that are difficult to observe through conventional sensing alone. I develop sensing and learning systems that transform these signals into actionable representations for robotic decision-making, while exploring how robots can adapt what, when, and how they sense based on their task and environment.

Before joining Duke, I earned an M.S. in Electrical Engineering and Computer Science from the University of Michigan, where I worked with [Dr. Maani Ghaffari](https://robotics.umich.edu/people/faculty/maani-ghaffari/) in [CURLY Lab](https://curly.engin.umich.edu/). I also hold a B.S. in Electrical and Computer Engineering from the Georgia Institute of Technology.

<!-- ## News
* **[1/2025]** Our paper [WildFusion](http://www.generalroboticslab.com/blogs/blog/2024-09-29-wildfusion/index.html) got accepted by ICRA 2025!
* **[8/2023]** Began my PhD journey at Duke University! -->

## Highlights

{% assign post = site.publications | where: "title", "Embodied Passive Aeroacoustic Perception Enables Relative Sensing and Pursuit Between Aerial Robots" | first %}
{% include publication-single.html %}

{% assign post = site.publications | where: "title", "Scensory: Real-Time Robotic Olfactory Perception for Joint Identification and Source Localization" | first %}
{% include publication-single.html %}

{% assign post = site.publications | where: "title", "WildFusion: Multimodal Implicit 3D Reconstructions in the Wild" | first %}
{% include publication-single.html %}

[View all publications]({{ '/publications/' | relative_url }})

## Just for Fun

<div class="robot-projects">

<div class="robot-project-item">
<p>Quadruped with parallel leg mechanism.</p>
<img src="/images/robotStudio.gif" alt="Parallel-driven quadruped" />
</div>

<!-- <div class="robot-project-item">
<p><strong>Robot flower</strong> — Reacts to ambient brightness.</p>
<img src="/images/robotflower.png" alt="Robot flower reacts based on brightness" />
</div> -->

<div class="robot-project-item">
<p>Vertical take-off and landing prototype.</p>
<img src="/images/SpinningVTOL.gif" alt="Spinning VTOL" />
</div>

</div>
