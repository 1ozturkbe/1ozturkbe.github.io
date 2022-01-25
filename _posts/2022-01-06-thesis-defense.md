---
layout: post
title: Successful thesis defense!
date: 06/01/2022
post_url: 2022-01-06-thesis-defense
categories: [blog, research, phd, optimization, global]
---

I have defended my thesis titled **Global and Robust Optimization for Engineering Design**! I am in the process of finalizing the thesis document, but I hope to post both the thesis and my presentation soon. 
Here is the abstract:

*There is a need to adapt and improve conceptual design methods through better optimization, in order to address the challenge of designing future engineered systems. Aerospace design problems are tightly-coupled multidisciplinary optimization (MDO) problems, and require all-at-once solution methods for design consensus and global optimality. Although the literature on MDO has been growing, it has generally focused on the use of gradient-based and heuristic methods, which are limited to local and low-dimensional optimization respectively. There are significant benefits to leveraging structured mathematical optimization instead. Mathematical optimization provides guarantees of solution quality, and is fast, scalable, and compatible with using physics-based models in design. More importantly perhaps, there has been a wave of research in optimization and machine learning that provides new opportunities to improve the engineering design process. This thesis capitalizes on two such opportunities.*

*The first opportunity is to enable efficient all-at-once optimization over constraints and objectives that use arbitrary mathematical primitives. This work proposes a constraint sampling and learning approach, leveraging developments in machine learning and mixed-integer optimization. More specifically, the feasible space of intractable constraints is sampled using existing and novel design of experiments methods, and learned using optimal decision trees. The decision trees describe union-of-polyhedra approximations of intractable constraints, which are solved efficiently using commercial solvers to find near-feasible and near-optimal solutions to the original problem. The constraints are then checked and repaired using projected gradient methods, restoring feasibility and local optimality. The method is demonstrated using a variety of synthetic and real-world examples where decision tree driven optimization provides efficient, practical and optimal solutions to difficult global optimization problems present in aerospace design, regardless of the form of the underlying constraints.*

*The second opportunity is to optimize designs affected by parametric uncertainty in a tractable and deterministic manner, while providing probabilistic guarantees of constraint satisfaction. Inspired by the wealth of literature on robust optimization, and specifically on robust geometric programming, this thesis proposes and implements robust signomial programming to solve engineering design problems under uncertainty. The methods are tested on a conceptual aircraft design problem, demonstrating that robust signomial programs are sufficiently general to address engineering design problems, solved efficiently by commercial solvers, and result in designs that protect deterministically against uncertain parameter outcomes that come from a predefined set.*

*In anticipation of future aerospace design problems becoming increasingly coupled, complex and risky, this thesis provides a new perspective for dealing with design challenges using structured mathematical optimization. The proposed methods inject mathematical rigor to engineering design methods while keeping practical concerns for conceptual design in focus.*

Thanks to my committee members Prof. Dimitris Bertsimas, Prof. Mark Drela and Dr. Bob Haimes, as well as my thesis readers Prof. Oli De Weck and Dr. Jack Dunn, for their support of me and this work. 

Pending the submission of my thesis and global optimization paper in *Operations Research*, I will also be making public the code required to replicate my thesis. Looking forward to it!

Berk 

[back]({{ site.url }}/blog)