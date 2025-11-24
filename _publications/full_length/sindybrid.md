---
title: "SINDybrid: automatic generation of hybrid models for dynamic systems"
collection: Journal Papers
permalink: /publication/sindybrid
pubtype: "journal"
excerpt: 'In this paper we propose a MILP formulation for the automatic identification and training of hybrid models starting from mechanistic information and data'
date: 2025-11-17
venue: 'Chemical Engineering Science'
paperurl: 'https://doi.org/10.1016/j.ces.2025.122873'
citation: 
---

Hybrid modelling enhances the accuracy and predictive capability of dynamic models by integrating first principles with data-driven methods, effectively mitigating epistemic uncertainties inherent in mechanistic approaches. However, hybrid model construction remains complex, typically requiring expert knowledge to identify model epistemic uncertainty and select suitable machine-learning components to capture it. This complexity limits broader adoption in research and industry. We introduce SINDybrid, an automated algorithm designed to streamline hybrid model development for dynamic systems. SINDybrid employs a mixed-integer linear programming (MILP) approach to systematically identify epistemic uncertainty sources and compensate them using optimally selected data-driven components. For broader accessibility and reproducibility, we provide SINDybrid as an open-source Python library. SINDybrid was validated through three case studies: a catalytic reaction system, a continuous fermentation process, and a Lotka-Volterra oscillator, each showcasing different epistemic uncertainties. The robustness of the algorithm is tested against varying experimental conditions, including measurement noise (up to 20 %), limited training batches (minimum 2), and sparse temporal sampling (minimum 5 samples per experiment). Results demonstrate a consistent ability of the SINDybrid approach to produce accurate hybrid models, achieving R<sup>2</sup> scores above 0.85 on validation data. Additionally, the algorithm effectively identifies uncertainty locations within system dynamics under challenging scenarios. This work highlights SINDybrid potential as a versatile, automated solution for hybrid modelling, significantly reducing the barriers to adopting hybrid methods in complex dynamic systems across scientific research and industrial applications.

[Download pre-print here](https://arxiv.org/abs/2506.12498)

[Download paper here](https://doi.org/10.1016/j.cep.2023.109285)

Recommmended citation: Di Caprio U., Leblebici M.E. (2026). SINDybrid: automatic generation of hybrid models for dynamic systems. <i>Chemical Engineering Science</i>, 321 (Part C), 122873