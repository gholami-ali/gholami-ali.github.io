---
title: "Hierarchical Gradient Coding"
mathjax: true
layout: post
---

The Gradient Coding problem referes to the setting where the computation of gradient is outsourced to multiple _workers_. Since not every worker would be reliable, to ensure the robustness of the system,
the scheme should be designed to tolerate some straggling workers; either because of a broken link or slow computation. We extended the setting to hierarchical gradient coding, where we consider intermediate nodes referred to as _relays_ between the server and the workers. We then characterized the optimal communication-computation trade-off for all the links in the system through designing
universal encoding polynomials. 

We then added the private hierarchical setting where we keep the gradient information of any subset of the data private to the relays, such that the final gradient could still be computed at the server.

A short version of our results was accepted and presented at ISIT 2025 ([Optimal Communication-Computation Trade-off in Hierarchical Gradient Coding](https://ieeexplore.ieee.org/document/11195435)), and the complete version is available on arXiv ([Hierarchical Gradient Coding: From Optimal
Design to Privacy at Intermediate Nodes](https://arxiv.org/pdf/2502.18251)), which is submitted to IEEE Transactions on Information Theory.
