---
title: "PROPHET: explainable predictive process monitoring with heterogeneous graph neural networks"
collection: publications
category: manuscripts
permalink: /publication/prophet
excerpt: 'This paper proposes a graph-based approach to solving next activity prediction task for explainable predictive process monitoring.'
date: 2024-09-18
venue: 'IEEE Transactions on Services Computing'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://doi.org/10.1109/TSC.2024.3463487'
citation: ' Pasquadibisceglie, V., Scaringi, R., Appice A., Castellano, G., Malerba D. (2024). &quot;PROPHET: Explainable Predictive Process Monitorning With Heterogeneous Graph Neural Networks; <i>IEEE-TSC</i>. 17.'
---

In this paper, we introduce PROPHET, an innovative approach to predictive process monitoring based on Heterogeneous Graph Neural Networks. PROPHET is designed to strike a balance between accurate predictions and interpretability, particularly focusing on the next-activity prediction task. For this purpose, we represent  the event traces recorded for different business process executions as heterogeneous graphs within a multi-view learning scheme combined with a heterogeneous graph learning approach. Using heterogeneous Graph Attention Networks (GATs), we achieve good accuracy by incorporating different characteristics of several events into graphs with different node types and leveraging different types of graph links to express relationships between event characteristics, as well as relationships between events. In addition, the use of a GAT model enables the integration of a modified version of the
GNN Explainer algorithm to add the explainable component to the predictive model. In particular, the GNN Explainer algorithm is modified to disclose explainable information related to characteristics, events and relationships between events that  mainly influenced the prediction. Experiments with various benchmark event logs prove the accuracy of {\sf PROPHET} compared to several current state-of-the-art methods and draw insights from explanations recovered through the GNN Explainer algorithm.