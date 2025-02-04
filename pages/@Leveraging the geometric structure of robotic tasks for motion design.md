date:: 2021
title:: @Leveraging the geometric structure of robotic tasks for motion design
pages:: 149
item-type:: [[journalArticle]]
access-date:: 2025-02-03T11:32:55Z
original-title:: Leveraging the geometric structure of robotic tasks for motion design
language:: en
url:: https://purl.stanford.edu/jw453mh1486
short-title:: PBDS dissertation
authors:: [[Andrew Michael Aaron Bylard]]
library-catalog:: purl.stanford.edu
links:: [Local library](zotero://select/library/items/RS9WCMRW), [Web library](https://www.zotero.org/users/12562648/items/RS9WCMRW)

- [[Abstract]]
	- Robots operating in the unstructured environments of the real world must contend with at least two sources of geometric complexity: (1) the difefrential geometric complexity of robot configuration spaces and task spaces, which can in practice be general non-Euclidean manifolds, and (2) the complexity of the geometric shape of robot links and obstacles in the environment, which have infinite variability and are often highly nonconvex. Mature robot autonomy requires algorithms that can tackle these sources of geometric complexity with precision and at real-time control and planning speeds. This thesis focuses on bridging existing gaps in previous methods to meet these needs. In particular, to address differential geometric complexity in motion design, we frist present a framework called Multi-Task Pullback Bundle Dynamical Systems (PBDS), which is a geometric control methodology for forming fast composable geometric motion policies, respecting simultaneous robotic tasks on non-Euclidean robot and task manifolds. Second, we present an embedded sequential convex programming approach which exploits differential geometric structure to eliminate explicit manifold-type constraints in trajectory optimization while still guaranteeing final satisfaction of these constraints. Together, these approaches correctly enforce the differential geometric structure of robot planning and control problems while maintaining similar or greater computational efficiency compared to past approaches. Finally, we address the shape complexity of robot links and obstacles by repurposing hardware-accelerated ray-tracing (i.e., ray-tracing cores) for rapidly forming collision avoidance constraints in trajectory optimization, particularly targeting complex robot and obstacle triangle mesh representations. This enables robot motion designers to leverage the full complexity of robot and obstacle geometries at speeds orders of magnitude faster than currently available collision-checking libraries, while leveraging recently-developed ray-tracing cores which have previously had little utility in the robot autonomy stack.
- [[Attachments]]
	- [PDF](zotero://select/library/items/ITFAL6CG) {{zotero-imported-file ITFAL6CG, "Bylard - 2021 - Leveraging the geometric structure of robotic tasks for motion design.pdf"}}
	- [Snapshot](https://purl.stanford.edu/jw453mh1486) {{zotero-imported-file 54QN2X5J, "jw453mh1486.html"}}