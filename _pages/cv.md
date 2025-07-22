---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download complete CV (PDF)](/files/CV.pdf)

Education
======
* **MSc in Applied Computational Science and Engineering**, Imperial College London, 2024-Present (Current: Distinction)
* **BSc in Mathematics and Applied Mathematics**, Taiyuan University of Technology, 2020-2024 (GPA: 92/100)

Research Experience
======
* **Jun 2025 - Present: MSc Independent Research Project**
  * Imperial College London
  * Topic: Comparative Benchmarking of Reduced-Order Models for Data Assimilation Applications
  * Supervisor: TBD

* **Dec 2023 - Dec 2024: Research Project Leader**
  * Deep Learning-Based Simulation of Dispersion Shock Waves in Nonlinear PDE Systems
  * First Author, Published in Physical Review E
  * Supervisor: Prof. Rui Guo

* **Aug 2023: Conference Presenter**
  * The 32nd International Joint Conference on Artificial Intelligence (IJCAI)
  * Oral presentation at MiGA workshop
  * First Author on MSTCN-VAE model

* **Jul 2022 - Apr 2023: Research Assistant**
  * Solving Nonlinear Partial Differential Equations Based on PINN Method
  * First Author, Published in Optik
  * Developed PINN implementations in TensorFlow and PyTorch

Skills
======
* **Programming & Tools**
  * Python (TensorFlow, PyTorch)
  * MATLAB, C++, Git, LaTeX
* **Scientific Computing**
  * Physics-informed neural networks
  * Koopman operator methods
  * Data assimilation & Operator learning
* **Research & Leadership**
  * Mathematical modeling
  * Large-scale data analysis
  * Team management & Academic writing

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
