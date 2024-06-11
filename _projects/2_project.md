---
layout: page
title: Machine learning
description: Using machine learning to tackle geoscience problems.
img: assets/img/atoms_barbara.webp
importance: 1
category: work
related_publications: false
---
Many problems in geosciences require models to make predictions. A subset of the questions I am working on include the followings:

    - How do a magma flows given temperature and composition? 
    - What is the composition of a lava given its Raman spectrum? 
    - Will the Piton de la Fournaise produce an eruption in the next few days?

Physical models may be used for solving those problems, but often, we lack the necessary equations to do that. In this case, machine learning has shown to be a promizing method. It allows exploring datasets, classifying data, and performing regression tasks.

# Classification of geochemical data

Machine learning algorithms such as PCA or Gaussian mixture models can be used to explore and use tabular geochemical data, including major and minor element concentrations or isotopic compositions. 

An example of that is our work with Mat Valetich, published in [Journal of Petrology](https://doi.org/10.1093/petrology/egab013). In this paper, we show how machine learning algorithms allow using the major and trace element compositions of melt inclusions to classify boninite magmas. The code is available on [Github](https://github.com/charlesll/boni-and-class), and is based on conventional (and easy-to-use) Scikit-Learn algorithms.

# Predicting the properties of magmas and glasses

Models such as i-Melt (see [the related project page](4_project.md)) leverage the power of ML to predict the properties of materials. They can be used then in many application, including fluid dynamic simulations, petrological models, etc.

# Treatment and interpretation of spectroscopic data

Processing Raman, Infrared, NMR... spectroscopic data is often time consuming and a tedious task. Many efforts are now made to automate such tasks, and also to discover new, hidden patterns. 

Our work shows that :
- leveraging ML can allow quantifying the chemical composition, including iron oxidation state, of glasses from their Raman spectra [(Le Losq et al., 2019)](10.2138/am-2019-6887);
- using methods such as PCA or NMF allow retrieving meaningful spectral components [(Jollands et al. 2021)](https://doi.org/10.5194/ejm-33-113-2021);
- deep learning models such as [i-Melt](4_project.md) can even predict spectra.
