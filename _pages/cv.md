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
* **MSc Applied Computational Science and Engineering**, Imperial College London (2024-Present)  
  Department of Earth Sciences and Engineering | Current Distinction  
  Key Courses: Computational Mathematics (A\*), Machine Learning (A\*), Fluid Dynamics (A\*), Deep Learning (A)

* **BSc Mathematics and Applied Mathematics**, Taiyuan University of Technology (2020-2024)  
  School of Mathematics | GPA: 92/100  
  Key Courses: Mathematical Analysis (97), Advanced Algebra (98), Numerical Analysis (94)  
  Awards: Academic Outstanding Individual (2020-2024)

Research Experience
======

* Comparative Benchmarking of Reduced-Order Models for Data Assimilation Applications

  **MSc Independent Research Project** \| Jun 2025 - Present
  
  - Leading a comprehensive benchmarking study of CAE-based reduced-order models (CAE+DMD, CAE+LinearMLP, CAE+WeakLinearMLP) for data assimilation applications across diverse physical systems.
  
  - Evaluating model performance and data assimilation effectiveness on computational fluid dynamics datasets (cylinder flow), turbulent flow systems (Kolmogorov flow), and real-world multi-physics atmospheric datasets.
  
  - Developing standardized evaluation frameworks to assess both reconstruction accuracy and assimilation quality of operator learning approaches in reduced-order modeling contexts.

* Deep Learning-Based Simulation of Dispersion Shock Waves in Nonlinear PDE Systems

  **Research Project Leader** \| Dec 2023 - Dec 2024  

  **Outputs**: Physical Review E
  
  - Led the full-cycle development of a research project, encompassing data preprocessing, model design, numerical experiments, and thesis writing.
  
  - Developed the DPINN and DRKT modules based on the PINN framework and traditional Runge-Kutta methods, innovatively addressing dispersion shock wave phenomena in the Generalized Gardner equation.
  
  - Integrated the modules into the PgMSNN model using the multi-stage training strategy.

* The 32nd International Joint Conference on Artificial Intelligence (IJCAI)

  **Research Team Leader** | Aug 2023  

  **Outputs**: IJCAI conference
  
  - Attend the IJCAI conference and oral presentation at MiGA workshop.
  
  - Presented the technical report of the MSTCN-VAE model, an unsupervised model based on skeletal data to effectively solve the micro-gesture classification problem.

* Solving Nonlinear Partial Differential Equations Based on PINN Method

  **Research Project Leader** | Jul 2022 - Apr 2023  

  **Outputs**: Optik
  
  - Using the PINN method to simulate the wave solutions (solitons, breathers) of Modified Schrodinger equation.
  
  - Reproduce the PINN method in the Tensorflow and Pytorch.
  
  - Build a Physical-Informed Neural Network to process the complex number output.

Competitions & Awards
======

**FEMA Predicting the Unpredictable Challenge** | Feb 2025  
*Team Captain | Rank 1*  
- Developed machine learning models for real-time lightning storm evolution prediction and location forecasting

**MiGA-IJCAI Challenge (Track1 Microgesture Classification)** | Apr-Jun 2023  
*Team Captain | Rank 12*  
- Led team development and optimization of unsupervised model for micro-gesture classification

**China Undergraduate Mathematical Contest in Modeling** | Sep 2023  
*Team Captain | National Second Prize*  
- Developed mathematical model for solar field optimization and energy efficiency calculation

**ASC Student Supercomputer Challenge** | Nov 2021 - Mar 2022  
*Team Member | Global Second Class*  
- Deployed Yuan1.0 model in HPC cluster for training and hyperparameter tuning

Technical Skills
======

**Programming Languages & Frameworks**
- Python (TensorFlow, PyTorch)
- MATLAB, C++ (parallel computing)
- Git, LaTeX

**Scientific Computing & Machine Learning**
- Physics-informed neural networks (PINNs)
- Koopman operator methods
- Data assimilation techniques
- Reduced-order modeling

**Research & Professional Skills**
- Mathematical modeling and analysis
- Experimental design and optimization
- Team leadership and project management
- Conference presentations

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks & Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
