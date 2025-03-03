---
layout: page
title: gpvisc
description: Gaussian Process - Artificial Neural Network modelling of magma viscosity. 
img: assets/img/gpvisc_code.png
importance: 1
category: work
related_publications: false
---

gpvisc is a machine learning model that combines Gaussian process and a deep neural networks to predict the viscosity of phospho-alumino-silicate melts.

Here are some of the nice features:

- builds on a exhaustive open access database of data in the system SiO2-FeO-Fe2O3-TiO2-Al2O3-MnO-MgO-CaO-Na2O-K2O-P2O5-H2O, have a look at it on the [IPGP data repository](https://doi.org/10.18715/IPGP.2024.lycv4gsa).
- open source, open access on [Github](https://github.com/charlesll/gpvisc).
- easy to install via PyPI, follow the intructions in the [documentation](http://charlesll.github.io/gpvisc/html/index.html).
- a [Streamlit instance](https://gpvisc.streamlit.app/) provide an easy to use web interface to the model.

We use this model in our EPSL paper to calculate the viscosity of a magma ocean on a lava planet such as K2-141 b, check this link: [https://doi.org/10.1016/j.epsl.2025.119287](https://doi.org/10.1016/j.epsl.2025.119287) !
