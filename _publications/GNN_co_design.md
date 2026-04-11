---
title: "Data-driven co-design of power distribution networks for resilience enhancement through graph neural network aided performance estimation"
collection: publications
category: manuscripts
permalink: /publication/GNN_co_design
excerpt: 'This paper proposes a control co-design framework of network design and recovery scheduling for distribution networks using GNN regression model and metaheuristic algorithm for graphs'
date: 2026-03-14
venue: 'Reliability Engineering & System Safety'
paperurl: 'https://doi.org/10.1016/j.ress.2026.112511'
citation: 'Chung, I. B., Luo, Y., & Wang, P. (2026). &quot;Data-driven Co-design of Power Distribution Networks for Resilience Enhancement through Graph Neural Network aided Performance Estimation.&quot; <i>Reliability Engineering & System Safety</i>, 112511.'
---

Abstract: To enhance the resilience of critical infrastructures, a co-design optimization framework is developed for the design of the distribution network and its recovery scheduling. Since network representations are distinct from conventional numerical data, the framework needs to be tailored to overcome unique challenges. Due to the networks being represented as graphs rather than numerical values, derivative-free optimization is the most suitable option. In a random search, the neighborhood must be defined considering the graph data structure. In this study, a surrogate model that can estimate the resilience of the network system is built using a deep-learning-based graph neural network (GNN) to reduce the computational burden during a derivative-free optimization algorithm. Network vulnerabilities are identified using centrality measures from graph theory, where the total demand loss is quantified with sequential component removals to represent system resilience. Integrating the design optimization into the recovery problem defined as a mixed-integer linear programming (MILP) model, the proposed framework can find the optimum solution for network design and recovery resource scheduling. To prove the efficacy of the proposed GNN-based co-design framework, it was applied to multiple power system benchmarks, where the results demonstrated the practicality of the framework.
