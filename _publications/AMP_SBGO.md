---
title: "Surrogate-based global optimization using an adaptive switching infill sampling criterion for expensive black-box functions"
collection: publications
category: manuscripts
permalink: /publication/AMP_SBGO
excerpt: 'This paper introduces a novel adaptive sampling approach using surrogate models to find the global optimum'
date: 2018-02-20
venue: 'Structural and Multidisciplinary Optimization'
paperurl: 'https://link.springer.com/article/10.1007/s00158-018-1942-2'
citation: 'Chung, I. B., Park, D., & Choi, D. H. (2018). &quot;Surrogate-based global optimization using an adaptive switching infill sampling criterion for expensive black-box functions.&quot; <i>Structural and Multidisciplinary Optimization</i>. 57(4), 1443-1459.'
---
Abstract: Surrogate-based global optimization algorithms use a surrogate model along with a sampling criterion. The AMP-SBGO algorithm sequentially samples points to gradually find the global optimum. The sampling criterion used to decide where to sample in each iteration dominates the algorithm and directly impacts its efficiency and robustness. This paper presents a method that uses multiple criteria for each phase of sampling, with conditions for switching from one criterion to another. Such behavior can improve the performance of the algorithm by allowing the optimization process to be less influenced by the initial sample points. Each phase, referred to as the global search phase and local search phase, utilizes different techniques. For the global search, a weighted maximin distance metric is proposed that is more efficient than ordinary maximin distance searches, and for the local search, the surrogate is optimized using a multi-start gradient-based optimizer. The algorithm was tested on 9 unconstrained mathematical test functions and 4 classes of GKLS functions along with 5 constrained test problems, which included 4 engineering design problems, and showed significant improvements compared to existing surrogate-based global optimization algorithms. The algorithm was then implemented to optimize the shape of a flange shaft in a washing machine.
