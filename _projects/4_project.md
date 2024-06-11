---
layout: page
title: i-Melt
description: Physics-guided neural network model to predict the properties of aluminosilicate melts and glasses
img: assets/img/atoms_barbara.webp
importance: 1
category: work
related_publications: false
---

i-Melt is a physics-guided neural network model, that combines deep neural networks with physical equations to predict the structural, thermodynamic and dynamic properties of aluminosilicate melts and glasses.

The best introduction to i-Melt is [this blog post on Medium](https://medium.com/pytorch/from-windows-to-volcanoes-how-pytorch-is-helping-us-understand-glass-8720d480f4f2). 

The second version now allows predictions of the properties of melts and glasses with alkali and alkaline-earth bearing aluminosilicate compositions, from SiO<sub>2<\sub> to aluminates and multicomponent aluminosilicates.

Models such as i-Melt are very interesting because they embed known physical/thermodynamic equations, leaving only unknow parts of the problem to be solved by machine learning. Leveraging our knowledge and the power of ML is perfect, it allows obtaining models with powerful predictive abilities, as shown in  [our paper](https://arxiv.org/abs/2304.12123).

It can be used as a Python library (check the [Github repo](https://github.com/charlesll/i-melt), installation with pip is on its way) and [a easy-to-use web calculator is available](https://i-melt.streamlit.app/).
