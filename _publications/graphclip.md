---
title: "GraphCLIP: Image-graph contrastive learning for multimodal artwork classification"
collection: publications
category: manuscripts
permalink: /publication/graphclip
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2009-10-01
venue: 'Knowledge-Based Systems'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://doi.org/10.1016/j.knosys.2024.112857'
citation: ' Scaringi, R., Fiameni, G., Vessio, G., Castellano, G (2025). &quot;GraphCLIP: Image-graph contrastive learning for multimodal artwork classification; <i>KBS</i>. 310 (112857).'
---

We present GraphCLIP, a novel contrastive learning framework for multimodal artwork classification that integrates visual and contextual information to improve predictive accuracy and interpretability. Traditional computer vision methods often fall short in visual arts, where context is crucial. GraphCLIP leverages image data and a Knowledge Graph to extract features from both perspectives. Evaluated on the $\mathcal{A}rt\mathcal{G}raph$ dataset,
with over 100,000 artworks in 32 styles and 18 genres, GraphCLIP outperforms existing models in singletask (up to +8% in F1-score) and multi-task settings (up to +6%), demonstrating robustness even with unseen classes. Additionally, visual and contextual qualitative explanations enhance model transparency. The versatility of GraphCLIP extends beyond art classification: its methodology can be adapted to other domains where integrating diverse data types is essential. (The code is publicly available at: [](https://github.com/CILABArtGraph/graphclip.git).)