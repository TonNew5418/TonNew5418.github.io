---
title: "SMILE: Infusing Spatial and Motion Semantics in Masked Video Learning"
collection: publications
category: conferences
permalink: /publication/SMILE
excerpt: 'This paper proposes SMILE, a self-supervised video learning method that improves semantic and motion representation by incorporating CLIP-guided spatial semantics and synthetic motion patterns, achieving state-of-the-art results across 7 datasets.'
date: 2025-06-13
venue: 'CVPR'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2025/papers/Thoker_SMILE_Infusing_Spatial_and_Motion_Semantics_in_Masked_Video_Learning_CVPR_2025_paper.pdf'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Masked video modeling, such as VideoMAE, is an effective paradigm for video self-supervised learning (SSL). However, they are primarily based on reconstructing pixellevel details on natural videos which have substantial temporal redundancy, limiting their capability for semantic representation and sufficient encoding of motion dynamics. To address these issues, this paper introduces a novel SSL approach for video representation learning, dubbed as SMILE, by infusing both spatial and motion semantics. In SMILE, we leverage image-language pretrained models, such as CLIP, to guide the learning process with their high-level spatial semantics. We enhance the representation of motion by introducing synthetic motion patterns in the training data, allowing the model to capture more complex and dynamic content. Furthermore, using SMILE, we establish a new self-supervised video learning paradigm capable of learning strong video representations without requiring any natural video data. We have carried out extensive experiments on 7 datasets with various downstream scenarios. SMILE surpasses current state-of-the-art SSL methods, showcasing its effectiveness in learning more discriminative and generalizable video representations.
