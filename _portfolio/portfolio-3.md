---
title: "Social Network Analysis in Online Learning — method-focused line"
collection: portfolio
permalink: /portfolio/sna-methods/
excerpt: "Applying established SNA techniques—sometimes with text features—to examine interaction and engagement in online discussion."
thumbnail: images/sna_readability_thumb.png
order: 2
tags: [learning-analytics, sna, community-detection, readability]
---

## Overview (2021–2024)
This line applies established social network analysis to course-scale discussion data. In one study, basic text readability is considered alongside network position. The aim is to offer a clear, practical view of participation patterns without heavy pipelines.

---

## Publications (with one-line takeaways)

**Interactive Learning Environments (2025)**  
*Beyond posting frequency: how network metrics and textual readability relate to engagement in online discussion.*  
[DOI](http://dx.doi.org/10.1080/10494820.2025.2550035)  
- **Question:** Do network positions and message readability relate to later engagement?  
- **Approach:** Common SNA metrics (e.g., indegree, betweenness, eigenvector) and readability indices (Flesch, FKGL) from course forums.  
- **Finding:** Network position is consistently associated with engagement; readability shows smaller, context-dependent links.  
- **Use:** Simple structural and text signals to see where attention concentrates.

**International Journal of Educational Technology in Higher Education (2024)**  
*Applying a community detection algorithm to examine group formation in online discussions.*  
[DOI](https://doi.org/10.1186/s41239-024-00495-w) · Slides: [AERA 2023](https://mlee010.github.io/MinkyungLee/files/AERA23_Louvain.pdf)  
- **Question:** What subgroups emerge naturally, and how do they communicate?  
- **Approach:** Louvain community detection; compared within-group cohesion and between-group ties.  
- **Finding:** Detected groups showed coherent internal communication patterns aligned with observed interaction.  
- **Use:** Readable maps of collaboration that can guide support and activity design.

**Education and Information Technologies (in revision)**  
*Quality of student cognitive engagement across different levels of social engagement.*  
- **Question:** Does social embeddedness relate to the quality of cognitive moves?  
- **Approach:** Related coded cognitive indicators to local/central network positions.  
- **Finding:** Richer cognitive moves tended to appear with higher embeddedness, with variation by role and topic.  
- **Use:** Monitoring both social position and content quality can help target facilitation.

---

## Methods (quick view)
- **Network construction:** reply-to edges at the post level; course-scale graphs.
- **Metrics:** indegree/outdegree, betweenness, eigenvector, clustering coefficient.
- **Communities:** Louvain for subgroup identification; compared cohesion and cross-group ties.
- **Text (when used):** readability indices (Flesch, FKGL, Gunning Fog, SMOG).
- **Role:** study design, analysis, writing.

<details><summary>Notes on assumptions & robustness</summary>

- Descriptive/associational focus; no causal claims.  
- Results can vary by prompt design, timing, and assessment context.  
- Replication in new settings is encouraged.
</details>

---

## Materials
- **Community detection paper (PDF):** [link](https://mlee010.github.io/MinkyungLee/files/41239_2024_495_OnlinePDF.pdf)  
- **Slides (community detection):** [AERA 2023](https://mlee010.github.io/MinkyungLee/files/AERA23_Louvain.pdf)  
- **Readability study:** add accepted manuscript or slides when available.

---

## What this adds
- A clear lens on **who interacts with whom** and how that aligns with attention and participation.  
- When included, **readability** offers a light-weight text signal that complements network position.  
- Practical cues (subgroup cohesion, central participants, message accessibility) that can inform facilitation and course adjustments.
