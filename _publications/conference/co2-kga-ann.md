---
title: "Optimization of an artificial neural network structure for modelling carbon capture in spray columns"
collection: Journal Papers
permalink: /publication/co2-kga-ann
pubtype: "proceeding"
excerpt: 'In this paper we apply bayesian optimization to identify the most efficient neural network structure to predict mass-transfer coefficients CO<sub>2</sub> capture spray columns'
date: 2022-08-01
venue: 'Computer Aided Chemical Engineering'
paperurl: 'https://doi.org/10.1016/B978-0-323-95879-0.50236-8'
citation: 
---
Anthropogenic CO<sub>2</sub> emissions reinforce global warming. The most mature technology to capture post-combustion CO<sub>2</sub> is the absorption with aqueous monoethanolamine (MEA) in spray or packed columns. However, this process is not considered economically viable. One reason for this hindrance is the low overall mass transfer coefficients (K<sub>G</sub>a) resulting in large process volumes that are high in capital and operating costs. Spray columns offer some advantages over the packed columns such as the lack of expensive column internals, low pressure drop and higher K<sub>G</sub>a. Although several spray columns have been investigated experimentally, there are only a few efforts to model this process. Because of the high intercorrelation between the process variables, modelling is a complex task. Machine learning techniques have shown great accuracy in modeling this kind of systems using large amounts of data. Artificial neural network (ANN) is one of the most promising and highly modular techniques in this field. The aim of this work is to find the ANN structure with higher accuracy and generalization capabilities to model the K<sub>G</sub>a for CO<sub>2</sub> absorption in spray columns using aqueous MEA. The ANN is trained using the back-propagation algorithm. The structure with higher accuracy and generalization properties is searched by a Bayesian optimizer. The trained model has a coefficient of determination (R<sup>2</sup>) of 0.98, and a mean squared error (MSE) of 7.89e-4 on the validation set. It returns prediction errors below 20%. The optimizer found that the autoencoder structure had the higher prediction accuracy and generalization capabilities. This shape has great feature importance extrapolation capabilities, allowing the ANN to have a high prediction accuracy. The proposed procedure can be applied also for other processes where transfer coefficients need to be estimated and optimized.

[Download paper here](https://doi.org/10.1016/B978-0-323-95879-0.50236-8)

Recommended citation: Di Caprio, U., Kayahan, E., Wu, M., Mercelis, S., Hellinckx, P., Van Gerven, T., Waldherr, S., Leblebici, M.E. (2022). Optimization of an artificial neural network structure for modelling carbon capture in spray columns. <i>Computer Aided Chemical Engineering</i>, 51, 1411-1416