---
title: "Social Network Analysis in Online Learning — Method-focused line"
collection: portfolio
permalink: /portfolio/sna-methods/
excerpt: "Applying established SNA techniques—sometimes alongside text features—to study interaction and engagement in online discussion."
thumbnail: images/sna_readability_thumb.png
order: 2
tags: [learning-analytics, SNA, community-detection, readability]
---

**Scope (2021–2024).** This line of work applies **established social network analysis** to course-scale discussion data and, in one study, adds a **readability** perspective. The contribution is a **slightly different lens** on familiar techniques—using community detection to interpret emergent groups and linking basic text accessibility to network positions and engagement.

**Key papers**
- *Beyond posting frequency: how network metrics and textual readability relate to engagement in online discussion.* **Interactive Learning Environments** (2025). [DOI](http://dx.doi.org/10.1080/10494820.2025.2550035)
- *Applying a community detection algorithm to examine group formation in online discussions.* **International Journal of Educational Technology in Higher Education** (2024). [DOI](https://doi.org/10.1186/s41239-024-00495-w)
- Slides: [AERA 2023](https://mlee010.github.io/MinkyungLee/files/AERA23_Louvain.pdf)
- Sharma & Lee (in revision). *Quality of student cognitive engagement across different levels of social engagement.* **Education and Information Technologies**

<details open><summary>Methods</summary>
- SNA: indegree/outdegree, betweenness, eigenvector, clustering; **Louvain** for community detection  
- Text features (readability paper only): Flesch, FKGL, Gunning Fog, SMOG  
- Role: study design, analysis, writing
</details>

**Open materials**
- Slides: [AERA 2023](https://mlee010.github.io/MinkyungLee/files/AERA23_Louvain.pdf)

**Related / adjacent (CoI & sociograms)**
- Lee & Clariana (in revision). *Implementing sociograms in online learning: examining their influence on Community of Inquiry elements.* **Learning Environments Research** — Slides: [AERA 2024](https://mlee010.github.io/MinkyungLee/files/AERA24Sociogram.pdf)
- CoI perceptions: [AECT 2021](https://mlee010.github.io/MinkyungLee/files/21Perception.pdf)

### Summary of Studies
**Beyond posting frequency: how network metrics and textual readability relate to engagement in online discussion**  
*Interactive Learning Environments (2025)*
- **Goal:** Examine whether students’ network positions and the readability of their posts relate to subsequent engagement (replies/attention).
- **Approach:** Computed common SNA metrics (e.g., indegree, betweenness, eigenvector) and basic readability indices (e.g., Flesch, FKGL) from course discussion data.
- **Main finding:** Network position was consistently associated with engagement; readability showed smaller but meaningful associations in certain contexts.
- **Takeaway:** Simple structural and text features can offer instructors a practical view of where participation concentrates and how message clarity might matter.

**Applying a community detection algorithm to examine group formation in online discussions**  
*International Journal of Educational Technology in Higher Education (2024)*
- **Goal:** Identify natural subgroups in course discussions and describe how those subgroups communicate.
- **Approach:** Used the Louvain method to detect communities; compared within-group cohesion and between-group interaction using standard network measures.
- **Main finding:** Detected groups showed coherent internal communication patterns; subgroup structure aligned with how students actually interacted over time.
- **Takeaway:** Community detection provides a readable map of collaboration that can inform group support, moderation, or activity design.
---

### Overall contribution of this line
- Uses established SNA tools (and, in one study, readability indices) to look at online discussion from a slightly different angle.
- Shows how **who-talks-to-whom** and **how messages read** can be combined (or examined separately) to describe participation patterns without complex pipelines.
- Offers practical signals (e.g., subgroup cohesion, central participants, message clarity) that can guide facilitation and course adjustments.

### Notes & scope
- These studies focus on **description and association**, not causal claims.
- Results may vary by course design, topic, and assessment practices; replication in new contexts is encouraged.
