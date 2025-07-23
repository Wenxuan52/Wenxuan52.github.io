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
  Key Courses: Computational Mathematics (A*), Machine Learning (A*), Fluid Dynamics (A*), Deep Learning (A)

* **BSc Mathematics and Applied Mathematics**, Taiyuan University of Technology (2020-2024)  
  School of Mathematics | GPA: 92/100  
  Key Courses: Mathematical Analysis (97), Advanced Algebra (98), Numerical Analysis (94)  
  Awards: Academic Outstanding Individual (2020-2024)

Research Experience
======

**MSc Independent Research Project** | Jun 2025 - Present  
*Imperial College London*  
- **Project**: Comparative Benchmarking of Reduced-Order Models for Data Assimilation Applications
- Leading comprehensive benchmarking study of CAE-based reduced-order models (CAE+DMD, CAE+LinearMLP, CAE+WeakLinearMLP)
- Evaluating model performance across computational fluid dynamics datasets, turbulent flow systems, and multi-physics atmospheric datasets
- Developing standardized evaluation frameworks for reconstruction accuracy and assimilation quality
- **Supervisor**: Prof. Sibo Cheng

**Research Project Leader** | Dec 2023 - Dec 2024  
*Deep Learning-Based Simulation of Dispersion Shock Waves in Nonlinear PDE Systems*  
- **Output**: Physical Review E (2024)
- Led full-cycle research development: data preprocessing, model design, numerical experiments, and manuscript preparation
- Developed novel DPINN and DRKT modules based on PINN framework and Runge-Kutta methods
- Integrated modules into PgMSNN model using multi-stage training strategy for dispersion shock wave phenomena
- **Supervisor**: Prof. Rui Guo

**Conference Research Leader** | Aug 2023  
*The 32nd International Joint Conference on Artificial Intelligence (IJCAI)*  
- **Output**: IJCAI Conference Paper, Oral Presentation at MiGA Workshop
- Presented MSTCN-VAE model: unsupervised approach for micro-gesture classification using skeletal data
- Led research team through model development, optimization, and conference presentation

**Research Assistant** | Jul 2022 - Apr 2023  
*Physics-Informed Neural Networks for Nonlinear PDEs*  
- **Output**: Optik (2023)
- Implemented PINN method for simulating wave solutions (solitons, breathers) of Modified Schrödinger equation
- Developed PINN implementations in both TensorFlow and PyTorch frameworks
- Built physics-informed neural network architecture for complex number output processing

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