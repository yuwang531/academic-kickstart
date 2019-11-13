---
title: "Controller Synthesis with Inductive Proofs for Piecewise Linear Systems: An SMT-Based Algorithm"
date: 2015-01-01
publishDate: 2019-11-13T00:53:51.935209Z
authors: ["Zhenqi Huang", "Yu Wang", "Sayan Mitra", "Geir E. Dullerud", "Swarat Chaudhuri"]
publication_types: ["1"]
abstract: "We present a controller synthesis algorithm for reach-avoid problems for piecewise linear discrete-time systems. Our algorithm relies on SMT solvers and in this paper we focus on piecewise constant control strategies. Our algorithm generates feedback control laws together with inductive proofs of unbounded time safety and progress properties with respect to the reach-avoid sets. Under a reasonable robustness assumption, the algorithm is shown to be complete. That is, it either generates a controller of the above type along with a proof of correctness, or it establishes the impossibility of the existence of such controllers. To achieve this, the algorithm iteratively attempts to solve a weakened and strengthened versions of the SMT encoding of the reach-avoid problem. We present preliminary experimental results on applying this algorithm based on a prototype implementation."
featured: false
publication: "*54th IEEE Conference on Decision and Control (CDC)*"
---

