---
title: "theta-pairings-dim2"
collection: research
category: code
permalink: /research/genus-2-pairings
excerpt: 'Implementation of pairings on genus-2 Jacobians using theta coordinates and biextensions'
codeurl: https://github.com/sferl/theta-pairings-dim2
# venue:  'University of Pisa'
---
<!-- # citation: 'Alessandro Sferlazza, University of Pisa, September 2024. Supervisors: Benjamin Smith, Davide Lombardo' -->

[link to the Github repo](https://github.com/sferl/theta-pairings-dim2)

This is a repository that implements the computation of the Tate pairing and Weil pairing on abelian varieties of dimension 2 (Jacobians of genus-2 hyperelliptic curves and products of elliptic curves) using the theory of algebraic theta functions and the theory of biextensions of elliptic curves.

It is based on:
- [```two-isogenies```](https://github.com/ThetaIsogenies/two-isogenies) that implements 2-dimensional abelian varieties in the theta model;
- [```kummer-line```](https://gitlab.inria.fr/roberdam/kummer-line) that implements biextension-based pairing algorithms in dimension 1.

It was written as a proof-of-concept implementation linked to Chapter 4 of my [Master's thesis](/research/master-thesis). The repo is still in an early stage (no randomized testing, no optimizations) but I hope to clean it up and integrate it in SageMath (after ```two-isogenies``` is integrated too) in the future. Contributions or suggestions are welcome!