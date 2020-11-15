---
title: "Model-Free Reinforcement Learning for Stochastic Games with Linear Temporal Logic Objectives"
date: 2020-11-02
publishDate: 2020-11-02
authors: ["Alper Kamil Bozkurt", "Yu Wang", "Michael Zavlanos", "Miroslav Pajic"]
publication_types: ["1"]
abstract: "We study the problem of synthesizing control strategies for Linear Temporal Logic (LTL) objectives in unknown environments. We model this problem as a turn-based zero-sum stochastic game between the controller and the environment, where the transition probabilities and the model topology are fully unknown. The winning condition for the controller in this game is the satisfaction of the given LTL specification, which can be captured by the acceptance condition of a deterministic Rabin automaton (DRA) directly derived from the LTL specification. We introduce a model-free reinforcement learning (RL) methodology to find a strategy that maximizes the probability of satisfying a given LTL specification when the Rabin condition of the derived DRA has a single accepting pair. We then generalize this approach to LTL formulas for which the Rabin condition has a larger number of accepting pairs, providing a lower bound on the satisfaction probability. Finally, we illustrate the applicability of our RL method on two motion planning case studies."
featured: true
# publication: "*59th IEEE Conference on Decision and Control (CDC) (Under Review)*"
url_pdf: "https://arxiv.org/abs/2010.01050"
---

