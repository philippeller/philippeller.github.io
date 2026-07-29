---
layout: page
title: Newtrinos.jl
description: A Julia package for global neutrino oscillation data analysis
img: assets/img/newtrinos_example.png
importance: 1
category: work
github: https://github.com/philippeller/Newtrinos.jl
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/newtrinos_example.png" title="Newtrinos.jl example" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Example output from the Newtrinos.jl quick-start guide.
</div>

Newtrinos.jl is an open-source Julia package for combining experimental neutrino data with physics models and inference tools in a flexible, modular way. It is organized into three layers:

* **Experimental likelihoods** — modules for individual experiments and datasets (e.g. IceCube DeepCore, Daya Bay).
* **Physics modules** — functions computing oscillation probabilities, atmospheric fluxes, and other theoretical predictions, including beyond-Standard-Model scenarios.
* **Analysis tools** — interfaces for running inference, both Frequentist and Bayesian.

Built on Julia's automatic differentiation, Newtrinos.jl supports full systematic-uncertainty treatment, joint likelihood construction across multiple experiments, and parallelized fits. It is the analysis framework underlying the [BSM physics project](/projects/bsm/), and has already been used in published results on the number of neutrino species and on non-unitary neutrino mixing.

## Further Information

GitHub repository: <https://github.com/philippeller/Newtrinos.jl>
