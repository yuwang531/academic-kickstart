---
title: "Differentially Private Objective Functions in Distributed Cloud-Based Optimization"
date: 2016-12-15
publishDate: 2016-12-15
authors: ["Yu Wang", "Matthew, Hale Hale", "Magnus Egerstedt", "Geir E. Dullerud"]
publication_types: ["1"]
abstract: "In this work, we study the problem of keeping the objective functions of individual agents $ε$-differentially private in cloud-based distributed optimization, where agents are subject to global constraints and seek to minimize local objective functions. The communication architecture between agents is cloud-based - instead of communicating directly with each other, they coordinate by sharing states through a trusted cloud computer. In this problem, the difficulty is twofold: the objective functions are used repeatedly in every iteration, and the influence of perturbing them extends to other agents and lasts over time. To solve the problem, we analyze the propagation of perturbations on objective functions over time, and derive an upper bound on them. With the upper bound, we design a noise-adding mechanism that randomizes the cloud-based distributed optimization algorithm to keep the individual objective functions $ε$-differentially private. In addition, we study the trade-off between the privacy of objective functions and the performance of the new cloud-based distributed optimization algorithm with noise. We present simulation results to numerically verify the theoretical results presented."
featured: false
publication: "*IEEE Conference on Decision and Control (CDC)*"
url_pdf: https://ieeexplore.ieee.org/document/7798824
---

