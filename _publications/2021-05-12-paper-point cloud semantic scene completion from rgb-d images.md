---
title: "Point Cloud Semantic Scene Completion from RGB-D Images"
collection: publications
category: manuscripts
permalink: /publication/2021-05-12-paper-point cloud semantic scene completion from rgb-d images
excerpt: 'In this paper, we devise a novel semantic completion network, called point cloud semantic scene completion network (PCSSC-Net), for indoor scenes solely based on point clouds.'
date: 2021-05-12
venue: 'AAAI'
paperurl: 'http://xrmind-lab.github.io/files/point cloud semantic scene completion from rgb-d images.pdf'
citation: 'Zhang S, Li S, Hao A, et al. Point cloud semantic scene completion from rgb-d images[C]//Proceedings of the AAAI Conference on Artificial Intelligence. 2021, 35(4): 3385-3393.'
---

In this paper, we devise a novel semantic completion network, called point cloud semantic scene completion network (PCSSC-Net), for indoor scenes solely based on point clouds. Existing point cloud completion networks still suffer from their inability of fully recovering complex structures and contents from global geometric descriptions neglecting semantic hints. To extract and infer comprehensive information from partial input, we design a patch-based contextual encoder to hierarchically learn point-level, patch-level, and scene-level geometric and contextual semantic information with a divide-and-conquer strategy. Consider that the scene semantics afford a high-level clue of constituting geometry for an indoor scene environment, we articulate a semantics-guided completion decoder where semantics could help cluster isolated
points in the latent space and infer complicated scene geometry. Given the fact that real-world scans tend to be incomplete as ground truth, we choose to synthesize scene dataset with RGB-D images and annotate complete point clouds as ground truth for the supervised training purpose. Extensive experiments validate that our new method achieves the stateof-the-art performance, in contrast with the current methods applied to our dataset.
