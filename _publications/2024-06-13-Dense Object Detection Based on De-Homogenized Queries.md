---
title: "Dense Object Detection Based on De-Homogenized Queries"
collection: publications
category: manuscripts
permalink: /publication/2024-06-13-Dense Object Detection Based on De-Homogenized Queries
excerpt: 'Developing a novel end-to-end dense object detection method based on differentiated encoding, improving deduplication capability and detection accuracy while reducing model parameters. '
date: 2024-06-13
venue: 'Electronics 2024, 13(12), 2312'
paperurl: 'https://merry7cherry.github.io/cherry-Ma/files/electronics-13-02312.pdf'
citation: 'Huang, Y.; Ma, C.; Zhou, H.; Wu, H.; Yuan, G. Dense Object Detection Based on De-Homogenized Queries. Electronics 2024, 13, 2312. https://doi.org/10.3390/electronics13122312'
---

**Abstract**

Dense object detection is widely used in automatic driving, video surveillance, and other fields. This paper focuses on the challenging task of dense object detection. Currently, detection methods based on greedy algorithms, such as non-maximum suppression (NMS), often produce many repetitive predictions or missed detections in dense scenarios, which is a common problem faced by NMS-based algorithms. Through the end-to-end DETR (DEtection TRansformer), as a type of detector that can incorporate the post-processing de-duplication capability of NMS, etc., into the network, we found that homogeneous queries in the query-based detector lead to a reduction in the de-duplication capability of the network and the learning efficiency of the encoder, resulting in duplicate prediction and missed detection problems. To solve this problem, we propose learnable differentiated encoding to de-homogenize the queries, and at the same time, queries can communicate with each other via differentiated encoding information, replacing the previous self-attention among the queries. In addition, we used joint loss on the output of the encoder that considered both location and confidence prediction to give a higher-quality initialization for queries. Without cumbersome decoder stacking and guaranteeing accuracy, our proposed end-to-end detection framework was more concise and reduced the number of parameters by about 8% compared to deformable DETR. Our method achieved excellent results on the challenging CrowdHuman dataset with 93.6% average precision (AP), 39.2% MR−2, and 84.3% JI. The performance overperformed previous SOTA methods, such as Iter-E2EDet (Progressive End-to-End Object Detection) and MIP (One proposal, Multiple predictions). In addition, our method is more robust in various scenarios with different densities.

_**Keywords**: object detection; dense detection; DETR; transformer_
