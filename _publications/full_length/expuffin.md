---
title: "ExPUFFIN: Thermodynamic consistent viscosity prediction in an Extended Path-Unifying Feed-Forward Interfaced Network"
collection: publications
permalink: /publication/expuffin
pubtype: "journal"
excerpt: 'In this paper we create and validate an hybrid model involving GNN for predicting viscosity using physical equations.'
date: 2026-03-18
venue: 'Chemical Engineering Journal Advances'
paperurl: 'https://doi.org/10.1016/j.ceja.2026.101129'
citation: 
---
Accurate prediction of temperature-dependent liquid viscosity is essential for process design and molecular screening but remains challenging for novel hydrocarbons. Purely data-driven graph neural networks (GNNs) can achieve good in-range accuracy yet often lack thermodynamic consistency and become unstable under temperature shifts or sparse calibration data. This work introduces ExPUFFIN (Extended Path-Unifying Feed-Forward Interfaced Network), a hybrid GNN framework that embeds established viscosity–temperature correlations directly into the output layer by learning molecule-specific parameters of Andrade-type and empirical formulations. The approach is evaluated on a curated dataset of 305 pure hydrocarbons using standard test metrics, interpolation analysis, Leave-One-Temperature-Out evaluation, and extrapolation beyond the experimental range. While the baseline model attains comparable test errors, it exhibits oscillatory and inconsistent behaviour outside the training domain. In contrast, the ExPUFFIN variants preserve smooth, monotonic viscosity–temperature trends and substantially reduce extrapolation errors. The results show that incorporating inductive bias into the network output improves robustness and reliability without compromising predictive accuracy.


[Download paper here](https://doi.org/10.1016/j.ceja.2026.101129)

Recommended citation: Rebello, C.M., Di Caprio, U., Steen-Hansen, J., Rodrigues, B., Costa, E.A., dos Santos, A.R., Esposito, F., Leblebici, M.E., Nogueira, I.B.R. (2026). ExPUFFIN: Thermodynamic consistent viscosity prediction in an Extended Path-Unifying Feed-Forward Interfaced Network. <i>Chemical Engineering Journal Advances</i>, 26, 101129.