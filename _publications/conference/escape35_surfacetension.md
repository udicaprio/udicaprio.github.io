---
title: "Predicting Surface Tension of Organic Molecules using COSMO-RS Theory and Machine Learning"
collection: Journal Papers
permalink: /publication/escape35_surfacetension
pubtype: "proceeding"
excerpt: 'In this paper we apply machine learning technique to improve the accuracy of COSMO-RS model in predicting surface tension of liquids employing molecular descriptors'
date: 2025-06-27
venue: 'Systems & Control Transactions'
paperurl: 'https://doi.org/10.69997/sct.187062'
citation: 
---
Surface tension is a fundamental property at the liquid/gas interface, influencing phenomena such as capillary action, droplet formation, and interfacial behavior in chemical engineering processes. Despite its significance, experimental determination of surface tension is time-intensive and impractical for in silico-designed compounds. Predictive models are essential for bridging this gap. This study expands on Gaudin's COSMO-RS-based model, which assumes uniform molecular orientation at the surface, by testing its predictive capability across broader temperatures (5-50°C) and developing a hybrid model combining first-principle and machine learning insights to improve Gaudin's model predictions. The HM employs a serial configuration where COSMO-RS predictions serve as inputs alongside molecular descriptors, derived using the Mordred library. SHAP analysis guides feature selection, enhancing model interpretability. An artificial neural network refines predictions, optimized via Bayesian optimization for architecture and hyperparameters. Using a diverse dataset of 85 organic molecules, the HM demonstrates improved accuracy, reducing various metrics compared to standalone first-principle predictions.

[Download paper here](https://doi.org/10.69997/sct.187062)

Recommended citation: Esposito F., Di Caprio U., Rodrigues B., Vermeire F.H., Nogueira I.B.R., Leblebici M.E. (2025). Predicting Surface Tension of Organic Molecules using COSMO-RS Theory and Machine Learning . i>Systems & Control Transactions</i>, 4, 1890-1895