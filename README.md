<h1 align="center">Pratik Dahal</h1>

<p align="center">
  <b>Statistics PhD Candidate • Data Scientist • Statistical Machine Learning</b>
</p>

<p align="center">
  Bayesian Modeling • Biostatistics • Survival Analysis • Experimentation • Applied ML • Python & SQL
</p>

<p align="center">
  I build statistically rigorous models and experiments, then turn them into systems that can be evaluated and used.
</p>

<p align="center">
  <a href="mailto:mapratikdahal@gmail.com">
    <img src="https://www.svgrepo.com/show/223047/gmail.svg" height="30" width="40"/>
  </a>
  <a href="https://github.com/dahlp94">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/github.svg" height="30" width="40"/>
  </a>
  <a href="https://www.linkedin.com/in/pratik-dahal-0363b671/">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" height="30" width="40"/>
  </a>
  <a href="https://dahlp94.github.io">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/chrome/chrome-original.svg" height="30" width="40"/>
  </a>
</p>

## About Me

I am a PhD candidate in Statistics focused on applied data science and statistical machine learning.

My work combines **Bayesian modeling, experimentation, uncertainty quantification, and applied ML** with the engineering needed to make analyses reproducible and usable.

I work primarily in **Python and SQL**, and I enjoy turning ambiguous problems into clear statistical questions, evaluating competing approaches carefully, and building practical tools around the results.

**Target roles:** Data Scientist • Applied Data Scientist • Statistical Data Scientist • Applied Scientist


## Technical Stack

**Programming & Data**  
Python • SQL • PostgreSQL • pandas • NumPy • SciPy

**Statistics & Machine Learning**  
PyMC • scikit-learn • PyTorch • Bayesian inference • MCMC • Variational inference • Experimentation • Bootstrap methods

**Applied ML Systems**  
FastAPI • MLflow • Streamlit • Git • pytest

**Research Areas**  
Bayesian computation • Spatial statistics • Graph-structured models • Uncertainty quantification


## Featured Work

### BayesWatch — Probabilistic Overdose Modeling Platform

End-to-end statistical modeling system for Arkansas county overdose mortality using CDC WONDER data.

- Developed a **suppression-aware Negative Binomial likelihood** that incorporates interval-censored death counts instead of dropping or midpoint-imputing them
- Modeled all **75 Arkansas counties across 525 county-year records**, including **362 suppressed observations**
- Compared pooled and hierarchical Bayesian models using a strict **2018–2023 training / 2024 temporal holdout**
- Tracked experiments and model lineage with **MLflow**, published selected predictions to PostgreSQL, and served results through **FastAPI and Streamlit**
- Added a grounded AI explanation layer that uses structured API results rather than generating model predictions

**Tech:** Python · PyMC · PostgreSQL · SQL · MLflow · FastAPI · Streamlit

[View repository](https://github.com/dahlp94/bayeswatch)


### Retail Media Incrementality Platform

Experimentation and commercial analytics platform for measuring whether advertising creates incremental business outcomes rather than relying only on attribution.

- Built randomized **treatment/control experiments** with approximately 80/20 assignment
- Estimated **conversion lift, incremental orders, and incremental revenue** alongside attributed metrics such as ROAS
- Added analytic confidence intervals for conversion lift and **member-level bootstrap uncertainty** for order and revenue effects
- Built reusable **SQL analytical marts** and translated experimental results into campaign-level budget recommendations

**Tech:** Python · SQL · PostgreSQL · Experimentation · Bootstrap

[View repository](https://github.com/dahlp94/retail-media-platform)


### SDM-CAR — Bayesian Spatial Modeling Research

Research project on flexible spatial dependence for Conditional Autoregressive models.

- Developed **graph-spectral extensions of CAR models** to relax fixed spatial dependence assumptions
- Implemented **collapsed variational inference and MCMC** under a common model formulation
- Evaluated recovery, misspecification, and prediction under block-missing spatial observations
- Focused on interpretable Bayesian modeling and uncertainty for structured spatial data

**Tech:** Python · Bayesian Statistics · CAR Models · Variational Inference · MCMC

[View repository](https://github.com/dahlp94/sdm-car)


### Vectra — Semantic Retrieval & Grounded Question Answering

A retrieval system for searching internal text and markdown documents by meaning and generating answers grounded in retrieved evidence.

- Built document ingestion, chunking, embedding, and storage using **PostgreSQL + pgvector**
- Implemented metadata-filtered semantic similarity search
- Built a **FastAPI** service that returns grounded answers with citations and retrieved chunk snippets
- Designed fallback behavior for weak retrieval rather than forcing unsupported answers

**Tech:** Python · FastAPI · PostgreSQL · pgvector

[View repository](https://github.com/dahlp94/vectra)


## Current Focus

- Bayesian and probabilistic modeling for real-world data problems
- Experimentation, incrementality, and uncertainty quantification
- Scalable variational inference for structured statistical models
- Spatial and graph-based statistical modeling
- Building reproducible workflows that connect analysis, evaluation, and usable software


## Contribution Graph

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dahlp94/dahlp94/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dahlp94/dahlp94/output/github-contribution-grid-snake.svg" />
    <img alt="GitHub contribution graph" src="https://raw.githubusercontent.com/dahlp94/dahlp94/output/github-contribution-grid-snake.svg" />
  </picture>
</div>


## Connect

- 🌐 [Portfolio](https://dahlp94.github.io)
- 💼 [LinkedIn](https://www.linkedin.com/in/pratik-dahal-0363b671/)
- 💻 [GitHub](https://github.com/dahlp94)
- 📧 [Email](mailto:mapratikdahal@gmail.com)
