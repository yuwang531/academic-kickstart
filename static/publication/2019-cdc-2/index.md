---
title: "Attack-Resilient Supervisory Control with Intermittently Secure Communication"
date: 2019-12-15
publishDate: 2019-12-15
authors: ["Yu Wang", "Miroslav Pajic"]
publication_types: ["1"]
abstract: "In this work, we study supervisory control of discrete event systems in the presence of network-based attacks on information delivered to and from the supervisors. The attacks are modeled by finite state transducers (FSTs), having the ability to nondeterministically rewrite a word to any word of a regular language. A desired language is called controllable if there exists a security-aware supervisor that ensures that the restricted language executed by the plant for any possible attack behavior is the desired one – we refer to such supervisors as attack-resilient. First, we solve the problem of computing the maximal controllable sub-language (MCSL) of a desired language and propose the design algorithm for an attack-resilient supervisor, in scenarios where no security guarantees exists for communication between the plant and the supervisor. Then, we consider the case where the supervisor has active but intermittent access to a size-limited secure channel, which ensures integrity and availability of the data transmitted over it. Specifically, we propose the notion of accessibility as a measure of distance between a language and its sub-language, and show that a desired language is controllable with intermittently secure communication if and only if its difference from its MCSL without secure channel is bounded by the accessibility measure. Finally, we illustrate our approach on several examples."
featured: false
publication: "*IEEE Conference on Decision and Control (CDC)*"
url_pdf: "https://ieeexplore.ieee.org/document/9029366"
---

