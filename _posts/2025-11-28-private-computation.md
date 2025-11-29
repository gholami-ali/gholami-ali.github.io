---
title: "Multi-Message Private Computation"
mathjax: true
layout: post
---

In the private information retreival (PIR) setting, the goal is that the user retreives a filen by sending queries to multiple servers, each storing the same library, and receiving corresponding answers from each server, while keeping the demanded file index private to each server. This is only possible if no matter the choice of demanded file, the distribution on the query sent to each server, remains the same. This becomes more challenging, when the aim is to reach the minimum amount of download needed from each server, a parameter referred to as the _capacity_.

The multi-message private computation (MM-PC) setting extends the PIR setting to the case where the user is allowed to request multiple (instead of one) linear combinations (instead of files themselves) of the files in the library. To that end, we have designed symmetric queries sent to the servers, where each request a linear combination of subpackets of possibly multiple files. We then show that some of these queries would be redundant (using the fact that the requests of the user are in the end linear combinations of some limited independent files), which helps to reduce the amount of download through an MDS-coded masking. We show that the resulted schemes would be order-optimal in most parameter regimes. As a by-product, the designed scheme leads to a new capacity-achieving private computation scheme for the case of one linear request. 

A short version of our results was accepted and presented at ISIT 2024 ([On Multi-Message Private Computation](https://ieeexplore.ieee.org/abstract/document/10619493)), and the complete version is published on IEEE Transaction on Communications [Fundamental Limits of Multi-Message Private Computation](https://ieeexplore.ieee.org/abstract/document/10891903/).
