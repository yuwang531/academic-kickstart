---
title: "STMC: Statistical Model Checker with Stratified and Antithetic Sampling"
date: 2020-07-15
publishDate: 2020-07-15
authors: ["Nima Roohi", "Yu Wang", "Matthew West", "Geir E Dullerud", "Mahesh Viswanathan"]
publication_types: ["1"]
abstract: "STMC is a statistical model checker that uses  antithetic and stratified sampling techniques  to reduce the number of samples and, hence,  the amount of time required before making a decision.  The tool is capable of statistically verifying any   black-box probabilistic system that PRISM can simulate,  against probabilistic bounds on any property that PRISM  can evaluate over individual executions of the system.  We have evaluated our tool on many examples and compared  it with both symbolic and statistical algorithms.  Our experimental results show that our techniques  are indeed able to reduce the number of samples significantly.  When the number of strata is large, our algorithms  singificantly reduced the number of samples. Furthermore, being a statistical model checker makes STMC  able to verify models that are well beyond the reach of current  symbolic model checkers.  On large systems (up to 101̂4 states)  STMC was able to check 100% of benchmark systems,  compared to existing methods which only succeeded on 14% of systems. The tool, installation instructions, benchmarks, and scripts for running the benchmarks are all available online as open source."
featured: false
publication: "*International Conference on Computer-Aided Verification (CAV)*"
url_pdf: "files/nr_stmc.pdf"
---

