date:: 2021-07
issn:: 1558-3783
issue:: 3
extra:: Conference Name: IEEE Transactions on Automation Science and Engineering
doi:: 10.1109/TASE.2021.3053422
title:: @RMPflow: A Geometric Framework for Generation of Multitask Motion Policies
pages:: 968-987
volume:: 18
item-type:: [[journalArticle]]
access-date:: 2025-02-03T11:27:48Z
original-title:: RMPflow: A Geometric Framework for Generation of Multitask Motion Policies
url:: https://ieeexplore.ieee.org/document/9388869
short-title:: RMPflow
publication-title:: IEEE Transactions on Automation Science and Engineering
authors:: [[Ching-An Cheng]], [[Mustafa Mukadam]], [[Jan Issac]], [[Stan Birchfield]], [[Dieter Fox]], [[Byron Boots]], [[Nathan Ratliff]]
library-catalog:: IEEE Xplore
links:: [Local library](zotero://select/library/items/2G9877BU), [Web library](https://www.zotero.org/users/12562648/items/2G9877BU)

- [[Abstract]]
	- Generating robot motion for multiple tasks in dynamic environments is challenging, requiring an algorithm to respond reactively while accounting for complex nonlinear relationships between tasks. In this article, we develop a novel policy synthesis algorithm, Riemannian motion policy (RMP)flow, based on geometrically consistent transformations of RMPs. RMPs are a class of reactive motion policies that parameterize non-Euclidean behaviors as dynamical systems in intrinsically nonlinear task spaces. Given a set of RMPs designed for individual tasks, RMPflow can combine these policies to generate an expressive global policy, while simultaneously exploiting sparse structure for computational efficiency. We study the geometric properties of RMPflow and provide sufficient conditions for stability. Finally, we experimentally demonstrate that accounting for the natural Riemannian geometry of task policies can simplify classically difficult problems, such as planning through the clutter on high-degree-of-freedom manipulation systems. Note to Practitioners—Requirements on safety and responsiveness for collaborative robots have driven a need for new ideas in control design that bridge between standard objectives in low-level control (such as trajectory tracking) and high-level behavioral objectives (such as collision avoidance) often relegated to planning systems. Modern results from geometric control, which promise stable controllers that can smoothly and safely transition between many behavioral tasks, therefore, become highly relevant. However, for years, this field has remained inaccessible due to its mathematical complexity. This article aims to: 1) make those ideas accessible to robotics and control experts by recasting them in a concrete algorithmic framework amenable to controller design and 2) to additionally generalize them to better satisfy the specific needs of robotic behavior generation. Our experiments demonstrate that the resulting controllers can engender natural behavior that adapts instantaneously to changing surroundings with zero planning while performing manipulation tasks. The framework is gaining traction within the robotics community, finding increasing application in areas, such as autonomous navigation, tactile servoing, and multi-agent systems. Future research will address learning these controllers from data to simplify that process of design and tuning, which at present can require experience.
- [[Attachments]]
	- [IEEE Xplore Abstract Record](https://ieeexplore.ieee.org/document/9388869) {{zotero-imported-file QQTG3G2U, "9388869.html"}}
	- [Submitted Version](https://arxiv.org/pdf/2007.14256) {{zotero-imported-file QF5D7TDT, "Cheng et al. - 2021 - RMPflow A Geometric Framework for Generation of Multitask Motion Policies.pdf"}}