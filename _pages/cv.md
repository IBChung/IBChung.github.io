---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
[My most recent academic cv is here](/files/IB_Chung_UIUC_Curriculum_Vitae.pdf)

Education
======
* Ph.D in Industrial Engineering, University of Illinois Urbana-Champaign, 2026 (expected)
* M.S. in Mechanical Engineering, Hanyang University, 2018
* B.S. in Mechanical Engineering, Hanyang University, 2016

Work experience
======
* Feb 2018 - Jun 2022: Research Engineer
  * PIDOTECH R&D Center [(Website)](https://www.pidotech.com/eng/)
  * Research and development of various technologies for multidisciplinary design optimization
  * Duties includes: Investigation and implementation of methods for data-driven design, design optimization, surrogate modeling, and machine-learning

Skills
======
* Design Optimizaiton
  * Adaptive sampling & surrogate modeling
  * Derivative-free/metaheuristic optimization
  * Linear programming and stochastic programming
* Machine Learning
  * Graph neural networks using graph convolution
  * Generative modeling
* Coding
  * Python
  * MATLAB

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% if post.category == "manuscripts" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>
  

Teaching
======
* Spring 2025: Engineering Graphs & Design (SE 101)
* Fall 2024: Components Design (SE 410)
* Fall 2023: Decision Analysis (SE 450)
  
Service and leadership
======
* Served as a reviewer for conferences: IDETC2025, IMECE2024, IDETC2024
