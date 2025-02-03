tags:: [[Dynamical systems]], [[Manifolds]], [[Measurement]], [[Planning]], [[Robot motion]], [[Stress]], [[Task analysis]]
date:: 2021-05
conference-name:: 2021 IEEE International Conference on Robotics and Automation (ICRA)
proceedings-title:: 2021 IEEE International Conference on Robotics and Automation (ICRA)
extra:: ISSN: 2577-087X
doi:: 10.1109/ICRA48506.2021.9561320
title:: @Composable Geometric Motion Policies using Multi-Task Pullback Bundle Dynamical Systems
pages:: 7464-7470
item-type:: [[conferencePaper]]
access-date:: 2025-02-03T11:29:05Z
original-title:: Composable Geometric Motion Policies using Multi-Task Pullback Bundle Dynamical Systems
url:: https://ieeexplore.ieee.org/document/9561320
authors:: [[Andrew Bylard]], [[Riccardo Bonalli]], [[Marco Pavone]]
library-catalog:: IEEE Xplore
links:: [Local library](zotero://select/library/items/BK2WTVNY), [Web library](https://www.zotero.org/users/12562648/items/BK2WTVNY)

- [[Abstract]]
	- Despite decades of work in fast reactive planning and control, challenges remain in developing reactive motion policies on non-Euclidean manifolds and enforcing constraints while avoiding undesirable potential function local minima. This work presents a principled method for designing and fusing desired robot task behaviors into a stable robot motion policy, leveraging the geometric structure of non-Euclidean manifolds, which are prevalent in robot configuration and task spaces. Our Pullback Bundle Dynamical Systems (PBDS) framework drives desired task behaviors and prioritizes tasks using separate position-dependent and position/velocity-dependent Riemannian metrics, respectively, thus simplifying individual task design and modular composition of tasks. For enforcing constraints, we provide a class of metric-based tasks, eliminating local minima by imposing non-conflicting potential functions only for goal region attraction. We also provide a geometric optimization problem for combining tasks inspired by Riemannian Motion Policies (RMPs) that reduces to a simple least-squares problem, and we show that our approach is geometrically well-defined. We demonstrate the PBDS framework on the sphere S2 and at 300-500 Hz on a manipulator arm, and we provide task design guidance and an open-source Julia library implementation. Overall, this work presents a fast, easy-to-use framework for generating motion policies without unwanted potential function local minima on general manifolds.
- [[Attachments]]
	- [IEEE Xplore Abstract Record](https://ieeexplore.ieee.org/document/9561320) {{zotero-imported-file IG6TERJM, "9561320.html"}}
	- [Submitted Version](https://arxiv.org/pdf/2101.01297) {{zotero-imported-file RZGVPYUV, "Bylard et al. - 2021 - Composable Geometric Motion Policies using Multi-Task Pullback Bundle Dynamical Systems.pdf"}}