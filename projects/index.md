---
title: Projects
nav:
  order: 2
  tooltip: Explore our current projects
---

# {% include icon.html icon="fa-solid fa-diagram-project" %}Projects

Our projects turn the lab's broader research questions into concrete, collaborative directions. They are deliberately open-ended: each can support theses, methodological studies, benchmarks, and partnerships across machine learning and the life sciences.

{% include section.html %}

## Self-supervised representations for reservoir computing

**Goal.** Bring modern self-supervised representation learning to reservoir computing while retaining its fast, lightweight training.

Reservoirs create temporal representations through fixed or only partially trained recurrent dynamics, but their states are not usually optimized to make different views of the same signal agree. We will adapt objectives from **JEPA**, **BYOL**, and **contrastive learning** to sequential reservoir states. Possible views include masked time windows, augmentations of the same signal, future-state prediction, and multiple sensor channels.

The project will study which objectives work without negative samples, how teacher–student updates interact with fixed dynamics, and whether dynamics-informed reservoirs provide better inductive biases. Evaluation will cover representation quality, label efficiency, robustness, memory capacity, and compute cost on time-series and audio benchmarks.

**Questions we are exploring**

- Can a reservoir learn transferable features from unlabelled sequences while keeping most recurrent weights fixed?
- Which temporal augmentations preserve the semantics of a dynamical system?
- Can physical or mechanistic knowledge shape a reservoir before self-supervised training begins?

{% include section.html %}

## Surprise-gated recurrent networks

**Goal.** Update a recurrent state only where new evidence is genuinely informative—not merely where an input has changed.

[Delta networks](https://proceedings.mlr.press/v70/neil17a.html) reduce recurrent computation by allowing selected channels to update when the change from the previous step crosses a threshold. This is efficient, but a small or repeated input can still be informative when it is unexpected under the model's current belief. We propose replacing a purely magnitude-based gate with a measure of [**Bayesian surprise**](https://doi.org/10.1162/neco.2009.05-08-785): the change between prior and posterior beliefs induced by the new evidence.

The first stage will define differentiable, stable surprise estimators for channel-wise hidden-state updates and compare them with standard delta thresholds. The second will scale the idea to token-level routing: only tokens with sufficiently high surprise contribute to a state update. We will then explore the same principle in modern scalable recurrent architectures, measuring the trade-off between predictive quality, sparsity, latency, and energy use.

**Questions we are exploring**

- When does Bayesian surprise retain useful stationary inputs that a delta rule would skip?
- Should surprise be estimated per channel, per token, or hierarchically at both levels?
- Can a model calibrate its update budget dynamically while remaining stable on long sequences?

{% include section.html %}

## CellProgram Atlas: interpretable regulatory–metabolic factors

**Goal.** Extend the framework introduced in *A latent factor framework to organize regulatory and metabolic programs inferred from scRNA-seq* into a reusable atlas of coordinated cell programs.

Single-cell expression profiles can separately support the inference of regulatory activity and metabolic state. This project studies how a shared latent-factor representation can organize those signals into compact, interpretable programs, helping researchers compare cell populations and trace the biological processes associated with each state.

Building from the paper, future work can test the framework on larger and more diverse cohorts, integrate additional omic and spatial measurements, and follow regulatory–metabolic programs across time, perturbations, disease progression, or treatment. Other directions include uncertainty-aware factors, improved scalability, cross-dataset alignment, links to clinical phenotypes, and experimental validation of the most relevant inferred programs.

**Questions we are exploring**

- Which regulatory and metabolic programs are conserved across tissues, patients, and conditions?
- Can spatial, proteomic, or perturbation data distinguish association from functional coupling?
- How can factor uncertainty and biological prior knowledge make the resulting atlas more reliable?

{%
  include button.html
  link="https://doi.org/10.1093/bioadv/vbag185"
  text="Read the CellProgram Atlas foundation paper"
  icon="fa-solid fa-arrow-up-right-from-square"
  style="bare"
%}

{% include section.html %}

Interested in contributing a thesis, dataset, or complementary perspective? [Get in touch with us](/contact).
