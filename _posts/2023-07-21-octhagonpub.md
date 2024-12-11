---
layout: post
title: Global optimization paper published in the Journal of Global Optimization!
date: 21/07/2023
post_url: 2023-07-21-octhagonpub
categories: [blog, research, phd, global, optimization]
---

**Global Optimization via Optimal Decision Trees** has been published in the *Journal of Global Optimization*! It is open access and available [here](https://link.springer.com/article/10.1007/s10898-023-01311-x). 
Here is the abstract:

*The global optimization literature places large emphasis on reducing intractable optimization problems into more tractable structured optimization forms. In order to achieve this goal, many existing methods are restricted to optimization over explicit constraints and objectives that use a subset of possible mathematical primitives. These are limiting in real-world contexts where more general explicit and black box constraints appear. Leveraging the dramatic speed improvements in mixed-integer optimization (MIO) and recent research in machine learning, we propose a new method to learn MIO-compatible approximations of global optimization problems using optimal decision trees with hyperplanes (OCT-Hs). This constraint learning approach only requires a bounded variable domain, and can address both explicit and inexplicit constraints. We solve the MIO approximation to find a near-optimal, near-feasible solution to the global optimization problem. We further improve the solution using a series of projected gradient descent iterations. We test the method on numerical benchmarks from the literature as well as real-world design problems, demonstrating its promise in finding global optima efficiently.*

The [Julia implementation of OCTHaGOn](https://github.com/1ozturkbe/OCTHaGOn.jl) is also available, as well as its [documentation](https://1ozturkbe.github.io/OCTHaGOn.jl/). 

Berk 
