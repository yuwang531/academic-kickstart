---
title: "Differential Privacy in Linear Distributed Control Systems: Entropy Minimizing Mechanisms and Performance Tradeoffs"
date: 2017-01-25
publishDate: 2017-01-25
authors: ["Yu Wang", "Zhenqi Huang", "Sayan Mitra", "Geir E. Dullerud"]
publication_types: ["2"]
abstract: "In distributed control systems with shared resources, participating agents can improve the overall performance of the system by sharing data about their personal preferences. In this paper, we formulate and study a natural tradeoff arising in these problems between the privacy of the agent's data and the performance of the control system. We formalize privacy in terms of differential privacy of agents' preference vectors. The overall control system consists of N agents with linear discrete-time coupled dynamics, each controlled to track its preference vector. Performance of the system is measured by the mean squared tracking error. We present a mechanism that achieves differential privacy by adding Laplace noise to the shared information in a way that depends on the sensitivity of the control system to the private data. We show that for stable systems the performance cost of using this type of privacy preserving mechanism grows as O(T3/N$ε$2), where T is the time horizon and $ε$ is the privacy parameter. For unstable systems, the cost grows exponentially with time. From an estimation point of view, we establish a lower-bound for the entropy of any unbiased estimator of the private data from any noise-adding mechanism that gives $ε$-differential privacy. We show that the mechanism achieving this lower-bound is a randomized mechanism that also uses Laplace noise."
featured: false
publication: "*IEEE Transactions on Control of Network Systems (TCNS)*"
url_pdf: https://ieeexplore.ieee.org/document/7833044
---

