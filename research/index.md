---
title: Research
nav:
  order: 1
  tooltip: Learn about our research
---

# {% include icon.html icon="fa-solid fa-flask-vial" %}Our research

Neurone Lab investigates intelligence as a problem of **structure, dynamics, and information flow**. We move in both directions between biology and computation: biological organization inspires new learning architectures, while machine learning helps us interpret cells, tissues, brains, and complex signals. This common perspective connects our four main research themes.

{% include section.html %}

## NeuroAI and efficient recurrent learning

We ask which principles of nervous systems can make artificial networks more efficient, adaptive, and interpretable. Our work includes architectures constrained by the _Caenorhabditis elegans_ connectome, biologically motivated sparsity, conditional computation, and reservoir computing. Rather than treating network connectivity as an arbitrary implementation detail, we study how topology and temporal dynamics shape memory, representation, and learning.

Reservoir computing is especially useful in this setting: a recurrent dynamical system transforms an input history into a rich state while only a lightweight readout needs to be trained. We investigate how known dynamics can inform the reservoir, how self-supervised objectives can improve its representations, and how selective state updates can reduce computation without discarding informative events.

{%
  include figure.html
  image="images/Research_all-02.png"
  caption="From biological connectivity and dynamics to efficient artificial learning systems."
  width="75%"
%}

## Single-cell and systems biology

Single-cell RNA sequencing reveals cellular heterogeneity, but its thousands of correlated measurements do not directly explain the programs that govern a cell. We develop latent-variable and integrative methods that organize gene regulation, pathways, and metabolism into interpretable factors. These methods can connect cell states to coordinated biological programs, compare those programs across populations, and generate hypotheses for experimental validation.

This work builds on the lab's broader experience in gene-expression analysis, multi-omic integration, pathway inference, consensus clustering, and metabolic networks. Our aim is not only to predict a label, but to expose the molecular organization behind it.

## AI for biomedical imaging

We develop learning methods for images in which reliable annotations are scarce and the acquisition process matters. Applications include label-free classification of cells from digital holograms, holographic flow cytometry, Fourier ptychographic microscopy, microscopy denoising, and clinical neuroimaging. By combining acquisition-aware models, robust evaluation, and explainable architectures, we seek systems that are useful to both computational researchers and domain experts.

Our recent work joins this theme to NeuroAI through connectome-inspired models for label-free cell classification, testing whether constrained biological topology can provide competitive predictions together with more transparent internal structure.

{%
  include figure.html
  image="images/Research_all-01.png"
  caption="Computational methods reveal patterns in single cells, molecular programs, and biomedical images."
  width="75%"
%}

## Time series, audio, and representation learning

Sequential data provide a natural testbed for models of memory and efficient computation. We study representation learning and feature extraction for time series, environmental soundscapes, real-world audio, source separation, and speech enhancement. These applications also let us test general ideas—such as compression, selective updates, and self-supervision—under noise and changing temporal context.

{% include section.html %}

## One lab, shared questions

Across these areas, we repeatedly ask: **what should a model remember, which structure should it preserve, and how can its representation remain scientifically meaningful?** We approach those questions through new architectures, curated datasets, reproducible analysis pipelines, and collaboration with biological and clinical researchers.

{%
  include button.html
  link="projects"
  text="Explore our current projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{%
  include button.html
  link="publications"
  text="Browse our publications"
  icon="fa-solid fa-book"
  style="bare"
%}
