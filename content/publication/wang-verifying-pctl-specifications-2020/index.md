---
title: "Verifying PCTL Specifications on Markov Decision Processes via Reinforcement Learning"
date: 2020-01-01
publishDate: 2019-11-13T00:48:38.011590Z
authors: ["Yu Wang", "Nima Roohi", "Matthew West", "Mahesh Viswanathan", "Geir E. Dullerud"]
publication_types: ["1"]
abstract: "We propose a new statistical verification technique for PCTL$*̂$ logic, which unifies Probabilistic Computational Tree Logic (PCTL) and Linear Time Logic (LTL), on labeled Markov Decision Processes (MDPs) with unknown transition probabilities using reinforcement learning. We first show that verifying a non-nested PCTL$̂$ formula on a MDP is equivalent to estimating the reachability probability of a goal set on the product MDP of the original MDP and a Muller automaton modeling the corresponding LTL specification. Then, we develop Q-learning algorithms to statistically estimate reachability probability on the product MDP, with the optimal policy identified and evaluated using the principle of optimism in the face of uncertainty (OFU). Specifically, we construct upper confidence bounds (UCB) for each state-action pair from previous samples, and explore the best action with the highest UCB. Using the OFU principle, we design termination conditions for any desired confidence level, and prove the correctness of the proposed algorithms. Finally, we evaluate the proposed algorithms on several case studies."
featured: false
publication: "*21st International Conference on Verification, Model Checking, and Abstract Interpretation (VMCAI) (Under Review)*"
---

