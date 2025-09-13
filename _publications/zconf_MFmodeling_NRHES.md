---
title: "Multi-Fidelity Modeling for Dynamic Power Control and Optimization of Nuclear-Renewable Hybrid Energy Systems"
collection: publications
category: conferences
permalink: /publication/zconf_MFmodeling_NRHES
excerpt: 'This work presents a multi-fidelity modeling approach to tune the controller for N-R HES'
date: 2023-11-21
venue: 'IDETC-CIE 2023'
paperurl: 'https://doi.org/10.1115/DETC2023-116914'
citation: 'Chung, I. B., & Wang, P. (2023). &quot;Multi-Fidelity Modeling for Dynamic Power Control and Optimization of Nuclear-Renewable Hybrid Energy Systems.&quot; <i>In International Design Engineering Technical Conferences and Computers and Information in Engineering Conference. American Society of Mechanical Engineers.</i>. (Vol. 87301, p. V03AT03A036).'
---

Abstract: The attempt to utilize renewable energy that are not as stable as carbon-based power has led to hybrid energy systems (HES), where multiple generation sources are combined to supply the target sector. Nuclear-renewable hybrid energy system (N-R HES) is a promising technology that couples nuclear power plant to the renewable energy sources to send the generated power to the grid. Due to the fluctuations in the generation as well as the demand, an industrial process is typically connected to the system to utilize the produced surplus or byproducts. However, it is important to build a control strategy that can manage the power distribution between the grid and the industrial process. This study focuses on creating a multi-fidelity model to predict the appropriate control state for satisfying each demand on the given timescale of the nuclear renewable HES. A high-fidelity model was constructed using Simulink and a forward calculation was used as a low-fidelity model, where the data generated from the high-fidelity model are a nested set of the low-fidelity model’s input domain. The multi-fidelity surrogate model was trained using co-kriging method and the surrogate was tested on a synthesized example problem to validate its practicality in controlling a dynamic energy system.
